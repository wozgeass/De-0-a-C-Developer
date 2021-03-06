# Buenas practicas de programación

Como lo mencione al principio, básicamente en este libro nos centraremos en aprender el lenguaje **C** para saber el **como** contribuir o empezar algún proyecto *open source*, aun hoy día existen tantas aplicaciones que usan el lenguaje **C** y es casi vital que sepamos programar en este lenguaje.

Pero muchos de nosotros no le tomamos la importancia necesaria a este tema hasta que intentamos contribuir en algún proyecto ya existente, obviamente al no llevar buenas practicas tendemos a ser regañados y en muchos casos humillados.

Algo que quiero que tomes a consideración es que en el mundo *Linux* la gran mayoría de usuarios que dicen usarlo son solo usuarios finales y cuando llegas a toparte con algún desarrollador son en muchos caso algo gruñones. Pero si quieres trabajar en este medio nunca tomes nada personal.

Y seguramente te vas a preguntar, por que razón varios desarrolladores son gruñones, bueno la respuesta a esto es bastante simple, lo pondré de la siguiente manera:

> En muchos casos la mayoría de personas que aspiran a convertirse en desarrolladores suelen pedirles ayuda preguntando cosas sin antes consultar la documentación o buscar si en algún otro lado alguien mas llego a la respuesta, básicamente les gusta lo fácil y los desarrolladores están tan ocupados tratando de solucionar un problema que simplemente les da flojera contestar o te dicen que leas el manual pero con mas palabras antisonantes.

Lo primero que tienes que entender es que a los desarrolladores les gustan los problemas realmente complejos y las buenas preguntas que les hagan pensar en ellos. De no ser así no estarían en donde están. Si les proporcionas preguntas interesante te lo agradecerán mucho inclusive podrían empezar a respetarte; ya que las buenas preguntas suponen un estimulo y un regalo. Las buenas preguntas ayudan al desarrollador a mejorar la comprensión, y a menudo revelan problemas que podrían no haber percibido o en los que de otra manera no habrían reparado. En el mundo del desarrollador las buenas preguntas podrían entenderse como un sincero cumplido.

Por otro lado como se relaciona esto con las buenas practicas en la programación, llegado a este momento ahora supondremos que intentas realizar una parche de tu programa favorito, pero tu nunca pusiste atención ni leíste su estándar de codificación y en donde aprendiste a programar nunca usaste estas buenas practicas. Al intentar subir tu cambio los desarrolladores verán que no cumple el estándar y aun que haga lo que se supone que debe hacer, no lo incluirán dentro del código principal.

No te quiero engañar este capitulo no te hará mejor programador solo intentara mostrarte algunos conocimientos de los principios, patrones y heurísticas propias de haber sufrido en carne propia la necesidad de usar buenas practicas. También no sera nada fácil si es que ya tienes un estilo de programación propio, difícil pero no imposible. Soy de la idea de que las cosas que experimenta uno mismo son las que mas nos permiten aprender por lo que en esta parte nos centraremos en ver el **como** de una manera practica.

Pero todo esto requiere algo mas que conocer principios y patrones, deberemos practicarlo y fallar y volver a intentarlo, incluso debes ver como otros practican y fallan recuperándose al paso, o ver el precio que pagan por tomar decisiones equivocadas.

Si eres un programador con algunos años de experiencia, probablemente ya sufriste los desastres cometidos por otros en el código. En un periodo de algunos años los equipos que avanzaban a pasos agigantados pueden acabar a pasos de tortuga. Cada cambio en el código afecta a dos o tres partes del mismo. Ningún cambio sera trivial. Y para ampliar o modificar el código sera necesario comprender todos los detalles, efectos y consecuencias, para de ese modo poder añadir nuevos detalles, efectos y consecuencias. Con el tiempo, el desastre aumenta de tal modo que no se puede remediar.

Al aumentar este desastre, la productividad del equipo disminuye y acaba por desaparecer. Al reducirse la productividad, el encargado hace lo único que puede; ampliar la plantilla del proyecto con la esperanza de aumentar la productividad. Pero esa nueva plantilla no conoce el diseño del sistema. No conoce la diferencia entre un cambio adecuado al objetivo de diseño y otro que lo destroce. Por tanto todos se encuentran sometidos a una gran presión para aumentar la productividad. Por ello, cometen mas errores, aumentando el desastre y la productividad se acerca a cero cada vez mas y mas.

