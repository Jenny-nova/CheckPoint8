# Resumen

**var**: Es la forma clásica de declarar variables en JavaScript. Tiene un alcance (scope) global o de función, lo que significa que si la declaras dentro de una función, solo existe allí. Sin embargo, puede causar problemas por su comportamiento de hoisting (se eleva al inicio del contexto), lo que a veces lleva a errores difíciles de detectar.

**let**: Es una forma más moderna y recomendada para declarar variables. Tiene un alcance de bloque (block scope), lo que significa que solo existe dentro del bloque en el que la declaras (por ejemplo, dentro de un if, for, etc.). Además, no se hoiste de la misma manera que var, lo que hace que su comportamiento sea más predecible.

**const**: También tiene alcance de bloque, pero la diferencia principal es que una vez que asignas un valor a una variable declarada con const, no puedes volver a cambiarla. Es ideal para declarar constantes o valores que no deben modificarse. Sin embargo, si la variable es un objeto o un array, puedes modificar sus propiedades o elementos, pero no puedes volver a asignar toda la variable.

### Buenas Prácticas

\- **Nombres Descriptivos**: Usa nombres que describan el contenido de la variable, como `nombreUsuario` o `totalVentas` , para que tu código sea más legible.



\- **Alcance**: Prefiere `let` y `const` sobre `var` para evitar problemas de alcance y mejorar la claridad de tu código.

\
\- **Inmutabilidad**: Usa `const` siempre que sea posible para evitar cambios accidentales en variables que no deberían cambiar.
