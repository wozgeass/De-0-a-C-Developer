# Compilador
Si te encuentras iniciando en el mundo linux seguramente te habras ya encontrado en un mundo diferente al que estas acostumbrado y has tenido que aprender algunas cosas antes para poder hacer tu estadia en el sistema mas comoda.

Para los que ya tienen tiempo usando el sistema y solo han sido usuarios del sistema quizas no les importe mucho este libro, pero si eres de los curiosos que tienen ganas de ir mas haya, encontraras en este libro un buen texto de referencia para poderte convertir mas fácilmente en un desarrollador de aplicaciones nativas en linux.

Usualmente en muchos libros encontraras información sobre como poder compilar tus programas usando el compilador **GCC**, pero muy pocos nos explican que existen mas compiladores asi como librerias de **C**. Entre los compiladores que nos encontraremos estan:

- **Clang**
- **Gcc**
- **Icc**

Del mismo modo existen un gran numero de librerias para programar en C respetando lógicamente el estandar OSI de C.

- **glibc**
- **eglibc**
- **uClibc**
- **musl libc**

Para poder crear y desarrollar utilizando linux deberemos conocer un concepto que ingles se le conoce como **Toolchain** pero lo que es en realidad es un conjunto de herramientas que permiten crear, linkear ejecutables y librerias.

Si tu interes despues es el de ir mas lejos y desarrollar aplicaciones nativas para sistemas operativos embebidos quizas sea importante que entiendas lo siguiente:

Existen basicamente 2 tipos de Toolchain:

- **Nativo**
- **Cruzado**

Por un lado el **nativo** sera el que mas utilizaremos en este libro ya que permite crear nuestros ejecutables para la misma arquitectura en la que nos encontramos. El cruzado aplicaria en el momento en el que nosotros desearamos crear ejecutables para otra arquitectura diferente a en la que estamos.

> Por ejemplo: Si estuvieramos en un ordenador de arquitectura **x86** y queremos pasar algunos programas en **C** o **C++** a nuestro **Raspberry** y como tiene arquitectura **ARM** tendriamos que usar un toolchain cruzado.

Un toolchain standard consiste en 3 componentes :

- Binutils: Son un conjunto de aplicaciones 


Considerado el compilador mas usado en el ambiente Linux incluso actualmente **UNIX**. **GCC** significa **GNU compiler collection** (**Colección de compiladores de GNU**).
La *Free Software Fundation* lo distribuye con una licencia **GPL**. A principio de los **90s**, el recién terminado sistema operativo **GNU** fue finalmente completado con la inclusión del **Kernel Linux**.

