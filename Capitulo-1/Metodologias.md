# Metodologías de la programación
Lo mas común con lo que nos topamos cada vez que aprendemos un lenguaje de programación, es querer iniciar inmediatamente a programar sin antes haber pensado un poco sobre el problema a resolver. Y al toparnos con problemas de diseño solemos recurrir a rehacer las cosas. Esta parte es para tener cuando menos una buena idea desde donde iniciar y como hacerlo.
## Introducción
Se entiende por metodología el conjunto de reglas y pasos estrictos que se siguen para desarrollar una aplicación. Hay diversas metodologías, independientemente de la vayamos a utilizar suele haber una serie de pasos comunes en todas ellas (*Relacionado con el ciclo de vida de la aplicación*):
1. Análisis.
2. Diseño.
3. Codificación.
4. Ejecución.
5. Prueba.
6. Mantenimiento.

### Análisis
Al programar aplicaciones siempre se debe realizar un cierto análisis.
> El análisis estudia los requisitos que ha de cumplir la aplicación.

El resultado de esto es una hoja de especificaciones en la que aparecen los requerimientos de la aplicación. Esta hoja es redactada por el o la analista o la persona responsable del proceso de creación de la aplicación.

En la creación de algoritmos sencillos, el análisis consistiría unicamente en:
- **Determinar las entradas**. Es decir, los datos que posee el algoritmo cuando comienza su ejecución. Esos datos permiten obtener el resultado.
- **Determinar las salidas**. Es decir, los datos que obtiene el algoritmo como resultado. Lo que que algoritmo devuelve al usuario.
- **Determinar el proceso**. Se estudia cual es el proceso que hay que realizar.

### Diseño
En esta fase se crean esquemas simbolizan la aplicación. Estos esquemas los elaboran analistas. Gracias a estos esquemas se simboliza la aplicación. Estos esquemas en definitiva se convierten en la documentación fundamental para plasmar en papel lo que el programador debe hacer.

En estos esquemas se puede simbolizar: la organización de los datos de la aplicación, el orden de los procesos que tiene que realizar la aplicación, la estructura física (*en cuanto archivo y carpetas*) que utilizara la aplicación.

La creación de estos esquemas se puede hacer en papel, o utilizar una herramienta para hacerlo.

En el caso de la creación de algoritmos, conviene en esta fase usar el llamado diseño descendente. Mediante este diseño el problema se divide en módulos, que a su vez, se vuelven a dividir a fin de solucionar problemas mas concretos. Al diseño descendente se le suele llamar **Top-Down**. Gracias a esta técnica un problema complicado se divide en pequeños problemas que son mas fácilmente solucionables.

Siempre existe en el diseño la zona principal que es el programa  principal que se ejecutara cuando el programa este codificado en un lenguaje de programación.

En la construcción de aplicaciones complejas en esta fase se utilizan gran cantidad de esquemas para describir la organización de los datos y los procedimientos que ha de seguir el programa. En pequeños algoritmos se utilizan esquemas mas sencillos.

### Codificación
Es la escritura de la aplicación en un lenguaje de programación. Normalmente la herramienta utilizada en el diseño debe ser compatible con el lenguaje que se utilizara. Es decir si se utiliza un lenguaje orientado a objetos, la herramienta de diseño debe ser una herramienta que permita utilizar objetos.

Pero no comas ansias, se muy bien que debes estar ya con muchas ganas de empezar a programar en **C** pero esta parte es de suma importancia y te dará las armas suficientes para hacer algo mas grande sin que tengas que hacer re-estructuraciones al momento de tu codificación.

### Ejecución
Tras la escritura del código, mediante un compilar o un interprete podemos traducir el código a uno interpretable por la maquina. En este proceso pueden detectarse errores en el código que impiden su transformación. En este caso el software encargado de la traducción avisa de esos errores para que el programador los pueda corregir.

