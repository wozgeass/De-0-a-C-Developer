# Metodologías de la programación.
Lo mas común con lo que nos topamos cada vez que aprendemos un lenguaje de programación, es querer iniciar inmediatamente a programar sin antes haber pensado un poco sobre el problema a resolver. Y al toparnos con problemas de diseño solemos recurrir a rehacer las cosas. Esta parte es para tener cuando menos una buena idea desde donde iniciar y como hacerlo.
## Introducción.
Se entiende por metodología el conjunto de reglas y pasos estrictos que se siguen para desarrollar una aplicación. Hay diversas metodologías, independientemente de la vayamos a utilizar suele haber una serie de pasos comunes en todas ellas (*Relacionado con el ciclo de vida de la aplicación*):
1. Análisis.
2. Diseño.
3. Codificacion.
4. Ejecución.
5. Prueba.
6. Mantenimiento.

### Análisis.
Al programar aplicaciones siempre se debe realizar un cierto análisis.
> El análisis estudia los requisitos que ha de cumplir la aplicación.

El resultado de esto es una hoja de especificaciones en la que aparecen los requerimientos de la aplicación. Esta hoja es redactada por el o la analista o la persona responsable del proceso de creación de la aplicación.

En la creación de algoritmos sencillos, el análisis consistiría unicamente en:
- **Determinar las entradas**. Es decir, los datos que posee el algoritmo cuando comienza su ejecución. Esos datos permiten obtener el resultado.
- **Determinar las salidas**. Es decir, los datos que obtiene el algoritmo como resultado. Lo que que algoritmo devuelve al usuario.
- **Determinar el proceso**. Se estudia cual es el proceso que hay que realizar.

### Diseño.
En esta fase se crean esquemas simbolizan la aplicación. Estos esquemas los elaboran analistas. Gracias a estos esquemas se simboliza la aplicación. Estos esquemas en definitiva se convierten en la documentación fundamental para plasmar en papel lo que el programador debe hacer.

En estos esquemas se puede simbolizar: la organización de los datos de la aplicación, el orden de los procesos que tiene que realizar la aplicación, la estructura física (*en cuanto archivo y carpetas*) que utilizara la aplicación.

La creación de estos esquemas se puede hacer en papel, o utilizar una herramienta para hacerlo.

En el caso de la creación de algoritmos, conviene en esta fase usar el llamado diseño descendente. Mediante este diseño el problema se divide en módulos, que a su vez, se vuelven a dividir a fin de solucionar problemas mas concretos. Al diseño descendente se le suele llamar **Top-Down**. Gracias a esta técnica un problema complicado se divide en pequeños problemas que son mas fácilmente solucionables.

Siempre existe en el diseño la zona principal que es el programa  principal que se ejecutara cuando el programa este codificado en un lenguaje de programación.

En la construcción de aplicaciones complejas en esta fase se utilizan gran cantidad de esquemas para describir la organización de los datos y los procedimientos que ha de seguir el programa. En pequeños algoritmos se utilizan esquemas mas sencillos.

### Codificación.
Es la escritura de la aplicación en un lenguaje de programación. Normalmente la herramienta utilizada en el diseño debe ser compatible con el lenguaje que se utilizara. Es decir si se utiliza un lenguaje orientado a objetos, la herramienta de diseño debe ser una herramienta que permita utilizar objetos.

Pero no comas ansias, se muy bien que debes estar ya con muchas ganas de empezar a programar en **C** pero esta parte es de suma importancia y te dara las armas suficientes para hacer algo mas grande sin que tengas que hacer re-estructuraciones al momento de tu codificación.

### Ejecución.
Tras la escritura del código, mediante un compilar o un interprete podemos traducir el código a uno interpretable por la maquina. En este proceso pueden detectarse errores en el código que impiden su transformación. En este caso el software encargado de la traducción avisa de esos errores para que el programador los pueda corregir.

### Prueba.
Las pruebas o verificaciones de un programa es el proceso de ejecución del programa con una amplia variedad de datos de entrada, que determinaran si el programa tiene errores *(bugs)*. Para realizar las verificaciones se debe desarrollar una amplia gama de datos de test, valores normales de entrada, valores extremos de entrada que comprueben los limites del programa y valores de entrada que comprueben aspectos especiales del programa.

La *depuración* es el proceso de encontrar los errores del programa y corregir o eliminar dichos errores.
Cuando se ejecuta un programa, comúnmente se suele producir 3 tipos de errores:
1. **Errores de Compilación**. Se producen normalmente por uso incorrecto de las reglas del lenguaje de programación y suelen ser *errores de sintaxis*. Si existe un *error de sintaxis*, la computadora no puede comprender la instruccion, no se obtendra el programa objeto y el compilador imprimira una lista de todos los errores encontrados durante la compilacion.
2. **Errores de Ejecucion**. Estos se producen por instrucciones que la computadora puede comprender pero no ejecutar. Ejemplos tipicos son: divicion por cero y raices cuadradas de numeros negativos. En estos casos se detiene una ejecucion del programa y se imprime un mensaje de error.
3. **Errores logicos**. Se producen en la logica del programa y la fuente del error suele ser el diseño del algoritmo. Estos errores son los mas dificiles de detectar, ya que el programa puede funcionar y no producir errores de compilacion ni de ejecucion, y solo puede advertirse el error por la obtencion de resultados incorrectos. En este caso se deve volver a la fase de diseño del algoritmo, modificar el algoritmo, cambiar el programa fuente, compilar y ejecutar una vez mas. De ahi que la importancia de las primeras fases es crucial.