En ultima instancia, el equipo se rebela. Informan al encargado que no pueden seguir trabajando con ese código. Exigen un cambio de diseño. La dirección no requiere invertir en un cambio de diseño del proyecto pero no pueden ignorar el bajo nivel de productividad. Acaban por ceder a las exigencias de los programadores y autoriza el gran cambio de diseño. Se selecciona un nuevo equipo. Todos requieren formar parte del nuevo equipo por ser lienzo en blanco. Pueden empezar de cero y crear algo realmente bello, pero solo los mejores serán elegidos para el nuevo equipo. Los demás deben continuar con el mantenimiento del sistema actual.

Ahora los 2 equipos compiten. El nuevo debe crear un sistema que haga lo que el antiguo no puede. Ademas, debe asumir los cambios que continuamente se aplican al sistema antiguo. El encargado no sustituirá el sistema antiguo hasta que el nuevo sea capaz de hacer todo lo que hace el antiguo.

Esta competición puede durar mucho tiempo. Y cuando acaba, los miembros originales del equipo se encuentran trabajando en otras empresas y los miembros actuales exigen un cambio de diseño del nuevo sistema por que es un desastre.

Si ya sufriste alguna fase de esta breve historia, ya sabrás que dedicar tiempo a que el código sea correcto no solo es rentable, es una cuestión de supervivencia profesional.

Imaginemos que creemos que las buenas practicas no son un obstáculo significativo. Imaginemos también que aceptamos que la única forma de avanzar es mantener esas buenas practicas. Entonces te preguntaras como puedo crear buen código. No tiene sentido intentar crearlo si no sabemos lo que es. La mala noticia es que crear buen código  es como pintar un cuadro. Muchos sabemos si un cuadro se ha pintado bien o no, pero reconocer la calidad de una obra no significa que podamos pintar. Por ellos, reconocer buen código no significa que sepamos como crearlo.

Un programador sin este sentido puede reconocer el desastre cometido en un modulo pero no saber como solucionarlo. Y un programador con este sentido vera las posibles opciones y elegirá la variante optima para definir una secuencia de cambios.

> **En definitiva, un programador que tengas buenas practicas es un artista que puede transformar un lienzo en blanco en un sistema de código elegante.** 

Y este es uno de los motivos por el que los proyectos *open source* han logrado sobrevivir tantos años, inclusive al pasar a través de encargados diferentes. *Linux* y muchos proyectos son muestra de ello.

## Nombres consistentes

Por lo general al momento de codificar algo, asignamos nombre a archivos, carpetas y archivos. Usamos nombres constantemente. Por ello, debemos hacerlo bien. 

Es fácil afirmar que los nombres deben revelar nuestras intenciones. Lo que quiero recalcar es la importancia de hacerlo. Elegir nombres correctos lleva tiempo pero también ahorra trabajo. Por ello, prestar atención a los nombres es vital.

El nombre de una variable, función, o clase debe responder una serie de cuestiones básicas. Debe indicar por que existen, que hace y como se usa. Si un nombre requiere un comentario, significa que no revela su contenido.

> Incorrecto:

```C
int d;  // variable que indica la edad
```

> Correcto:

```C
int edad;
```

Como viste arriba el nombre de la variable "d" no indica nada. No evoca la sensación de un valor que pueda describir mi edad.

Otro mejor ejemplo podría ser el siguiente:

```C
int edadDias;
int edadHoras;
int edadSegundos;
int edadAños;
```

Debes evitar dejar pistas falsas el significado del código, cuyo significado se aleje del que pretendemos. Por ejemplo:

```C
int aix;
int hp;
int oracle;
int solaris;
```
 
Que son nombres de variables pobres ya que son los nombres de otros sistemas operativos. 

Gran parte de nuestro cerebro se dedica al concepto palabra. Y, por definición, las palabras son pronunciables. Seria una pena malgastar esa parte de nuestro cerebro dedicada al lenguaje hablado. Por tanto es importante también usar nombres que sean pronunciables. Esta es una actividad importante, ya que la programación es una actividad social.

> Incorrecto:

```C
int vsdincper;  //Variable que guarda solo el día del nacimiento de la persona
```

> Correcto:

```C
int diaNacimiento;
```

Como puedes ver quizá sea un poco grande pero esa variable al leerla es fácil y te dice que valor guarda.

Evita usar la misma palabra para 2 fines distintos. Si aplicas la regla de una palabra por conceptos, acabaras con muchos elementos que por ejemplo tengan una palabra *agregar*. Mientras las listas de parámetros y los valores devueltos de las distintas funciones *agregar* sean semánticamente equivalentes, no hay problema. Sin embargo podrías usar la palabra *agregar* por motivos de coherencia, aunque no sea en el mismo sentido. Imagina que hay varias funciones en las que *agregar* puede crear un nuevo valor sumando variables o concatenando 2 cadenas. Imagina ahora creamos una nueva función que añade una parámetro a una colección. Parece coherente ya que hay muchas otras funciones *agregar*, pero en este caso hay una diferencia semántica, de modo que debemos usar un nombre como *insertar* o *añadir*. Ten en consideración que como desarrolladores y autores de algún programa, nuestro objetivo es facilitar la compresión del código.
  
