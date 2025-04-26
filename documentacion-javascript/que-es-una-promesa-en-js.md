# ¿Qué es una promesa en JS?

Una **promesa** en JavaScript es un objeto que representa el resultado eventual de una operación asíncrona. Es decir, cuando realizamos tareas que toman tiempo, como solicitar datos a un servidor, leer archivos o realizar cálculos complejos, no queremos que nuestro programa se quede esperando a que esa tarea termine. En su lugar, usamos promesas para gestionar esas operaciones de manera eficiente y ordenada.

### ¿Por qué usar promesas?

Antes de las promesas, las operaciones asíncronas se manejaban con callbacks, lo que podía hacer que el código fuera difícil de leer y mantener, especialmente cuando había muchas tareas encadenadas (el famoso "callback hell").

&#x20;Las promesas ofrecen una forma más clara y estructurada de manejar estas tareas, permitiendo escribir código que se lee de forma secuencial y fácil de entender.

### &#x20;¿Cómo funciona una promesa?

Una promesa puede estar en uno de estos tres estados:

1. **Pendiente** : La operación aún no ha terminado.
2. **Cumplida** : La operación terminó con éxito y tenemos un resultado.
3. **Rechazada** : La operación falló y tenemos un error.

Cuando creamos una promesa, le decimos qué hacer cuando se cumple o se rechaza, usando los métodos `.then()`y `.catch()`.

### Sintaxis

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

`new Promise()` crea una nueva promesa. Dentro de los paréntesis, pasamos una función que recibe dos parámetros: **resolve** y **reject**.

`resolve()` se llama cuando la operación asíncrona fue exitosa, y pasa un valor que será recibido por los métodos `.then()`.

`reject()`se llama si hubo un error, y ese error será recibido por los métodos `.catch()`.

Luego, para manejar el resultado de la promesa, usamos:

\


<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

### Ejemplo

Supongamos que queremos simular una tarea que tarda en completarse, como obtener datos de un servidor:

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

En este ejemplo, la promesa simula una tarea que tarda 2 segundos.

* Si todo va bien (éxito es true), se llama a resolve() y el .then() recibe el resultado.
* Si algo sale mal (éxito es false), se llama a reject() y el .catch() captura el error.

### Ventajas de usar promesas

* **Código más limpio y legible**: Puedes encadenar varias operaciones asíncronas usando .then().
* **Manejo centralizado de errores**: Con .catch(), puedes gestionar errores en un solo lugar.
* **Facilita el uso de async/await:** Las promesas permiten usar la sintaxis moderna async/await, que hace que el código asíncrono parezca sincrónico y aún más fácil de entender.

