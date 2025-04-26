# ¿Qué hacen async y await por nosotros?

`async` y `await` son palabras clave que hacen que trabajar con promesas sea más fácil y parecido a escribir código normal, como si fuera sincrónico (paso a paso). Nos ayudan a escribir código más limpio y fácil de entender.

* **`async`** convierte una función normal en una **función asíncrona**, lo que significa que automáticamente devolverá una **promesa** (en JS) o un **objeto awaitable** (en Python). Es decir, algo que "promete" un resultado en el futuro, no necesariamente de inmediato.
* **`await`** se usa **dentro** de una función `async` para **pausar** la ejecución de esa función hasta que la promesa/resultado esté listo. Es como decir: _"espera aquí hasta que esto termine"_, pero sin bloquear todo el programa.

### Cómo usar async/await

1. Declara una función como async: Esto indica que dentro de esa función podrás usar await.
2. Usa await antes de una promesa: Esto hace que la función espere a que la promesa se resuelva antes de continuar.

### Ejemplo

Supongamos que quieres obtener datos de una API y mostrarlo:

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

La función **mostrarDatos** es **async**, así que podemos usar **await** dentro de ella. Cuando llamamos a `await obtenerDatos()`, la función se detiene en ese punto hasta que la promesa se resuelve. Una vez que los datos están listos, se muestran en la consola.

### ¿Qué nos aporta su uso?

* Más claridad: en lugar de hacer `.then()` y anidar callbacks (lo que puede volverse caótico), escribimos código que parece sincrónico pero en realidad es asíncrono.
* Control de flujo: podemos manejar esperas, errores y secuencias de tareas de forma mucho más limpia.

### &#x20;Resumen:

Usa **async** para definir funciones que trabajan con promesas.

Usa **await** para esperar a que una promesa se resuelva antes de continuar. Esto hace que tu código sea más fácil de leer y entender, como si fuera paso a paso.