Recuerda que las personas que quizás vayan a leer tu código serán programadores. Por ello, es recomendable usar términos matemáticos, algoritmos, nombres de patrones y demás. 

Algunos nombres tienen significado por si mismos, pero la mayoría no. Por ello, debemos incluirlos con un contexto, variables, funciones y espacios de nombres con nombres adecuados.
Cuando todo lo demás falle, pueden usarse prefijos como ultimo recurso.

Imaginemos que tenemos la variable `primerNombre`, `ultimoNombre`, `calle`, `numeroCasa`, `ciudad`, `estado`, `codigoPostal`. Si las combinamos, es evidente que forman una dirección. Pero si las variable `state` se usa de forma aislada en una función, ¿Sabríamos que es parte de una dirección? lógicamente podemos añadir contextos por medio de prefijos: `agregarPrimNombre`,  `agregarUltimNombre`, `agregarEstado`. Al menos si los lectores del código comprenderán que estas variables forman parte de una estructura mayor.

## Manejo de las funciones

Desde los inicios de la programación, creábamos sistemas a partir de rutinas y subrutinas. Después de la época de **Fortran** y **PL/1**, se creaban sistemas con programas, subprogramas y funciones. En la actualidad, solo las funciones han sobrevivido. Son la primera linea organizativa en cualquier programa en varios proyectos *Open Source*.

> La primera regla de las funciones es que deben ser de tamaño reducido. 

> La segunda es que deben ser todavía mas reducidas.

Quizás no sea una afirmación que pueda justificar. Del mismo modo no puedo mostrar referencias a estudios que demuestren que las funciones muy reducidas sean mejores. Lo que si puedo afirmar es que durante casi 7 años he creado funciones de diferentes tamaños. Desde monstruosas funciones de 300 a 400 lineas a funciones de 30 a 100 lineas. Esta experiencia me ha demostrado, mediante ensayo y error, que las funciones deben ser muy reducidas.

En la década de los 80's se decía que una función no debía superar el tamaño de una pantalla. Que por aquellos tiempos tenían 24 lineas por 80 columnas. En la actualidad, con una fuente mínima y un monitor de gran resolución, se puede ver 180 caracteres por lineas y 120 lineas o mas en monitores 4k.

Lo que nos deja con la siguiente interrogante:

> ¿Qué tamaño mínimo debe tener una función?
 
Quizás para responder esta interrogante debas considerar una de las premisas de **UNIX**, pero modificada un poco para entender este contexto:

> Que cada función solo debe hacer una cosa. Debe hacerlo bien y debe ser lo único que haga.

De igual manera que las variables las funciones necesitan nombres consistentes. Cuanto mas reducida y concreta es una función, mas sencillo sera elegir un nombre descriptivo. No temas a los nombres extensos. En muchos casos un nombre extenso es preferible sobre uno breve y enigmático. Lo mejor seria usar una convención de nombres que permita leer varias palabras en los nombres de la funciones y usa esas palabras para asignar a la función un nombre que describa su cometido.

> Correcto:

```C
int sumaEnteros()
```

> Incorrecto:

```C
int suEN()
```

La elección de nombres descriptivos clarifica el diseño de las funciones y le permite mejorarlos. Se coherente con los nombres. Eso quiere decir que uses las mismas frases, sustantivos y verbos en los nombres de función que elijas para las funciones.

## Argumento de funciones

El numero ideal de argumentos para una función es lo menor que se pueda. Ya que los argumentos son todavía mas complicados desde un punto de vista de pruebas. Imagina la dificultad de crear todos los casos de prueba para garantizar el funcionamiento de las distintas combinaciones de argumentos. Si no hay argumentos, todo sera mas sencillo. Si hay uno, no es demasiado difícil. Con 2 o 3 argumentos el problema es mas complejo. Con mas de 3 argumentos, probar cada combinación de valores adecuados es todo un reto. Los argumentos de salida son mas difíciles de entender que los de entrada. Ya que al leer una función, estamos acostumbrados al concepto de información añadida a la función a través de argumentos y extraída a través de un valor de retorno. No esperamos que la información se devuelva a través de los argumentos. Por ellos, los argumentos de salida suelen obligarnos a realizar una comprobación doble.

Hay 2 motivos principales para pasar un solo argumentos a una función.




  
  
  
  








