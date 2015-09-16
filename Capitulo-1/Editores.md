#Editores.
Como lo dije casi al principio, el editor que desees usar para desarrollar es irrelevante, lo que pretendo ahora es mostrarte con gran detalle y detenimiento las bondades de mi editor favorito por lo que iniciaremos con su nombre:

![Vim](/Imagenes/Vimlogo.svg)

Se muy bien que existen varios editores pero este en especial me ha parecido muy sencillo y poderoso, ademas me encuentro trabajando resaltadores de sintaxis para diferentes librerías y colectando plugins para hacer un vim mucho mas robusto y usable como un IDE para diferentes lenguajes.

Como ya dijimos Vim  o ("VI IMproved") es un clon de VI, es decir, un programa similar al editor de textos "VI".

Vim no solo trabaja en modo de texto en cualquier terminal, sino que también tiene un interfaz gráfica para el usuario, es decir, menús y soporte para el ratón.

![Vim](/Imagenes/GVim.png)

Está disponible para muchas plataformas y tiene muchas características añadidas en comparación con VI. Es compatible con casi todos los comandos de VI - excepto con los errores.

Esta disponible en un gran numero de sistemas operativos entre y no podía faltar para los 3 sistemas mas importantes:
Linux:
- Linux:
![Linux](/Imagenes/logos/Linux.svg)
- OSX:
![OSX](/Imagenes/logos/Apple.svg)
- Windows:
![Windows](/Imagenes/logos/Windows.svg)
- Pero si eres usuario de sistemas BSD debo informarte que también lo vas a poder usar:
![FreeBSD](/Imagenes/logos/Freebsd.svg)

El copyright está en las manos del autor principal y mantenedor, Bram Moolenaar <bram@vim.org>.  Vim es un "**programa-de-caridad**" "**charity-ware**"), es decir que se sugiere que hagas una donación a los huérfanos en Uganda.

Y si te lo preguntabas vim a pesar de entrar en **charity-ware** es software *Open Source* y todos los que quieran apoyar son bienvenidos para contribuir en algo al proyecto.

## Caracteristicas
Es un editor para un Principiante - Amigable para el usuario:

Es mucho más fácil para los principiantes que VI debido a la disponibilidad de ayuda en línea bien extensa, comandos para "deshacer" (undo) y "rehacer" (redo) (¡no te preocupes mucho con los errores - simplemente usa undo y redo!),  soporte para el ratón y tambien iconos y menús configurables (GUI).

Soporta la edición de derecha-a-izquierda (ej. con el *Árabe*, *Farsi*, *Hebreo*), y textos en *multi-octeto*, es decir, lenguajes con caracteres gráficos representados por más de un "*octeto*", por ejemplo *Chino*, *Japonés*, *Coreano (Hangul)*, técnicamente hablando, Vim soporta texto escrito en **UTF-8** y **Unicode**.

![Codificación](/Imagenes/Codificacion.png)

Vamos a poder seleccionar el texto "**visualmente**" antes de que "*operen*" en él, ej. copiar, remover, substituir, mover la posición a la izquierda o derecha, cambiar la capitalización de las letras o el formato del texto incluso preservando la indentación del mismo.  También la selección y operaciones en bloques de texto rectangulares.

Vim tiene comandos que completan su entrada de información sea con comandos, nombres de fichero, o palabras.

Del mismo modo tiene "*autocommands*" para la ejecución automática de los comandos (ej. decompresión automática de ficheros comprimidos).
Vim reconoce automáticamente el tipo de ficheros (**DOS**, **mac**, **Unix**) y también le permite el guardar el archivo en cualquier otro formato ¡no hay necesidad de usar unix2dos para usar en Windows nunca más!

Vim tiene una "*historia*" para los comandos y las búsquedas, así que usted puede llamar nuevamente los comandos o el patrón de búsqueda anteriores para editarlos.

Vim permite "*grabar*" una serie de acciones de edición para poder ejecutarlas nuevamente cuando se realizan tareas repetitivas.

Vim tiene límites de memoria mucho más grandes para la longitud de línea y el tamaño del almacenador intermediario (buffer) en comparación con VI normal.

Vim permite corregir de múltiples almacenadores intermediarios y puedes partir la pantalla en muchas *sub-ventanas* (**horizontal** o **verticalmente**), así que vas a poder ver muchos ficheros o muchas partes de algunos ficheros.

Vim tiene un lenguaje de escritura incorporado para poder extenderlo facilemente.

Vim permite el usar desplazamientos relativos para los comandos de búsqueda, así que se puede poner el cursor inmediatamente en el lugar *después* del texto encontrado.

Vim permite para salvar la información de una sesión de edición en un fichero ("*viminfo*") lo cual permite que sean usados en una subsecuente sesión de edición, ej.  la lista de almacenadores intermediarios, de las marcas de fichero, de los registros, comandos y de la historia de las búsquedas.

Vim puede expandir las tabulaciones dentro del texto usando caracteres de espacio (**expandtab**,**retab* **).

Vim permite el encontrar texto en ficheros usando un índice con las "*etiquetas*" (**tags* ***) junto con muchos otros comandos que manipulan la lista de de etiquetas.

Vim muestra el texto en color según su "*lenguaje (de programación)*".  Tu mismo puedes definir el "**lenguaje**" ("**sintaxis**") de los ficheros.
Viene con muchisimos ficheros de sintaxis para la colorisación del texto
en los lenguajes de programación comunes (*Ada*, *C*, *C++*, *Eiffel*, *FORTRAN*, *Haskell*, *Java*, *lisp*, *Modula*, *PASCAL*, *prólogo*, *Python*, *scheme*, *SQL*, *Verilog*, *VisualBasic*), programas de matemáticas (*arce*, *Matlab*, *Mathematica*, *SAS*), texto que use marcado específico (*DocBook*, *HTML*, *LaTeX*, *PostScript*, *SGML-LinuxDoc*, *TeX*, *WML*, *XML*, *Markdown*), retornos de programas (*diff*), ficheros de la configuració de programas (*Apache*, *autoconfig*, *BibTeX*, *CSS*, *CVS*, *IDL*, *LILO*, *mail*, *samba*), lenguajes de escritura del procesador de comandos (*shell*) y  de
configuración (shells: *sh*, *csh*, *ksh*, *zsh*), lenguajes de procesamiento de texto (*awk*, *Perl*, *sed*, *yacc*), ficheros de sistema (*printcap*, *Xdefaults*) y por supuesto para Vim y sus textos de ayuda.

Ademas de que tiene otras extenciones como snipets, o verificadores de sintaxis que lo hacen mucho mas pontente y mas cercano a un **IDE**, de ahi que les este dando una pequeña entrada sobre lo extraordinario que me resulta este editor.

En este momento me encuentro trabajando en algunas extenciones precisamente con este editor para hacerlo mas robusto y poder usarlo mas como un IDE para los lenguajes **C**, **C++**, **LaTeX**, **Python**, **Bash** entre otros. Al mismo tiempo estoy recolectando algunos scripts que me resalten sintaxis en varias librerias entre ellas esta Gtk, Gdk, MPI, OpenGL, ANSI-C, me encuentro trabajando en NCURSES y la de Linux Kernel-API.