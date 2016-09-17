# Introducción
Cuando ocupas una computadora siempre te cuestionas que es lo que la hace funcionar, como es que puedes hacer tu trabajo. Para todo esto es importante tener nociones de programación, ya que siempre podremos encontrarnos con distintos problemas que como tales son muy difíciles de solucionar.

En muchos de estos casos el aprender un lenguaje de programación nos ayuda a ocupar el poder de procesamiento de la computadora para la solución de estos problemas aparentemente imposibles de solucionar, por otra parte te va a permitir experimentar el gozo de haber creado algo por mismo o inclusive el mismo gusto pero de haber contribuido a algún proyecto **Open Source**.

Cabe destacar que la complejidad de la programación dependerá del problema que se trate de solucionar, comprender que toda esta idea de poder dar solución a problemas con mayor rapidez y eficacia se debe en gran parte a los avances y progresos en electrónica, matemáticas, física, etc.

En mi opinión la programación no es algo tan difícil, para muchos de nosotros que no tuvimos ciertas nociones, empezar con algo así no fue fácil, pero no por su complejidad, si no mas bien por que tuvimos un mal comienzo y quizás quisimos correr en lugar de aprender buenos fundamentos..

Un poco mas tarde me di cuenta que lo que distingue a muchos programadores de otros es su creatividad, para poder iniciar el desarrollo de algo tan simple o tan complejo como su mente visualice.

Por lo que la programación es una disciplina que requiere simultáneamente del uso de cierto grado de creatividad, un conjunto de conocimientos técnicos asociados y la capacidad de operar constantemente con abstracciones (tanto simbólicas como enteramente mentales).

La creatividad necesaria para programar no se diferencia demasiado de aquella utilizada para producir textos. Sin embargo, lo que hace a la programación algo especial es que requiere emplear un conjunto de conocimientos técnicos asociados a la manipulación de las computadoras. Esto agrega un grado notable de rigurosidad a esta actividad, ya que no podemos programar sin tener en cuenta este aspecto. Por otra parte, al poseer una naturaleza ligada a la resolución de diferente problemas del mundo real, se requiere de una capacidad de abstracción que permita operar sin que los conocimientos técnicos limiten al programador a resolver adecuadamente dichos problemas.

Por ejemplo actividades que requieren:

> Un uso intensivo de la creatividad son relacionadas comúnmente con el Arte.

> Conocimientos técnicos profundos son los relacionados con la medicina, electrónica y química.
 
> Operar continuamente en abstracto son las relacionadas con filosofía, lógica y matemáticas.

A lo largo de la vida seguiremos enfrentando continuamente con todo tipo de problemas. Para ellos nos valdremos de distintas herramientas, que combinadas de maneras innovadoras ampliaremos el espectro de soluciones y vuelven factible el desarrollo de cualquier programa.

Algo muy cierto es que a los que les guste la programación se podrán dedicar a construir programas, mantenerlos o contribuir a diversos Proyectos y siempre habrá mercado para esas personas.

# Conceptos de la programación
Lo que nos lleva a definir formalmente que es un programa:

> Un **Programa** es una descripción ejecutable de soluciones a problemas computacionales, es decir, un texto descriptivo que al ser procesado por una computadora da solución a un problema propuesto. De esta manera, la parte descriptiva de los programas es el texto que el programador le provee a la computadora.

Y como dijimos antes las descripciones dadas por los programas pueden estar escritas con diferentes símbolos y para diferentes propósitos.

Cuando el código consiste mayormente de palabras y nociones que son mas sencillas para que manejen las personas, con el objetivo de que puedan entender y construir los programas, hablamos de un lenguaje de **Alto Nivel**, y al código resultante lo llamaremos **código de fuente**.

Cuando el código consiste mayormente de números y símbolos de difícil compresión para las personas, pero de rápida ejecución por una maquina, hablamos de un lenguaje de **bajo nivel**, y al código resultante lo llamamos **código objeto** o **código ejecutable**. Por lo que hablaríamos de un **alto nivel de abstracción** cuando nos referíamos a la abstracciones mas cercanas a las ideas del problema a ser solucionado, a la mente de los programadores; y de **bajo nivel de abstracción** cuando nos refiramos a abstracciones mas cercanas a las ideas relacionadas a la forma de funcionamiento de las computadoras.

