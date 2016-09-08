# Introducción
Como ya vimos antes **C** es un lenguaje de programación de alto nivel que fue usado para desarrollar el sistema operativo **UNIX**. Las primeras versiones de **UNIX** se escribieron en ensamblador, pero a partir de 1973 pasaron a escribirse en **C**. Pero el ensamblador sigue siendo el segundo lenguaje mas utilizado en el **Kernel Linux**: en concreto aquellas partes intimamente relacionadas al hardware o la inicializacion.

A continuacion te dejo un recuento del numero de lineas logicas que podemos encontrar en la versión 4.7 del kernel Linux.

| **Lenguaje** | **Lineas** | **Porcentaje** |
| -- | -- | -- |
| C | 14,104,422 | 97.63 |
| Ensamblador | 283932 | 1.97 |
| Perl | 24286 | 0.17 |
| Sh | 12078 | 0.08 |
| Cpp | 5358 | 0.04 |
| Python | 8546 | 0.06 |
| Yacc | 4327 | 0.03 |
| Lex | 2414 | 0.02 |
| Awk | 1130 | 0.01 |
| Pascal | 231 | 0.0 |
| Lisp | 218 | 0.0 |
| **Total** | **14,446,942** | **100** |

La gran mayoria de aplicaciones estandar que acompañan a cualquier sistema Linux y Unix estan escritas en C. Esta es la razon que hace de este lenguaje la forma natural de comunicarse con el sistema.

El lenguaje puede clasificarse dentro del grupo de los lenguajes de alto nivel, aun a pesar de no estar fuertemente tipado; sin embargo, tambien le ofrece al programador posibilidades que solo estan presentes en los lenguajes de bajo nivel. Así, por ejemplo, en C se pueden manipular bits y aritmetica de direcciones. C tambien permite como ya vimos en el capitulo anterior la programación estructurada y modular.

Tambien permite el desarrollo de aplicaciones que se ajustan al paradigma de programación modular. Algunas de las caracteristicas de este modelo son:

- Los programas 

## Ciclo de creacion de un programa
A la hora de crear un programa, hemos de empezar por la edicion de un fichero que contendra el codigo fuente. Este fichero se nombra, por convenio, añadiendole la extension .c. Si nos valemos del editor vim la forma de editarlo seria:

```bash
vim programa.c
```
Y el compilador gcc sera el encargado de generar el fichero ejecutable a patir del fichero fuente. Para invocarlo deberemos de hacerlo de la manera siguiente:

```bash
gcc programa.c -o programa
```
