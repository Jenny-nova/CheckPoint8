# ¿Qué hace el operador de extensión en JS?

Cuando empiezas a programar en JavaScript, uno de los operadores más versátiles que encontrarás es el **operador de extensión** (`...`), también conocido como **spread operator**.\
Aunque parece simple, puede hacer varias cosas poderosas de forma muy sencilla.

Se usa para expandir elementos de un array o propiedades de un objeto en lugares donde se esperan cero o más argumentos, elementos o propiedades. Es muy útil para copiar arrays, combinar arrays, o copiar objetos de manera sencilla y elegante. Es una herramienta muy poderosa para trabajar con estructuras de datos en JavaScript.

### Ejemplo

si tienes un **array** y quieres copiarlo o agregar sus elementos a otro array, puedes usar el operador de extensión así:

```javascript
const array1 = [1, 2, 3];
const array2 = [...array1, 4, 5]; 

```

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

Útil para evitar modificar el array original.

Así como para **expandir listas de argumentos**, `...` puede ser usado en cualquier parte dentro del Array literal, y múltiples veces.

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

Y en **objetos**, también puedes usarlo para copiar propiedades:

```javascript
const obj1 = { a: 1, b: 2 };
const obj2 = { ...obj1, c: 3 }; // { a: 1, b: 2, c: 3 }

```

También puedes recoger elementos restantes (Rest Operator)

Cuando defines funciones o extraes datos de un array u objeto, `...` puede recolectar el resto de los elementos.

Aquí `...numeros` junta todos los argumentos en un solo array `numeros`.

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

### ¿Por qué es importante?

* Hace tu código más limpio y legible.
* Evita errores al copiar o modificar datos.
* Te prepara para trabajar con frameworks modernos como React, donde se usa muchísimo.

\
\