### Pruebas
Las pruebas o verificaciones de un programa es el proceso de ejecución del programa con una amplia variedad de datos de entrada, que determinaran si el programa tiene errores *(bugs)*. Para realizar las verificaciones se debe desarrollar una amplia gama de datos de test, valores normales de entrada, valores extremos de entrada que comprueben los limites del programa y valores de entrada que comprueben aspectos especiales del programa.

La *depuración* es el proceso de encontrar los errores del programa y corregir o eliminar dichos errores.
Cuando se ejecuta un programa, comúnmente se suele producir 3 tipos de errores:
1. **Errores de Compilación**. Se producen normalmente por uso incorrecto de las reglas del lenguaje de programación y suelen ser *errores de sintaxis*. Si existe un *error de sintaxis*, la computadora no puede comprender la instrucción, no se obtendrá el programa objeto y el compilador imprimirá una lista de todos los errores encontrados durante la compilación.
2. **Errores de Ejecución**. Estos se producen por instrucciones que la computadora puede comprender pero no ejecutar. Ejemplos típicos son: división por cero y raíces cuadradas de números negativos. En estos casos se detiene una ejecución del programa y se imprime un mensaje de error.
3. **Errores lógicos**. Como su nombre lo dice se producen en la lógica del programa y la fuente del error suele ser el diseño del algoritmo. Estos errores son los mas difíciles de detectar, ya que el programa puede funcionar y no producir errores de compilación ni de ejecución, y solo puede advertirse el error por la obtención de resultados incorrectos. En este caso se debe volver a la fase de diseño del algoritmo, modificar el algoritmo, cambiar el programa fuente, compilar y ejecutar una vez mas. De ahí que la importancia de las primeras fases es crucial.

### Mantenimiento
En esta fase se crea la documentación del programa (Aun que no lo creas es un paso fundamental para la creación de aplicaciones). Gracias a esa documentación se puede corregir futuros errores o renovar mas fácilmente ciertas partes.

La documentación de un problema consta de las descripciones de los pasos a dar en el proceso de resolución de dicho problema. La importancia de la documentación debe ser destacada por su decisiva influencia en el producto final. Programas pobremente documentados son difíciles de leer, mas difíciles de depurar y casi imposibles de mantener o modificar.

La documentación de un programa pude ser *interna* y *externa*. La **documentación interna** es la contenida en lineas de comentarios. La **documentación externa** incluye análisis, diagramas de flujo y/o pseudocodigo, manuales de usuario con instrucciones para ejecutar el programa y para interpretar los resultados.

La documentación es vital cuando se desea corregir posibles errores futuros o bien cambiar el programa. Tales cambios se denominan *mantenimiento del programa*. Después de cada cambio de documentación debe ser actualizada para facilitar cambios posteriores.

##Programación Modular
Es uno de los métodos de diseño mas flexibles y potentes para mejorar la productividad de un programa. En la programación modular el programa se divide en módulos (partes independientes), cada uno de los cuales ejecutan una única actividad o tarea y se codifican independientemente de otros módulos. Cada uno de estos módulos se analiza, codifica y pone punto por separado. Cada programa contiene un modulo denominado **programa principal** que controla todo lo que sucede transfiriendo el control a submodulos (también llamados *subprogramas*), de modo que ellos puedan ejecutar sus funciones; sin embargo, cada submodulo devuelve el control al modulo principal cuando haya completado su tarea. Si la tarea asignada a cada submodulo es demasiado compleja, este deberá romperse en otro módulos mas pequeños. El proceso sucesivo de subdivición de módulos continua hasta que cada modulo tenga solamente una tarea especifica que ejecutar.

Esta tarea puede ser *entrada*, *salida*, *manipulación de datos*, *control de otros módulos* o *alguna combinación de estos*. Un módulo puede transferir temporalmente (bifurcar) el control a otro modulo; sin embargo, cada modulo debe eventualmente devolver el control al modulo del cual se recibe originalmente el control.

Los módulos son independientes en el sentido en que ningún modulo puede tener acceso directo a cualquier otro modulo excepto al modulo al que llama y sus propios submodulos. Sin embargo, los resultados producidos por un modulo pueden ser utilizados por cualquier otro modulo cuando se transfiera a ellos el control.

