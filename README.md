# AW_Pasatiempos
Práctica Pasatiempo en Cascada prácticamente completa
Se pide desarrollar, de forma individual, una página web que permita resolver un pasatiempo del tipo En Cascada. En la figura 1 puede verse un ejemplo de ese pasatiempo y la  descripción de  su resolución.

La página web deberá permitir:

* Mostrar de  forma completa, con el tablero, las pistas y  la descripción,  un pasatiempo En Cascada. Puede ser el que se ofrece u otro seleccionado por el alumno.
Permitir al usuario resolver en  la propia página web el pasatiempo. En cada casilla sólo podrá ir una letra.
* La página web cargará asíncronamente un diccionario de palabras dado en el fichero diccionario.txt que residirá en el servidor, y comprobará que todas las palabras que el usuario vaya completando existen en el diccionario.  Si no es así lo  avisará mediante una alerta.
* Si el usuario permite almacenamiento local (cookies) se podrá guardar una resolución parcial para ser recuperada posteriormente. Para ello se identificará de  forma única el pasatiempo y se usará algún mecanismo  de almacenamiento local. Si el usuario lo desea se borrará ese almacenamiento para  dejar limpio el pasatiempo.

* La página podrá dar hasta tres pistas como ayuda  a la resolución del pasatiempo. Cada pista consistirá en  que el usuario  pone  una  serie de letras y la página le da una  lista con las palabras que existen en el diccionario que contienen exactamente esas letras.

Se entregarán al menos  el fichero html y el fichero css que resuelven el problema. Si se desea se podrá entregar algún fichero más como imágenes. El  diccionario no se entregará.

CAMBIO EN LAS ESPECIFICACIONES: El diccionario se deberá cargar desde  la dirección https://ordenalfabetix.unileon.es/aw/diccionario.txt.

Para realizar la petición asíncronada se deberá de tener en cuenta que será una petición CORS (https://developer.mozilla.org/es/docs/Web/HTTP/CORS). Para llevarla a cabo correctamente se debe de tener en cuenta:

La página html tiene que tener el atributo global crossorigin="anonymous" (https://developer.mozilla.org/es/docs/Web/HTML/Attributes/crossorigin)

La petición debe ser simple o segura, según la definición que puede verse en este enlace (https://javascript.info/fetch-crossorigin)
