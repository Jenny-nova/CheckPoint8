# ¿Qué es la deconstrucción de variables?

La **deconstrucción** de variables en JavaScript, también conocida como "**desestructuración**", es una característica muy útil que te permite extraer valores de arreglos u objetos y asignarlos a variables de manera sencilla y clara. En lugar de acceder a cada propiedad o elemento uno por uno, puedes "deconstruir" todo en una sola línea, lo que hace que el código sea más limpio y fácil de entender.

Por ejemplo, si tienes un objeto con varias propiedades, puedes extraer esas propiedades en variables individuales sin tener que acceder a ellas una por una. Lo mismo pasa con arreglos, donde puedes asignar sus elementos a variables específicas en una sola línea.

También nos permite recuperar el valor de una propiedad y guardarlo en una variable de una. Lo importante es que tengamos en cuenta que la variable que se creará tendrá el mismo nombre que la propiedad que estamos recuperando.&#x20;

Se usa principalmente cuando quieres extraer datos de objetos o arreglos de manera rápida y clara, por ejemplo, al trabajar con respuestas de APIs, objetos complejos o listas de datos. Es muy útil en situaciones donde necesitas acceder a varias propiedades o elementos de forma frecuente y quieres mantener tu código limpio y organizado.

### Sintaxis y ejemplo

Las expresiones de objetos y arreglos literales proporcionan una manera fácil de crear paquetes de datos

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

La desestructuración utiliza una sintaxis similar, pero en el lado izquierdo de la asignación para definir qué valores desempacar de la variable origen.

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

### A continuación mostramos varios ejemplos donde nos puede ser útil usar la deconstrucción&#x20;

#### Cuando queremos intercambiar los valores de dos variables, podemos usar una expresión de desestructuración.

```javascript
let playerOne = 'Tiffany';
let playerTwo = 'Kristine';

[playerOne, playerTwo] = [playerTwo, playerOne];

console.log(`
Player One: ${playerOne}
Player Two: ${playerTwo}
`);

```

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

#### También podemos implementar la desestructuración en matrices:

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

#### Podemos encontrarnos con desestructuración combinada de arreglos y objetos:

La desestructuración de arreglos y objetos se puede combinar. Supongamos que deseas manipular el tercer elemento del siguiente arreglo props, y luego deseas la propiedad name en el objeto, puedes hacer lo siguiente:

<figure><img src="../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

### Ventajas

* Código más legible y conciso: reduces la cantidad de líneas y mejora la claridad.
* Facilita la asignación de múltiples valores: puedes extraer varias propiedades o elementos en una sola operación.
* Mejora la eficiencia: al reducir la repetición de código, facilita el mantenimiento y la depuración.
