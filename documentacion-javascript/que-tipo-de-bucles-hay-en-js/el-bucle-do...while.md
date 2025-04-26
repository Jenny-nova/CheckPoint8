# El bucle do…while

Aunque no es muy famoso ni muy utilizado, es interesante que sepas que existe en JavaScript un bucle que se ejecuta al menos una vez, y luego se repite mientras se cumpla una condición.

El bucle `do/while` es similar al `while`, pero hay una diferencia clave: el bloque de código se ejecuta al menos una vez, incluso si la condición es falsa desde el principio.

La estructura básica es:

```javascript
do {
   // Código a ejecutar
} while (condición);

```

### Ejemplo de uso de DO…WHILE

Vamos a imprimir los números del 0 al 4, nuestro código sería:

```javascript
let i = 0;
do {
  console.log(i);
  i++;
} while (i < 5);

```

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Si en cambio, nuestra variable seria (i =5), sabemos que no cumple nuestra condición (while i < 5), pero al menos nuestro código se ejecutará una vez:

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

### Beneficios&#x20;

#### while:&#x20;

* Verifica la condición antes de ejecutar el bloque de código. Si la condición es falsa desde el principio, el código no se ejecuta.
* Ideal cuando no sabes exactamente cuántas veces se debe repetir, solo quieres que siga mientras se cumpla una condición.
* Es útil para bucles que dependen de condiciones dinámicas que cambian durante la ejecución.
* Es sencillo y fácil de entender para ciclos que dependen de una condición que puede variar.

#### do/while:&#x20;

* Se usa cuando quieres que el código dentro del bucle se ejecute al menos una vez, sin importar la condición.
* Es útil en situaciones donde necesitas realizar una acción inicial y luego verificar si se debe repetir.
* Permite que la condición se evalúe después de la ejecución del bloque, garantizando al menos una ejecución.