### Mantenimiento.
En esta fase se crea la documentación del programa (Aun que no lo creas es un paso fundamental para la creación de aplicaciones). Gracias a esa documentación se puede corregir futuros errores o renovar mas facilmente ciertas partes.

La documentacion de un problema consta de las descripciones de los pasos a dar en el proceso de resolucion de dicho problema. La importancia de la documentacion debe ser destacada por su decisiva influencia en el producto final. Programas pobremente documentados son dificiles de leer, mas dificiles de depurar y casi imposibles de mantener o modificar.

La documentacion de un programa pude ser *interna* y *externa*. La **documentacion interna** es la contenida en lineas de comentarios. La **documentacion externa** incluye analisis, diagramas de flujo y/o pseudocodigo, manuales de usuario con instrucciones para ejecutar el programa y para interpretar los resultados.

La documentacion es vital cuando se desea corregir posibles errores futuros o bien cambiar el prgrama. Tales cambios se denominan *mantenimiento del programa*. Despues de cada cambio de documentacion debe ser actualizada para facilitar cambios posteriores.

##Programacion Modular.
La programacion modular es uno de los metodos de diseño mas flexibles y potentes para mejorar la productividad de un programa. En la programacion modular el programa se divide en modulos (partes independientes), cada uno de los cuales ejecutan una unica actividad o tarea y se codifican independientemente de otros modulos. Cada uno de estos modulos se analiza, codifica y pone punto por separado. Cada programa contiene un modulo denominado **programa principal** que controla todo lo que sucede transfiriendo el  el contro a submodulo (tambien llamados *subprogramas*), de modo que ellos puedan ejecutar sus funciones; sin embargo, cada submodulo devuelve el contro al modulo principal cuando haya completado su tarea. Si la tarea asignada a cada submodulo es demasiado compleja, este debera romperse en otro modulos mas pequeños. El proceso sucesivo de subdivicion de modulos continua hasta que cada modulo tenga solamente una tarea especifica que ejecutar.

Esta tarea puede ser *entrada*, *salida*, *manipulacion de datos*, *control de otros modulos* o *alguna combinacion de estos*. Un módulo puede transferir temporalmente (bifurcar) el contro a otro modulo; sin embargo, cada modulo debe eventualmente devolver el control al modulo del cual se recibe originalmente el control.

Los modulos son independientes en el sentido en que ningun modulo puede tener acceso directo a cualquier otro modulo excepto al modulo al que llama y sus propios submodulos. Sin embargo, los resultados producidos por un modulo puden ser utilizados por cualquier otro modulo cuando se transfiera a ellos el control.

Dado que los modulos son independientes, diferentes programadores pueden trabajar simultaneamente en diferentes partes del mismo programa. Esto reducira el tiempo del diseño del algoritmo y posterior codificacion del programa. Ademas, un modulo se puede modificar radicalmente sin afectar a otros modulos, incluso sin alterar su funcion principal.

La descomposicion de un programa en modulos indpendientes mas simples se conoce tambien como metodo de **Divide y venceras**. Por lo que se diseña cada modulo con independencia de los demas, y siguiendo el metodo ascendente o descendente se llegara hasta la descomposicion final del problema en modulos en forma jerarquica.

##Programacion estructurada.
Segun los terminos de la *programacion modular*, *programacion descendente* y *programacion estructurada* se introdujeron en la segunda mitad de la decada de los sesenta y a menudo se utilizan son sinonimos aunque no significan lo mismo. La programacion modular y descendente ya se ha examinado anteriormente. La programacion estructurada significa escribir un programa de acuerdo a las siguientes reglas:
- El programa tiene un diseño modular.
- Los modulos son diseñados de modo descendente.
- Cada modulo se codifica utilizando las tres estructuras de control basicas: secuencia, seleccion y repeticion.

El termino **programacion estructurada** se refiere a un conjunto de tecnicas que han ido evolucionando desde los primeros trabajo de *Edgar Dijkstra*. Estas tecnicas aumentan considerablemente la productividad del programa reduciendo en elevado grado el tiempo requerido para escribir, verificar, depurar y mantener los programas. Ademas utiliza un numero limitado de estructuras de control que minimizan la complejidad de los programas y, por consiguiente, reducen los errores; hace los programas mas fáciles de escribir, verificar, leer y mantener. Los programas deben estar dotados de una estructura.

La programación estructurada es el conjunto de técnicas que incorporan:
- Recurso abstractos.
- Diseño descendente.
- Estructuras básicas.

### Recurso Abstractos.

# Creación de Algoritmos.
Independientemente de la notación que utilicemos para escribir algoritmos, estos contiene instrucciones a realizar por el ordenador. Lógicamente la escritura de estas instrucciones  siguen unas normas muy estrictas. Las instrucciones pueden ser de estos tipos:
- **Primitivas**: Son acciones sobre los datos del programa, estas pueden ser:
	- Asignación.
	- Instrucciones de Entrada/Salida.
- **Declaraciones**: Sirven para advertir y documentar el uso de variables y subprogramas en el algoritmo.
- **Control**: Sirven para alterar el orden de ejecución del algoritmo. En general el algoritmo se ejecuta secuencialmente. Gracias a estas instrucciones el flujo del algoritmo depende de ciertas condiciones que nosotros mismos indicamos.
