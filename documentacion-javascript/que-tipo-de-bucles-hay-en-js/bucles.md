# bucles

Cuando hablamos de los bucles, existen dos instrucciones que pueden resultar bastante útiles en algunas situaciones.

### Saliendo del bucle con `BREAK`

Podemos controlar cuándo queremos salir de un bucle utilizando la palabra reservada break. Cuando el intérprete de JavaScript encuentra la palabra break, sale del bucle y continúa ejecutando el código que haya después.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

¿Cuál es el valor de `cuentaAtras` en este código? Veamos, el bucle estaba haciendo una cuenta atrás... pero le hemos dicho que cuando tuviese el valor 5 saliese del bucle. Por lo tanto, el valor de `cuentaAtras` es 5.

Usar break puede ser útil en bucles si queremos salir de ellos por alguna condición en concreto o para evitar justamente los bucles infinitos.

### Saltando una iteración con `CONTINUE`

Igual que tenemos la posibilidad de "romper" el bucle con break, también podemos saltarnos instrucciones específicas, es decir, si llega a esta instrucción el bucle se saltará lo que ponga a continuación y pasará a la siguiente instrucción del bucle.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

¿Qué aparece en la salida de la consola? El bucle está haciendo una cuenta atrás... pero le hemos dicho que si el número es par, se salte esa iteración y deje de ejecutar el código que le sigue. Por ello, los números pares no aparecen en la consola.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
