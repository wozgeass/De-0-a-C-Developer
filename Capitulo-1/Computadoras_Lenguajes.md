# Relación computadoras y los lenguajes de programación.
Esta parte es un sugerencia de varias personas donde piden que se explique un poco mas a detalle como se relacionan las computadoras con los lenguajes de programación, lo quise omitir pensando que eso lo podrían buscar en algunos otros libros pero creo que no estaría completo el libro sin esta parte.
Las computadoras hoy en día se han convertido en una herramienta esencial en muchas áreas: industria, gobierno, ciencia, educación, etc. El papel de los programas y aplicaciones juega un papel crucial; sin una lista de instrucciones a seguir, la computadora es virtualmente inútil. Y los lenguajes de programación nos permiten escribir esos programas y, por consiguiente, comunicarnos con las computadoras a través de ellos.
Una computadora procesa los datos y los convierte en información significativa. Para conseguir esos resultados, un programador necesita conocimientos tanto de hardware como de software.

## Organización de una computadora.
Desde la decada de los *40's* se crearon las primeras computadoras con nombres muy extravagantes como **Atanasoff-Berry**, **UNIVAC**, **ENIAC** o **EDVAC**.
La aparición de **IBM** fue el punto de partida de la moderna computación, pasando de computadoras imposibles de pagar por cualquier personas a unas un poco mas accesibles. Del mismo modo el software se vio cambiado desde el inicio de una compañía llamada **Microsoft** que fue en gran medida una de las que propicio la creación del **Software Libre** y el **Open Source**.
Aunque a primera vista puedan parecer sinónimos los **datos** e **información** existe una gran diferencia entre ellos.

> Los **datos** consta de echos en bruto. 

> La **información**, por otra parte, son datos procesados.

La información tiene datos significativos; los datos en su forma original (en bruto) no lo son tanto. La computadora procesa esos datos y la información significativa es el resultado que se conoce muy comúnmente como *salida*.
Los datos, por si mismo no sirven de mucho y no son muy útiles para las personas que los manipulan y necesitan tomar decisiones con ellos.

Los programas modernos producen información en muchos formatos. Estos programas reproducen música, se comunican con otras computadoras a través de la red y mas aun con los smart phones que en los últimos años se han convertido en algo casi obligatorio. Todos estos envían una salida a la pantalla, impresora, es decir los datos de entrada y los datos de salida pueden ser, realmente, cualquier cosa, texto, imágenes, música.

Una computadora necesita tanto del **hardware** como del **software** para poder ser usada real y prácticamente. El **hardware** de la computadora sin el software que le acompaña es como si tuviéramos un libro con paginas en blanco. La portada, contraportada y las paginas interiores constituyen el **hardware** del libro, pero el libro no es útil sin ningún texto, el **software**.

## Hardware
Cuando un usuario interactuá con una computadora, proporciona una entrada; en respuesta, la computadora procesa la entrada devolviendo una salida valiosa al usuario. La entrada puede ser en formato de ordenes o instrucciones dadas, texto, números o imágenes. La salida puede ser el resultado: cálculos en *calc* de **libreoffice**, una oficio en *writer* o un auto moviéndose por la pantalla en un juego como **super tux**. Una computadora necesita disponer de un conjunto de funcionalidades y proporcionar la capacidad de:

1. Aceptar la entrada.
2. Visualiza o presentar la salida.
3. Almacenar la información en un formato consistente.
4. Ejecutar operaciones aritméticas o lógicas bien sobre datos de entrada o bien sobre datos de salida.
5. Monitorizar, controlar y dirigir las operaciones globales y de secuencia del sistema.

![Vim](/Imagenes/Arquitectura/CPU.svg)
### Procesador
El procesador es el dispositivo interior de la computadora que ejecuta las instrucciones del programa o aplicación. También se le suele conocer como **UCP** *(Unidad Central de Procesamiento)*. En el mercado existen muchas marcas disponibles para computadoras de escritorio o laptop como:

1. **INTEL**
2. **AMD**

O para móviles como:

1. **ARM**
2. **INTEL**
3. **AMD**
4. **NVIDIA**
5. **SAMSUNG**
6. **QUALCOMM**

Ya casi no existe persona que no tenga un smart phone y ha sido este el caso en el que mucha gente ahora prefiere desarrollar apps que aprender el bajo nivel, sin embargo ignoran que lo que sustenta esas apps son el sistema operativo.

