# ¿Qué es la programación orientada a objetos?

La **Programación Orientada a Objetos** (POO, o en inglés OOP) es un estilo de programación muy utilizado, donde creas y utilizas estructuras de datos de una forma muy similar a la vida real, lo que facilita considerablemente la forma de planificar y preparar el código de tus programas o aplicaciones.

El concepto de **orientación a objetos** se ve muy claro cuando tenemos en nuestra mente el concepto de **Clase**. Todos los elementos relacionados con esa Clase los vamos a incluir en su interior. Por un lado, las variables y constantes que teníamos «sueltas» en nuestro programa, las agruparemos dentro de una clase, donde también incluiremos todas las funciones.

Las variables y constantes incluidas en una clase se denominan **propiedades**, y se utilizan para guardar información relacionada (se suele denominar estado).&#x20;

Por otro lado, las funciones incluidas en una clase se denominan **métodos** y se utilizan para realizar una acción relacionada con la clase.

### Conceptos clave de POO en JavaScript

1. **Clases**: Son como planos o moldes para crear objetos. Definen qué propiedades (datos) y métodos (funciones) tendrán los objetos que crees a partir de ellas.
2. **Objetos**: Son instancias de clases. Cada objeto puede tener sus propios valores para las propiedades definidas en la clase.
3. **Propiedades**: Son los datos que describen al objeto. Por ejemplo, un objeto "coche" puede tener propiedades como "color", "marca" y "modelo".
4. **Métodos**: Son funciones que realizan acciones con los objetos. Por ejemplo, un método "arrancar" en un objeto "coche" podría encender el motor.

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### Ejemplo

Definimos una clase llamada Persona:

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

Luego creamos un objeto (instancia) de la clase Persona:

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

Usamos el método del objeto, con nuestra función saludar:

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

En la consola nos aparecerá:

<figure><img src="../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

### Beneficios

1. **Organización del código**: La POO permite estructurar el código en objetos que representan entidades del mundo real, lo que hace que sea más fácil de entender y mantener.
2. **Reusabilidad**: Puedes crear clases que sirvan como plantillas y reutilizarlas en diferentes partes del programa o incluso en otros proyectos, ahorrando tiempo y esfuerzo.
3. **Facilidad de mantenimiento**: Al estar el código organizado en objetos y clases, es más sencillo realizar cambios o corregir errores sin afectar otras partes del programa.
4. **Encapsulamiento**: La POO permite ocultar detalles internos de los objetos, exponiendo solo lo necesario, lo que mejora la seguridad y la integridad del código.
5. **Herencia**: Puedes crear nuevas clases basadas en clases existentes, lo que facilita extender funcionalidades sin duplicar código.
6. **Polimorfismo**: Permite que diferentes objetos puedan ser tratados de manera similar, lo que hace que el código sea más flexible y adaptable.