Es importante observar que tanto el código fuente como el código ejecutable están conformados por símbolos, y en este sentido es correcto llamar a ambos programas. Esto suele crear cierta confusión, pues entonces  la palabra programa se utiliza para dos propósitos diferentes:

1. El código que escribe el programador.
2. El código que ejecuta la computadora.

El primer punto sera el punto de estudio en este libro y el segundo es el resultado de varios procesos de traducción y compilación sobre el código fuente, que veremos un poco mas adelante en un apartado especial.

Si bien cuando escribimos el código fuente de un programa utilizamos símbolos como los del lenguaje natural, este texto debe ser capaz de poder ejecutarse por medio de la traducción que realiza nuestro compilador. Siendo esta característica la que hace que los programas se diferencien de otros textos, ya que no cualquier texto es ejecutable por una computadora. Lo hace a un texto ejecutable es mas bien su *sintaxis dura*, que no es mas que un conjunto de reglas estrictas de un determinado lenguaje de programación. con las que se escribe el código fuente.

> Los programadores tienen que balancear dos mundos bien diferente: un mundo de estructura y un mundo de imaginación. Creando conceptos abstractos usando lenguajes de programación muy estructurados.
[Programmer-Creativity-Boost](http://lifedev.net/2008/07/programmer-creativity-boost/)

# Lenguajes de Programación
Cuando programamos, no podemos utilizar el lenguaje natural con que nos comunicamos cotidianamente. Por el contrario, se emplea un lenguaje que un interprete o un compilador sea capaz de traducir a lenguaje maquina.

> Un **lenguaje de programación** es una serie de reglas que establecen que descripciones serán aceptadas y ejecutadas y cuales no tienen sentido para el mecanismo de ejecución provisto por la computadora.
Ademas, estas reglas están diseñadas de manera composicional, para que sea sencillo construir programas de mayor envergadura.

En actualidad existe un gran numero de lenguajes de programación, de características sumamente diferentes y que emplean diferentes enfoques con los que podemos programar. Cada lenguaje depende de un conjunto de ideas que guían, como su propósito final, la forma en que codificamos la descripción que otorgaremos a la computadora. Ya que esta forma viene dada por las reglas que definen como se combinan los elementos que el lenguaje de programación provee al programador.

A su vez, algunos lenguajes de programación están pensados para volcar mejor las ideas abstractas que el programador intenta emplear. Esto se conoce como lenguaje de **alto nivel**, ya que intentan, con cierto grado de eficacia, soslayar aquellas tareas que la computadora requiere realizar para que el programa cumpla con sus objetos. Pero también existen existen lenguajes de **bajo nivel**, que no hacen definir en mayor o menor medida cada paso que el programa seguirá, y por ende, están ligados a la naturaleza operacional de la computadora. Esta denominación (**Bajo y Alto**) surge de la idea de imaginar que la computadora es la base fundacional sobre la que los programas se ejecutan, que de las ideas abstractas se van construyendo sobre ellas. Justamente denominados a un lenguaje de mas **alto nivel** de abstracción cuanto mas lejos de la base se encuentra, o sea, cuanto mas abstracto, menos relacionados con el proceso real de ejecución.

> Un lenguaje de **Alto nivel** expresa mejor las ideas en las que debe pensar el programador, y en alguna forma están mas alejado de la maquina especifica que ejecutara cada programa escrito en dicho lenguaje.

> Un lenguaje de **Bajo Nivel** expresa mejor las ideas propias de los mecanismos de ejecución, por lo que es mas dependiente de la maquina especifica que ejecutara cada programa escrito en dicho lenguaje.

En la gran mayoría de los cursos de programación inicial suelen utilizarse una forma de lenguaje denominado comúnmente pseudocodigo, que se confunde con la de lenguaje de programación. Pero que no veremos por motivos de que seria muchísimo mas extenso este libro.

# Paradigmas de programación
Durante la década de 1960, la proliferación de lenguajes de programación siguió creciendo, y de a poco fueron diferenciándose grupos o familias de lenguajes, en torno a la predominancia de ciertas características. El foco de desarrollo de software se fue desplazando hacia la educación, para poder formar a los futuros programadores. La administración a gran escala siguió teniendo fuerte presencia, pero las aplicaciones orientadas a la defensa fueron disminuyendo.

Estos grupos o familias de lenguajes dieron origen a lo que ahora denominamos paradigma de programación, que no es otra cosa que un conjunto de ideas y conceptos al respecto del estilo con el que se expresan las soluciones a problemas a través de un lenguaje de programación. Cada paradigma privilegia ciertas ideas sobre otras, y  ciertas formas de combinación por sobre otras, dando lugar a estilos muy diferentes en la forma de programar.

> Un **paradigma de programación** es un conjunto de ideas y conceptos vinculados a la forma en que se relacionan las nociones necesarias para solucionar problemas con el uso de un lenguaje de programación.

Para 1970 ya se podían identificar cuatro grandes paradigmas, que están vigentes hoy incluso hoy en día y que son claramente reconocidos. Mucho después se intento identificar paradigmas adicionales a estos cuatro, pero no hubo cierto consenso sobre si alguno de ellos llegaría o no a poder ser considerado un paradigma y merecer ese nombre.

Los cuatro paradigmas de programación que surgieron a fines de los **60s** y principio de los **70s**, y que resultaron de fundamental influencia en la forma de hacer la programación, son:
1. **El paradigma Imperativo**.
2. **El paradigma Orientado a Objetos**.
3. **El paradigma Funcional**.
4. **El paradigma Lógico**.

Los dos primeros están mas orientados a la forma de manejar estados y podrían ser denominados **procedurales**, mientras que los 2 últimos están mas orientados a expresar conceptos o nociones independientes del estado y podrían ser denominados **declarativos**. El paradigma que se desarrollo con mayor ímpetu al principio fue el imperativo, debido a su cercanía con los lenguajes de bajo nivel. Los otros tardaron mas tiempo en adoptar un estado de madurez, y no fue hasta mediados de la década de **80s** que tanto el paradigma funcional como el lógico y el orientado a objetos empezó a ser foco de atención masiva.

Dentro del paradigma imperativo se clasifican lenguajes mas vinculados con la secuencia de instrucción y mas cercano al ensamblador. Algunos nombres notables que surgieron en esa época dentro del paradigma imperativo, y  aun conocidos hoy en día son:
- **Basic**, desarrollado en 1965 por **John Kemey** y **Thomas Kurtz** con la intención de que se convirtieran en un lenguaje de enseñanza.
- **Pascal**, desarrollado en 1970 con fines didácticos, por  **Niklaus Wirth** se caracteriza por ser un lenguaje de programacion fuertemente tipado.
- **C**, desarrollado por **Dennis Ritchie** y **Ken Thompson** en los laboratorios Bell entre 1969 y 1973, con el propósito de proveer una traducción eficiente a ensamblador y permitir la administración eficaz de los recursos de computo  de las maquinas con arquitectura Von Neumann a través de abstracciones cercanas al bajo nivel, que brinda una forma cómoda e independiente a la computadora de administrar sus recursos.

Y la fama y el motivo en el que nos centraremos en ese lenguaje se debe a que por la característica anterior en su diseño, fue utilizado en la programación del sistema operativo **UNIX** y fue ampliamente portado a numerosos sistemas. Es uno de los lenguajes mas difundidos y conocidos de todos los tiempos, y su estudio implica un conocimiento profundo de la forma en que se ejecutan un gran numero de aplicaciones en **Linux**, **Unix** y otros sistemas operativos.

Dentro del paradigma funcional se clasifican lenguajes orientados a la descripción  de datos, de su forma, las relaciones entre ellos, y sus transformaciones. Si bien inicialmente no fueron tan populares, la investigación llevo a este paradigma a la madurez y desde el mismo se realizaron grandes aportes a todos los lenguajes modernos. Algunos lenguajes que surgieron en esa época dentro de este paradigma son: 
- **ML**, desarrollado por **Robin Milner** y otros a principios de los 70s en la universidad de Edimburgo en Reino Unido con el propósito de servir para desarrollar tácticas de prueba en herramientas de demostración automática de teoremas, utilizando un sistema de tipos estáticos que es una de sus grandes innovaciones.
- **Miranda**, desarrollado por **David Turner** en 1985 como sucesor de sus primeros lenguajes de programación SASL y KRC, incorporando conceptos aprendidos del lenguaje ML y Scheme, derivado como dialecto de LISP por Guy L. Stele and Gerald J. Sussman en el laboratorio de Inteligencia artificial del MIT, siguiendo principios de minimalidad en la cantidad de conceptos distintos a proveer, pero conservando un gran poder expresivo.
- **Haskel**, en Honor de **Haskell B. Curry**, se publico por primera vez en 1990, y es actualmente el lenguaje  de alto nivel con mayor pureza conceptual, expresando el estado del arte en el desarrollo de lenguaje de programación funcional. Su impacto en la comprensión de conceptos de alto nivel no puede ser ignorada por un programador actual.

Dentro del paradigma orientado a objetos se encuentran lenguajes que agrupan el código alrededor de la metáfora de objeto, y que intenta representar mediante datos encapsulados las entidades del mundo real. Al ya mencionado lenguaje SIMULA, pionero de los lenguajes orientados a objetos, y algunos otros como:
- **SmallTalk**, creado en el Learning Research Group de Xerox por Alan Kay y Otros, también en los 70s, Pensado con fines educacionales basándose en la teoría constructivista del aprendizaje. Siendo la base del desarrollo posterior en tecnología de objetos, que hoy es uno de los pilares de la construcción moderna de software.

Seguramente te preguntaras sobre los lenguajes de programación multi propósito como java, python, c++, puestos son lenguajes de programación que son considerados con mas de un paradigma por lo que a pesar de tener el soporte de la orientación a objetos, no los incluiré.

Finalmente, dentro del paradigma lógico se encuentra distintos lenguajes orientados a la descripción de las relaciones lógicas entre aserciones, que habilitaban las posibilidad de realizar inferencias y ciertas formas de razonamiento automático, lo cual fue la inspiración para desarrollar el área conocida como inteligencia artificial. El lenguaje mas conocido de este paradigma, que también surgió a finales de la década de 1970 en Marseille, Francia, en el grupo de Alain Colmerauer, es PROLOG, un lenguaje basado en la afirmación de hechos y reglas de inferencia, que se utilizan mediante consultas en la forma de afirmaciones que deben validadas a partir de los hechos.

Seguramente te veras que ademas de Prolog existe otro lenguaje llamado lisp,  ese lenguaje a pesar de ser lógico también puede ser ocupado con otros tipos de paradigma sin embargo se le conoce mas por ser ocupado con paradigma lógico.

Cada uno de los lenguajes mencionados dejo un sin numero de descendientes y prácticamente todos  los lenguajes modernos se vinculan, de una forma u otra, con algunos de estos.

Otro gran avance de esta época fue algo llamado **programación estructurada**, que sucedió dentro del paradigma imperativo, y consistió fundamentalmente en aumentar la abstracción de los lenguajes, eliminando primitivas de control des-estructurado, o sea, que permitan moverse libremente por el código, sin tener en cuenta su estructura lógica.

# Algoritmo
Las personas efectuamos cotidianamente series de pasos, procedimientos o acciones que nos permiten alcanzar algún resultado o resolver algún problema. Estas series de pasos, procedimientos o acciones, comenzamos a aplicarlas desde que empieza el día, cuando, por ejemplo, decidimos bañarnos. Posteriormente, cuando tenemos que ingerir alimentos también seguimos una serie de pasos que nos permiten alcanzar un resultado especifico. Y la historia se repite un innumerable numero de veces. En realidad todo el tiempo estamos aplicando algoritmos para resolver problemas.

> Un **algoritmo** es un conjunto de paso por paso, procedimientos o acciones que nos permiten alcanzar un resultado o resolver un problema.

Una receta en un libro de cocina seria un excelente ejemplo de algoritmo: la preparación de un platillo complicado se divide en pasos simples comprensibles para cualquier personas con experiencia en cocina.

Otro buen ejemplo de algoritmo podría ser la coreografía para un ballet clásico: se divide una danza complicada  en una sucesión de pasos y posiciones básicas de ballet.

Muchas veces aplicamos el algoritmo de manera inadvertida, inconsciente o automática. Esto ocurre generalmente cuando el problema al que nos enfrentamos lo hemos resuelto con anterioridad un gran numero de veces.

A continuación, se presenta un algoritmo simple para el proceso cotidiano de cambiar una llanta baja:

1. **Aflojar los birlos de la llanta**.
2. **Levantar el carro con el gato**.
2. **Quitar los birlos de la llanta**.
3. **Quitar la llanta**.
4. **Poner la rueda de refacción**.
5. **Poner los birlos de la llanta**.
6. **Bajar el carro aflojando el gato**.
7. **Apretar los birlos de la llanta**.

Las características que deben tener los algoritmos son las siguientes:

1. **Precisión:** *Los pasos a seguir en el algoritmo se debe precisar claramente*.
2. **Determinismo:** *El algoritmo, dado un conjunto de datos de entrada idéntico, siempre debe arrojar los mismo resultados*.
3. **Finitud:** *El algoritmo, independientemente de la complejidad del mismo, siempre debe tener longitud finita*.

Los algoritmos tienen comúnmente 3 secciones o módulos principales:

- **Datos de Entrada.**
- **Procesamiento de los datos.**
- **Impresión de resultados.**

![Partes de Un Algoritmo](/Imagenes/Algoritmo.svg)

# Diagrama de flujo
> Un diagrama de flujo representa la esquematización gráfica de un algoritmo.

Realmente muestra gráficamente los pasos o procesos a seguir para alcanzar la solución de un problema. La construcción correcta del mismo es muy importante, ya que a partir de este se escribe el programa en un lenguaje de programación determinado. En este caso utilizaremos el lenguaje, aun que cabe recordar el diagrama de flujo se debe construir de manera independiente al lenguaje de programación. El diagrama de flujo representa la solución del problema. El programa representa la implementación de un lenguaje de programación.

La tabla y las imágenes que veremos a continuación se utilizaran, junto con una explicación de las mismas imágenes, satisfaciendo las recomendaciones de la **International Organization for Standarization** (**ISO**), y el **American National Standards Institute** (**ANSI**).

| Representación del Símbolo | Explicación del Símbolo |
|:--------:|:--------:|
|![Inicio o fin](/Imagenes/Circulo.svg)|Se utiliza para marcar el inicio y el fin del diagrama de flujo|
|![Lectura](/Imagenes/RectanguloLadeado.svg)|Se utiliza para introducir los datos de entrada, expresando lectura|
|![Proceso](/Imagenes/Rectangulo.svg)|Representa un proceso. En su interior se colocan asignaciones, operaciones aritméticas, cambios de valor de variables|
|![Decision](/Imagenes/Rombo.svg)|Se utiliza para representar una decisión. En su interior se almacena una condición, y, dependiendo del resultado se sigue por una de las ramas o camino alternativos. Este símbolo se utiliza con pequeñas variaciones en las estructuras selectivas if e if-else que veremos en otros capítulos, así como en las estructuras repetitivas for, while y do-while|
|![Multiple Decisión](/Imagenes/Pulpo.svg)|Se utiliza para representar una decisión múltiple, switch, que analizaremos también mas adelante. En su interior se almacena un selector, y, dependiendo del valor de dicho selector, se sigue por una de las ramas o caminos alternativos|
|![Escritura](/Imagenes/RectanguloMordido.svg)|Se utiliza para representar la impresión de un resultado, expresando escritura|
|![Direccion](/Imagenes/Flechas.svg)|Expresan la dirección del flujo del diagrama|
|![Coneccion](/Imagenes/Circulo.svg)|Expresa conexión dentro de una misma pagina|
|![Conector](/Imagenes/Conector.svg)|Representa conexión entre paginas diferentes|
|![Modulo](/Imagenes/Modulo.svg)|Se utiliza para expresar un modulo de un problema o un subproblema, que hay que resolver antes de continuar con el flujo normal del diagrama|

En la imagen siguiente se presentan los pasos que se deben seguir en la construcción de un diagrama de flujo. El procesamiento de los datos generalmente relacionado con el proceso de toma de decisiones. Ademas, es muy común repetir un conjunto de pasos.
![Etapas en la construcción de un diagrama de flujo](/Imagenes/Diagrama.svg)

## Reglas para la construcción de diagramas de flujo
Los símbolos presentados, colocados en los lugares adecuados, permiten crear una estructura gráfica flexible que ilustra los pasos a seguir para alcanzar un resultado especifico. El diagrama de flujo facilita entonces la escritura del programa en C. Lo que veremos a continuación se presenta el conjunto de reglas para la construcción de diagramas de flujo:

1. **Todo diagrama de flujo debe tener un inicio y un fin.**
2. **Las lineas utilizadas para indicar la dirección del flujo del diagrama deben ser rectas: ya sea verticales u horizontales**.
3. **Todas las lineas utilizadas para indicar la dirección del flujo del diagrama deben estar conectadas. La conexión puede ser un símbolo que exprese lectura, proceso, decisión, impresión, conexión o fin del diagrama**.
4. **El diagrama de flujo debe construirse de arriba hacia abajo y de izquierda a derecha**.
5. **La notación utilizada en el diagrama de flujo debe ser independiente del lenguaje de programación. La solución presentada se puede escribir posteriormente en diferentes lenguajes de programación**.
6. **Al realizar una tarea compleja, es conveniente poner comentarios que expresen o ayuden a entender lo que hayamos hecho**.
7. **Si las construcción del diagrama de flujo requiriera mas de una hoja, debemos utilizar los conectores adecuados y enumerar las paginas correspondientes**.
8. **No puede llegar mas de una linea a un símbolo determinado**.

## Desventajas de los diagramas de flujo
Aun que me parecen muy interesantes como primer acercamiento a la programación ya que son fáciles de entender. De hecho se utilizan fuera de la programación como esquema para ilustrar el funcionamiento de algoritmos sencillos.

Sin embargo cuando el algoritmos se complica, el diagrama de flujo se convierte en ininteligible. Ademas los diagramas de flujo no facilitan el aprendizaje de la programación estructurada.

#Pseudocodigo
Las bases de la programación estructurada fueron enunciadas por **Niklaus Wirdth**. Segun este científico cualquier problema algorítmico podía resolverse con el uso de estos 3 tipos de instrucciones:

1. **Secuenciales** Instrucciones que se ejecutan en orden normal. El flujo del programa  ejecuta la instrucción y pasa a ejecutar la siguiente.
2. **Alternativas** Instrucciones en las que se evaluá una condición y dependiendo si el resultado es verdadero o no, el flujo del programa se dirigirá a una instrucción u otra.
3. **Iterativas** Instrucciones que se repiten continuamente hasta que se cumple una determinada condición.

El tiempo le ha dado completamente la razón y ha generado un programación que insta a todo programador a utilizar solo instrucciones de esos 3 tipos. Es lo que se conoce como programación estructurada.

Pero el propio **Niklaus Wirdth** diseño el lenguaje pascal como el primer lenguaje estructurado. Lo malo es que pascal al ser un lenguaje completo incluye instrucciones excesivamente orientadas al ordenador.

Por lo que en aquella época se aconsejo para el diseño de algoritmos estructurados el uso de un lenguaje especial llamado pseudocodigo, que ademas de puede traducir a cualquier idioma y lenguaje de programación.

EL pseudocodigo ademas permite el diseño modular de programas y el diseño descendente gracias a esta posibilidad.

Debes enterder ademas de que existe un gran numero de tipos de pseudocodigos, es decir no hay un pseudocodigo 100% estándar. Pero si hay una gran cantidad de detalles aceptados por todos los que escriben pseudocodigos. Aquie te comentare el pseudocodigo aceptado en español. Hay que tomar en cuenta que muchas de las ideas de pseudocodigo se basa en pascal, por lo que la traducción es casi directa.

> El **pseudocodigo** son instrucciones escritas en un pseudolenguaje orientado a ser entendido por una personas no por un ordenador. Por ello en pseudocodigo  solo se pueden utilizar ciertas instrucciones.

Entra las instrucciones que se pueden utilizar estan:

- **De Entrada/Salida**. Para leer o escribir datos desde el programa hacia el usuario.
- **De Proceso**. Operaciones que realiza el algoritmo (Suma, Resta, Multiplicación, División, cambio de valor, etc.)
- **De Control de Flujo**. Instrucciones alternativas o iterativas (bucles y condiciones).
- **De Declaraciones**. Creación de variables y subprogramas.
- **Llamadas a Subprogramas**.
- **Comentarios**. Notas que se escriben junto al pseudocodigo para explicar mejor su funcionamiento.