El procesador solo puede ejecutar instrucciones simples, tales como cálculos aritméticos sencillos o desplazamientos de numero por diferentes posiciones. Sin embargo, la velocidad a la cual se realizan estos cálculos debe ser muy grande y esta característica le permite ejecutar instrucciones que realizan cálculos complejos.

La **UCP**, dirige y controla el proceso de información realizado por la computadora, procesando y manipulando la información almacenada en la memoria. Se puede recuperar esa información de la memoria. También puede almacenar los resultados de estos procesos en memoria para su uso posterior.

![Procesamiento](/Imagenes/Arquitectura/Procesamiento.svg)
La **UCP** consta de dos componentes:

1. **Unidad de Control** (*UC*)
2. **Unidad Aritmético Lorica** (*UAL*)

> La **Unidad de Control (UC)** coordina las actividades de la computadora, determinando que operaciones se deben realizar y en que orden; así mismo controla y sincroniza todo el proceso de la computadora.

> La **Unidad Aritmético Lorica (UAL)** Realiza operaciones aritméticas y lógicas, tales como suma, resta, multiplicación, división y comparaciones. Los datos en la memoria central se pueden leer o escribir por la **UCP**.

### Memoria

Otra parte muy importante de una computadora es la memoria. La unidad de memoria almacena la información en un formato lógicamente consistente. Normalmente, tanto las instrucciones como los datos se almacenan en memoria, con frecuencia en áreas distintas y separadas. La memoria se divide en dos categorías:

1. **Memoria Principal**
2. **Memoria Auxiliar**

> La **memoria Principal** contiene el programa en ejecución y los resultados de los cálculos intermedios de la computadora. Se le suele conocer mas como **Memoria Ram**.
> La **Memoria Auxiliar** o almacenamiento secundario consta de dispositivos utilizados para almacenar los datos en modo permanente. Cuando se necesitan los datos se pueden recuperar de estos dispositivos.

El programa se almacena en memoria externa de modo permanente pero cuando se ha de ejecutar debe transferirse a la memoria central. Este proceso se realiza mediante ordenes al sistema operativo que realiza las operaciones correspondientes.

### Microprocesador
Es un circuito integrado que controla y realiza las funciones y operaciones con los datos. En realidad el microprocesador representa la Unidad Central de Procesamiento o procesador, y popularmente cuando se habla de una computadora el termino que se utiliza en las características técnicas para referirse a la Unidad Central de Procesamiento. Las velocidades de un microprocesador se mide en MegaHercios (MHz) aunque es mas común que encuentres los GigaHercios (Ghz).

| **INTEL** | **AMD** |
| -- | -- |
| **Core i3** *(Sexta Generación)* | **APU ATHLON** *(Cuarta Generación)* |
| **Core i5** *(Sexta Generación)* | **APU A10** *(Séptima Generación)* |
| **Core i7** *(Sexta Generación)* | **FX** | 

Y para servidores y maquinas de alta disponibilidad:

| **INTEL** | **AMD** |
| -- | -- |
| **XEON** | **OPTERON** |

Pero se hoy en día los móviles han superado con creces a las PC y laptops que ahora hablamos de otros proveedores para estos dispositivos:

| **ARM** | **INTEL** | **AMD** | **NVIDIA** | **Samsung** | **Qualcomm** |
| -- | -- | -- | -- | -- | -- |
| **Cortex-A73** | **Core M** | **Polaris** | **Tegra X1** | **Exynos 8** | **Snapdragon 820** |

### Dispositivos de Entrada/Salida
Para que el usuario pueda introducir la entrada, la computadora tiene varios **dispositivos de entrada** como parte de su hardware, como:

1. Teclado
2. Raton (Mouse)
3. Scanner
5. Unidad DVD
6. Unidad Blue Ray
7. Web Cam
8. Joystick
9. Lectores de Codigo de Barras
10. Microfonos.

La salida al usuario se le proporciona mediante **dispositivos de salida**, tales como

1. Monitor
2. Cañon
3. Impresora
4. Bocinas

Los dispositivos de **entrada/Salida** permiten la comunicacion entre la computadora y el usuario. Los Dispositivos de entrada como su nombre lo indica, sirven para introducir datos en la computadora para su procesamiento. Los datos se leen de los dispositivos de entrada y se almacenan en la memoria principal. Convirtiendo la informacion de entrada en impulsos electricos que son procesados por el sistema operativo.

![Procesamiento](/Imagenes/Arquitectura/IO.svg)



