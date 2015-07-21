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

> Los programadores tienen que balancear dos mundos bien diferente: un mundo de estructura y un mundo de imaginación. Creando conceptos abstractos usando lenguajes de programación muy estructurados.
[Programmer-Creativity-Boost](http://lifedev.net/2008/07/programmer-creativity-boost/)

## Lenguajes de Programación.
Cuando programamos, no podemos utilizar el lenguaje natural con que nos comunicamos cotidianamente. Por el contrario, se emplea un lenguaje que un interprete o un compilador sea capaz de traducir a lenguaje maquina.

> Un lenguaje de programación es una serie de reglas que establecen que descripciones serán aceptadas y ejecutadas y cuales no tienen sentido para el mecanismo de ejecución provisto por la computadora.
Ademas, estas reglas están diseñadas de manera composicional, para que sea sencillo construir programas de mayor envergadura.

En actualidad existe un gran numero de lenguajes de programación, de características sumamente diferentes y que emplean diferentes enfoques con lso que podemos programar. Cada lenguaje depende de un conjunto de ideas que guian, como su propósito final, la forma en que codificamos la descripción que otorgaremos a la computadora. Ya que esta forma viene dada por las reglas que definen como se combinan los elementos que el lenguaje de programación provee al programador.

A su vez, algunos lenguajes de programación están pensados para volcar mejor las ideas abstractas que el programador intenta emplear. Esto se conoce como lenguaje de **alto nivel**, ya que intentan, con cierto grado de eficacia, soslayar aquellas tareas que la computadora requiere realizar para que el programa cumpla con sus objetos. Pero también existen existen lenguajes de **bajo nivel**, que no hacen definir en mayor o menor medida cada paso que el programa seguirá, y por ende, están ligados a la naturaleza operacional de la computadora. Esta denominación (**Bajo y Alto**) surge de la idea de imaginar que la computadora es la base fundacional sobre la que los programas se ejecutan, que de las ideas abstractas se van construyendo sobre ellas. Justamente denominados a un lenguaje de mas **alto nivel** de abstracción cuanto mas lejos de la base se encuentra, o sea, cuanto mas abstracto, menos relacionados con el proceso real de ejecución.

> Un lenguaje de **Alto nivel** expresa mejor las ideas en las que debe pensar el programador, y en alguna forma están mas alejado de la maquina especifica que ejecutara cada programa escrito en dicho lenguaje.

> Un lenguaje de **Bajo Nivel** expresa mejor las ideas propias de los mecanismos de ejecución, por lo que es mas dependiente de la maquina especifica que ejecutara cada programa escrito en dicho lenguaje.

En la gran mayoría de los cursos de programación inicial suelen utilizarse una forma de lenguaje denominado comúnmente pseudocodigo, que se confunde con la de lenguaje de programación. Pero que no veremos por motivos de que seria muchísimo mas extenso este libro.

## Paradigmas de programación.
Durante la década de 1960, la proliferación de lenguajes de programación siguió creciendo, y de a poco fueron diferenciándose grupos o familias de lenguajes, en torno a la predominancia de ciertas características. El foco de desarrollo de software se fue desplazando hacia la educación, para poder formar a los futuros programadores. La administración a gran escala siguió teniendo fuerte presencia, pero las aplicaciones orientadas a la defensa fueron disminuyendo.

Estos grupos o familias de lenguajes dieron origen a lo que ahora denominamos paradigma de programación, que no es otra cosa que un conjunto de ideas y conceptos al respecto del estilo con el que se expresan las soluciones a problemas a través de un lenguaje de programación. Cada paradigma privilegia ciertas ideas sobre otras, y  ciertas formas de combinación por sobre otras, dando lugar a estilos muy diferentes en la forma de programar.
> Un **paradigma de programación** es un conjunto de ideas y conceptos vinculados a la forma en que se relacionan las nociones necesarias para solucionar problemas con el uso de un lenguaje de programación.

Para 1970 ya se podian identificar cuatro grandes paradigmas, que están vigentes hoy incluso hoy en día y que son claramente reconocidos. Mucho después se intento identificar paradigmas adicionales a estos cuatro, pero no hubo cierto consenso sobre si alguno de ellos llegaría o no a poder ser considerado un paradigma y merecer ese nombre.

Los cuatro paradigmas de programación que surgieron a fines de los 60s y principio de los 70s, y que resultaron de fundamental influencia en la forma de hacer la programación, son:
1. El paradigma *Imperativo*.
2. EL paradigma *Orientado a Objetos*.
3. El paradigma *Funcional*.
4. El paradigma *Logico*.

Los dos primeros están mas orientados a la forma de manejar estados y podrían ser denominados **procedurales**, mientras que los 2 últimos están mas orientados a expresar conceptos o nociones independientes del estado y podrian ser denominados **declarativos**. El paradigma que se desarrollo con mayor ímpetu al principio fue el imperativo, debido a su cercanía con los lenguajes de bajo nivel. Los otros tardaron mas tiempo en adoptar un estado de madurez, y no fue hasta mediados de la década de 80s que tanto el paradigma funcional como el lógico y el orientado a objetos empezó a ser foco de atención masiva.

Dentro del paradigma imperativo se clasifican lenguajes mas vinculados con la secuencia de instrucción y mas cercano al ensamblador. Algunos nombres notables que surgieron en esa época dentro del paradigma imperativo, y  aun conocidos hoy en día son:
- **Basic**, desarrollado en 1965 por John Kemey y Thomas Kurtz con la intención de que se convirtieran en un lenguaje de enseñanza.
- **Pascal**, desarrollado en 1970 con fines didácticos, por  Niklaus Wirth a partir de Algo.
- **C**, desarrollado por Dennis Ritchie y Ken Thompson en los laboratorios Bell entre 1969 y 1973, con el propósito de proveer una traducción eficiente a ensamblador y permitir la administración eficaz de los recursos de computo  de las maquinas con arquitectura Von Neumann a traves de abstracciones cercanas al bajo nivel, que brinda una forma cómoda e independiente a la computadora de administrar sus recursos.

Y la fama y el motivo en el que nos centraremos en ese lenguaje se debe a que por la característica anterior en su diseño, fue utilizado en la programación del sistema operativo **UNIX** y fue ampliamente portado a numerosos sistemas. Es uno de los lenguajes mas difundidos y conocidos de todos los tiempos, y su estudio implica un conocimiento profundo de la forma en que se ejecutan un gran numero de aplicaciones en **Linux**, **Unix** y otros sistemas operativos.