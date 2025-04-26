# ¿Cuáles son las diferencias entre const, let y var?

A la hora de crear programas, es vital poder almacenar la información para poder utilizarla en un futuro. En JavaScript, usamos variables para conseguirlo, y se pueden definir como un espacio reservado en la memoria que almacena un valor asociado a un identificador.

### Buenas prácticas para nombrar variables

En JavaScript, los nombres de las variables pueden contener letras, números y el guión bajo (\_). Además, el primer carácter del nombre de la variable no puede ser un número.

Es importante tener en cuenta que los nombres de las variables son sensibles a las mayúsculas y minúsculas, lo que significa que miVariable y mivariable son dos variables diferentes en JavaScript.

\


<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

También es importante que los nombres de las variables sean descriptivos. Por ejemplo, si queremos almacenar el nombre de un usuario, podemos llamar a la variable `userName`. De esta forma, cuando leamos el código, sabremos que la variable contiene el nombre de un usuario.\


<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

### Convenciones y nomenclaturas

En JavaScript, existen diferentes nomenclaturas para nombrar las variables: **camelCase, snake\_case y SCREAMING\_CASE.**

\
**camelCase** es la forma más común de nombrar las variables en JavaScript. Consiste en escribir la primera palabra en minúsculas y las siguientes palabras con su primera letra en mayúsculas.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

**snake\_case** es una forma de nombrar que consiste en escribir todas las palabras en minúsculas y separarlas con guiones bajos.

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

**SCREAMING\_CASE** es una forma de nombrar que consiste en escribir todas las palabras en mayúsculas y separarlas con guiones bajos.

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

### Tipos de Variables

En JavaScript, puedes declarar variables utilizando tres palabras clave principales:\


1. `var` : Tiene un alcance global o de función, lo que puede llevar a confusiones si no se usa correctamente. Es la más flexible de todas\

2. `let` : Permite declarar variables con un alcance de bloque, lo que significa que solo están disponibles dentro del bloque donde se declaran. Es más seguro y recomendado para la mayoría de los casos. \
   &#x20;&#x20;
3. `const` : Se utiliza para declarar variables que no se pueden reasignar. Esto significa que una vez que le asignas un valor, no puedes cambiarlo. Sin embargo, si el valor es un objeto o un array, puedes modificar sus propiedades o elementos.
