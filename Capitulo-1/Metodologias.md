# Metodologias de la programacion.
Lo mas comun y con lo que nos topamos cada vez que aprendemos un lenguaje de programacion, es que queremos iniciar inmediatamente a programar sin antes haber pensado un poco sobre el problema a resolver. Y al toparnos con problemas de diseño solemos recurir a rehacer las cosas. Esta parte es para tener cuando menos una buena idea desde donde iniciar y como hacerlo.
## Introduccion.
Se entiende por metodologia el conjunto de reglas y pasos estrictos que se siguen para desarrollar una aplicacion. Hay diversas metodologias, independientemente de la metodologia a utilizar suele haber una serie de pasos comunes en todas ellas (*Relacionado con el ciclo de vida de la aplicacion*):
1. Analisis.
2. Diseño.
3. Codificacion.
4. Ejecucion.
5. Prueba.
6. Mantenimiento.

### Analisis.
Al programar aplicaciones Siempre se debe realizar un cierto analisis.
> El analisis estudia los requisitos que ha de cumplir la aplicacion.

El resultado de esto es una hoja de especificaciones en la que aparecen los requerimientos de la aplicacion. Esta hoja es redactada por el o la analista o la persona responsable del proceso de creacion de la aplicacion.

En la creacion de algoritmos sencillos, el analisis consistiria unicamente en:
- **Determinar las entradas**. Es decir, los datos que posee el algoritmo cuando comienza su ejecucion. Esos datos permiten obtener el resultado.
- **Determinar las salidas**. Es decir, los datos que obtiene el algoritmo como resultado. Lo que que algoritmo devuelve al usuario.
- **Determinar el proceso**. Se estudia cual es el proceso que hay que realizar.

### Diseño.
En esta fase se crean esquemas simbolizan la aplicacion. Estos esquemas los elaboran analistas. Gracias a estos esquemas se simboliza la aplicacion. Estos esquemas en definitiva se convierten en la documentacion fundamental para plasmar en papel lo que el programador debe hacer.

En estos esquemas se puede simbolizar: la organizacion de los datos de la aplicacion, el orden de los procesos que tiene que realizar la aplicacion, la estructura fisica (*en cuanto archivo y carpetas*) que utilizara la aplicacion.

La creacion de estos esquemas se puede hacer en papel, o utilizar una herramienta para hacerlo.

En el caso de la creacion de algoritmos, conviene en esta fase usar el llamado diseño descendente. Mediante este diseño el problema se divide en modulos, que a su vez, se vuelven a dividir a fin de solucionar problemas mas concretos. Al diseño descendente se le suele llamar **Top-Down**. Gracias a esta tecnica un problema complicado se divide en pequeños problemas que son mas facilmente solucionables.

Siempre existe en el diseño la zona principal que es el programa  principal que se ejecutara cuando el programa este codificado en un lenguaje de programacion.

En la construccion de aplicaciones complejas en esta fase se utilizan gran cantidad de esquemas para describir la organizacion de los datos y los procedimientos queha de seguir el programa. En pequeños algoritmos se utilizan esquemas mas sencillos.

### Codificacion.
Es la escritura de la aplicacion en un lenguaje de programacion. Normalmente la herramienta utilizada en el diseño debe ser compatible con el lenguaje que se utilizara. Es decir si se utiliza un lenguaje orientado a objetos, la herramienta de diseño debe ser una herramienta que permita utilzar objetos.

Pero no comas ancias, se muy bien que debes estar ya anciando el empezar a programar en **C** pero esta parte es de suma importancia y te dara las armas suficientes para hacer algo mas grande sin que tengas que hacer reestructuraciones al momento de tu codificacion.

### Ejecucion.
Tras la escritura del codigo, mediante un compilar o un interprete podemos traducir el codigo a uno interpretable por la maquina. En este proceso pueden detectarse errores en el codigo que impiden su transformacion. En este caso el software encargado de la traduccion avisa de esos errores para que el programador los pueda corregir.

### Prueba.
Se trata de testear la aplicacion para verificar que su funcionamiento es el correcto. Para ellos se comprueba todas la entradas posibles, comprobando que las salidas son las correspondientes.

### Mantenimiento.
En esta fase se crea la documentacion del programa (Aun que no lo creas es un paso fundamental para la creacion de aplicaciones). Gracias a esa docuemtnacion se puede corregir futuros errores o renovar