# ¿Qué es una función flecha?

Las funciones flecha son una forma más concisa de crear funciones en JavaScript, y se han vuelto muy populares en los últimos años debido a su sintaxis simplificada. Se introdujeron en ES6 (la versión 6 de JavaScript) y facilitan la escritura de funciones, especialmente cuando son funciones cortas o se usan como callbacks, pero son limitadas y no se puede utilizar en todas las situaciones

### Características principales

* Usan el símbolo `=>` (por eso se llama **flecha**).
* Son **más cortas** y **más fáciles de leer**.
* No tienen su propio `this` (esto es importante en algunos casos avanzados, pero no te preocupes mucho ahora).

### Sintaxis

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

Las funciones flecha son siempre funciones anónimas y function expressions. Esto significa que no tienen nombre y que se asignan a una variable.

En lugar de la palabra clave function, utilizamos una flecha `=>` para definir la función. También podemos omitir los paréntesis alrededor de los parámetros si solo tenemos uno:

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

### Ventajas de las funciones flecha

Las funciones flecha tienen varias ventajas sobre las funciones regulares en JavaScript. Algunas son:

* Sintaxis más concisa: la sintaxis de las funciones flecha es más corta y más fácil de leer que la sintaxis de las funciones regulares, especialmente cuando se trabaja con funciones de una sola línea.
* Return implícito: las funciones flecha pueden devolver el valor de la expresión sin usar la palabra clave return cuando son de una sola línea. Esto hace que las funciones flecha sean aún más cortas y más fáciles de leer.
* Funciones anónimas más legibles: las funciones flecha son una forma más legible y concisa de crear funciones anónimas en JavaScript, lo cual puede hacer que nuestro código sea más fácil de entender.

#### Return implícito:

Cuando una función flecha tiene una sola expresión, podemos omitir las llaves `{}` y la palabra clave `return` para hacerla aún más corta. Esto se conoce como `return` implícito. Vamos a pasar una función regular a una función flecha y vamos a ver cómo se ve finalmente con `return` implícito:

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

Como podemos ver, la función flecha con `return` implícito es mucho más corta y fácil de leer que la función regular. Esto es especialmente útil cuando estamos trabajando con funciones de una sola línea.

### Diferencias y limitaciones

* No tiene sus propios enlaces a this o super y no se debe usar como métodos.
* No tiene argumentos o palabras clave new.target.
* No apta para los métodos call, apply y bind, que generalmente se basan en establecer un ámbito o alcance
* No se puede utilizar como constructor.
* No se puede utilizar yield dentro de su cuerpo.