Dado que los módulos son independientes, diferentes programadores pueden trabajar simultáneamente en diferentes partes del mismo programa. Esto reducirá el tiempo del diseño del algoritmo y posterior codificación del programa. Ademas, un modulo se puede modificar radicalmente sin afectar a otros módulos, incluso sin alterar su función principal.

La descomposición de un programa en módulos independientes mas simples se conoce también como método de **Divide y vencerás**. Por lo que se diseña cada modulo con independencia de los demás, y siguiendo el método ascendente o descendente se llegara hasta la descomposición final del problema en módulos en forma jerárquica.

##Programación estructurada
Según los términos de la *programación modular*, *programación descendente* y *programación estructurada* se introdujeron en la segunda mitad de la década de los sesenta y a menudo se utilizan son sinónimos aunque no significan lo mismo. La programación modular y descendente ya se ha examinado anteriormente. La programación estructurada significa escribir un programa de acuerdo a las siguientes reglas:
- El programa tiene un diseño modular.
- Los módulos son diseñados de modo descendente.
- Cada modulo se codifica utilizando las tres estructuras de control básicas: secuencia, selección y repetición.

El termino **programación estructurada** se refiere a un conjunto de técnicas que han ido evolucionando desde los primeros trabajo de *Edgar Dijkstra*. Estas técnicas aumentan considerablemente la productividad del programa reduciendo en elevado grado el tiempo requerido para escribir, verificar, depurar y mantener los programas. Ademas utiliza un numero limitado de estructuras de control que minimizan la complejidad de los programas y, por consiguiente, reducen los errores; hace los programas mas fáciles de escribir, verificar, leer y mantener. Los programas deben estar dotados de una estructura.

La programación estructurada es el conjunto de técnicas que incorporan:
- Recurso abstractos.
- Diseño descendente.
- Estructuras básicas.

### Recurso Abstractos
La programación estructurada se auxilia de los recursos abstractos en lugar de los recursos concretos que dispone un determinado lenguaje de programación.
Descomponer un programa en términos de recursos abstractos -Según Dijkstra- consiste en descomponer una determinada acción compleja en términos de un numero de acciones mas simples capaces de ejecutarlas o que constituyan instrucciones de computadoras disponibles.

### Diseño descendente (top-down)
Es el proceso mediante el cual un problema se descompone en una serie de niveles o pasos sucesivos de refinamiento. La metodología descendiente consiste en efectuar una relación entre las sucesivas etapas de estructuración de modo que se relacionen unas con otras mediante entradas y salidas de información. Es decir, se descompone el problema en etapas o estructuras jerárquicas, de forma que se puede considerar cada estructura desde dos puntos de vista:
- ¿Qué hace?
- ¿Cómo lo hace?

###Estructuras de control
Las *estructuras de control* de un lenguaje de programación son métodos de especificar el orden en que las instrucciones de un algoritmo se ejecutaran. El orden de ejecución de las sentencias o instrucciones determina el *flujo de control*. Estas estructuras de control son, por consiguiente fundamentales en los lenguajes de programación y en los diseños de algoritmos, especialmente los pseudocodigos.

Las tres estructuras de control básicos son:
- **Secuencia.**
- **Selección.**
- **Repetición.**

# Creación de Algoritmos
Independientemente de la notación que utilicemos para escribir algoritmos, estos contiene instrucciones a realizar por el ordenador. Lógicamente la escritura de estas instrucciones  siguen unas normas muy estrictas. Las instrucciones pueden ser de estos tipos:
- **Primitivas**: Son acciones sobre los datos del programa, estas pueden ser:
	- Asignación.
	- Instrucciones de Entrada/Salida.
- **Declaraciones**: Sirven para advertir y documentar el uso de variables y subprogramas en el algoritmo.
- **Control**: Sirven para alterar el orden de ejecución del algoritmo. En general el algoritmo se ejecuta secuencialmente. Gracias a estas instrucciones el flujo del algoritmo depende de ciertas condiciones que nosotros mismos indicamos.
