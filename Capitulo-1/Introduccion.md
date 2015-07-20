# Introducción.
Cuando ocupas una computadora siempre te cuestionas que es lo que la hace funcionar, como es que puedes hacer tu trabajo. Para todo esto es importante tener nociones de programación, ya que siempre podremos encontrarnos con distintos problemas que como tales son muy difíciles de solucionar.

En muchos de estos casos el aprender un lenguaje de programación nos ayuda a ocupar el poder de procesamiento de la computadora para la solucion de estos problemas aparentemente imposibles de solucionar, por otra parte te va a permitir experimentar el gozo de haber creado algo por mismo o inclusive el mismo gusto pero de haber contribuido a algún proyecto Open Source.

Cabe destacar que la complejidad de la programación dependerá del problema que se trate de solucionar, comprender que toda esta idea de poder dar solución a problemas con mayor rapidez y eficacia se debe en gran parte a los avances y progresos en electrónica, matemáticas, física, etc.

En mi opinión la programación no es algo tan difícil, para muchos de nosotros que no tuvimos ciertas nociones, empezar con algo así no fue fácil, pero no por que sea muy complicado si no mas bien por que tuvimos un mal comienzo o quizás quisimos correr en lugar de iniciar tranquilamente.

Un poco mas tarde me di cuenta que lo que distingue a muchos programadores de otros es su creatividad, para poder iniciar el desarrollo de algo tan simple o tan complejo como su mente visualize.

Por lo que la programación es una disciplina que requiere simultáneamente del uso de cierto grado de creatividad, un conjunto de conocimientos técnicos asociados y la capacidad de operar constantemente con abstracciones (tanto simbólicas como enteramente mentales).

La creatividad necesaria para programar no se diferencia demasiado de aquella utilizada para producir textos. Sin embargo, lo que hace a la programación algo especial es que requiere emplear un conjunto de conocimientos técnicos asociados a la manipulación de las computadoras. Esto agrega un grado notable de rigurosidad a esta actividad, ya que no podemos programar sin tener en cuenta este aspecto. Por otra parte, al poseer una naturaleza ligada a la resolución de diferente problemas del mundo real, se requiere de una capacidad de abstracción que permita operar sin que los conocimientos técnicos limiten al programador a resolver adecuadamente dichos problemas.

Por ejemplo actividades que requieren:
- Un uso intensivo de la creatividad son relacionadas comúnmente con el Arte.
- Conocimientos técnicos profundos son los relacionados con la medicina, electrónica y química.
- Operar continuamente en abstracto son las relacionadas con filosofía, lógica y matemáticas.

A lo largo de la vida seguiremos enfrentando continuamente con todo tipo de problemas. Para ellos nos valdremos de distintas herramientas, que combinadas de maneras innovadoras ampliaremos el espectro de soluciones y vuelven factible el desarrollo de cualquier programa.

Algo muy cierto es que a los que les guste la programacion se podrán dedicar a construir programas, mantenerlos o contribuir a diversos Proyectos y siempre habrá mercado para esas personas.

## Conceptos de la programación.

Lo que nos lleva a definir formalmente que es un programa:

> Un Programa es una descripción ejecutable de soluciones a problemas computacionales, es decir, un texto descriptivo que al ser procesado por una computadora da solución a un problema propuesto. De esta manera, la parte descriptiva de los programas es el texto que el programador le provee a la computadora.

Y como dijimos antes las descripciones dadas por los programas pueden estar escritas con diferentes símbolos y para diferentes propósitos.

Cuando el código consiste mayormente de palabras y nociones que son mas sencillas para que manejen las personas, con el objetivo de que puedan entender y construir los programas, hablamos de un lenguaje de **Alto Nivel**, y al código resultante lo llamaremos **código de fuente**.

Cuando el código consiste mayormente de números y símbolos de difícil compresión para las personas, pero de rápida ejecución por una maquina, hablamos de un lenguaje de **bajo nivel**, y al cdigo resultante lo llamamos **codigo objeto** o **codigo ejecutable**. Por lo que hablariamos de un **alto nivel de abstraccion** cuando nos referíamos a la abstracciones mas cercanas a las ideas del problema a ser solucionado, a la mente de los programadores; y de **bajo nivel de abstracción** cuando nos refiramos a abstracciones mas cercanas a las ideas relacionadas a la forma de funcionamiento de las computadoras.

Es importante observar que tanto el código fuente como el código ejecutable están conformados por símbolos, y en este sentido es correcto llamar a ambos programas. Esto suele crear cierta confusión, pues entonces  la palabra programa se utiliza para dos propósitos diferentes:

1. El código que escribe el programador.
2. El código que ejecuta la computadora.

El primer punto sera el punto de estudio en este libro y el segundo es el resultado de varios procesos de traducción y compilación sobre el código fuente, que veremos un poco mas adelante en un apartado especial.

Si bien cuando escribimos el código fuente de un programa utliizamos símbolos como los del lenguaje natural, este texto debe ser capaz de poder ejecutarse por medio de la traducción que realiza nuestro compilador. Siendo esta característica la que hace que los programas se diferencien de otros textos, ya que no cualquier texto es ejecutable por una computadora. Lo hace a un texto ejecutable es mas bien su *sintaxis dura*, que no es mas que un conjunto de reglas estrictas de un determinado lenguaje de programación. con las que se escribe el código fuente.

> Los programadores tienen que balancear dos mundos bien diferente: un mundo de estructura y un mundo de imaginacion. Creando conceptos abstractos usando lenguajes de programacion muy estructurados.
[Programmer-Creativity-Boost](http://lifedev.net/2008/07/programmer-creativity-boost/)

## Lenguajes de Programacion.
Cuando programamos, no podemos utilizar el lenguaje natural con que nos comunicamos cotidianamente. Por el contrario, se emplea un lenguaje que un interprete o un compilador sea capaz de traducir a lenguaje maquina.

> Un lenguajde de programacion es una serie de reglas que establecen que descripciones seran aceptadas y ejecutadas y cuales no tienen sentido para el mecanismo de ejecucion provisto por la computadora.
Ademas, estas reglas estan diseñadas de manera composicional, para que sea sencillo construir programas de mayor envergadura.

En actualidad existe un gran numero de lenguajes de programacion, de caracteristicas sumamente diferentes y que emplean diferentes enfoques con lso que podemos programar. Cada lenguaje depende de un conjunto de ideas que guian, como su proposito final, la forma en que codificamos la descripcion que otorgaremos a la computadora. Ya que esta forma viene dada por las reglas que definen como se combinan los elementos que el lenguaje de programacion provee al programador.

A su vez, algunos lenguajes de programacion estan pensados para volcar mejor las ideas abstractas que el programador intenta emplear. Esto se conoce como lenguaje de **alto nivel**, ya que intentan, con cierto grado de eficacia, soslayar aquellas tareas que la computadora requiere realizar para que el programa cumpla con sus objetos. Pero tambien existen existen lenguajes de **bajo nivel**, que no hacen definir un mayor o menor medida cada paso que el programa seguira, y por ende, estan ligados a la naturaleza operacional de la computadora. Esta denominacion (**Bajo y Alto**) surge de la idea de imaginar que la computadora es la base fundacional sobre la que los programas ejecutan, y que de las ideas abstractas se van construyendo sobre ellas. Justamente denominados a un lenguaje de mas **alto nivel** de abstraccion cuanto mas lejos de la base se encuentra, o sea, cuanto mas abstracto, menos relacionados con el proceso real de ejecucion.