# CONST

Las constantes son variables, pero a diferencia de las otras, no pueden ser reasignadas. Para crear una constante, usamos la palabra reservada `const`

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

Estas variables son importantes porque le dicen al navegador que esa variable no va a cambiar nunca y por tanto puede llevar a cabo ciertas optimizaciones. Si intentas reasignar el valor de una constante, obtendrás un error:

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

Como no se pueden reasignar, las constantes siempre deben ser inicializadas con algún valor. Esto es otra diferencia respecto a let, que no es necesario inicializarla con un valor.

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

Son muy útiles para almacenar valores que no van a cambiar. Siempre que puedas, procura usar constantes para que tu código sea más predecible.

