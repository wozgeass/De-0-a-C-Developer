# Metodologías de la programación.
Lo mas común y con lo que nos topamos cada vez que aprendemos un lenguaje de programación, es querer iniciar inmediatamente a programar sin antes haber pensado un poco sobre el problema a resolver. Y al toparnos con problemas de diseño solemos recurrir a rehacer las cosas. Esta parte es para tener cuando menos una buena idea desde donde iniciar y como hacerlo.
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
Se trata de testear la aplicación para verificar que su funcionamiento es el correcto. Para ellos se comprueba todas la entradas posibles, comprobando que las salidas son las correspondientes.

### Mantenimiento.
En esta fase se crea la documentación del programa (Aun que no lo creas es un paso fundamental para la creación de aplicaciones). Gracias a esa documentación se puede corregir futuros errores o renovar

# Creacion de ALgoritmos.
Independientemente de la notacion que utilicemos para escribir algoritmos, estos contiene instrucciones a realizar por el ordenador. Logicamente la escritura de estas instrucciones 