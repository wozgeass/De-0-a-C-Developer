#Editores
Como lo dije casi al principio, el editor que desees usar para desarrollar es irrelevante, lo que pretendo ahora es mostrarte con gran detalle y detenimiento las bondades de mi editor favorito por lo que iniciaremos con su nombre:

![Vim](/Imagenes/logos/Vimlogo.svg)

Se muy bien que existen varios editores pero este en especial me ha parecido muy sencillo y poderoso, ademas me encuentro trabajando en algo que contare mas adelante y te facilitara en gran medida la vida si es que quieres programar usando este editor.

# Vim 
Como ya dijimos **Vim**  o ("**VI IMproved**") es un clon de **Vi**, es decir, un programa similar al editor de textos "**Vi**".

**Vim** no solo trabaja en modo de texto en cualquier terminal, sino que también tiene un interfaz gráfica para el usuario, es decir, menús y soporte para el ratón.

![Vim](/Imagenes/GVim.png)

Está disponible para muchas plataformas y tiene muchas características añadidas en comparación con **Vi**. Es compatible con casi todos los comandos de **Vi** - excepto con los errores.

Esta disponible en un gran numero de sistemas operativos entre ellos:
Linux:
- *Linux*:

![Linux](/Imagenes/logos/Linux.svg)

- *OSx*:

![OSX](/Imagenes/logos/Apple.svg)

- *Windows*:

![Windows](/Imagenes/logos/Windows.svg)

- Si eres usuario de sistemas *BSD* debo informarte que también lo vas a poder usar:
![FreeBSD](/Imagenes/logos/Freebsd.svg)

El copyright está en las manos del autor principal y mantenedor, **Bram Moolenaar** <bram@vim.org>.  **Vim** es un "**programa-de-caridad**" "**charity-ware**"), es decir que se sugiere que hagas una donación y en especial a una asociacion de huérfanos en Uganda.

Y si te lo preguntabas vim a pesar de entrar en **charity-ware** es software *Open Source* y todos los que quieran apoyar son bienvenidos para contribuir en algo al proyecto.

## Características
Es un editor para un Principiante - Amigable para el usuario:

Es mucho más fácil para los principiantes que *VI* debido a la disponibilidad de ayuda en línea bien extensa, comandos para "deshacer" (undo) y "rehacer" (redo) (¡no te preocupes mucho con los errores - simplemente usa undo y redo!),  soporte para el ratón y también iconos y menús configurables (GUI).

Soporta la edición de derecha-a-izquierda (ej. con el **Árabe**, **Farsi**, **Hebreo**), y textos en **multi-octeto**, es decir, lenguajes con caracteres gráficos representados por más de un "**octeto**", por ejemplo **Chino**, **Japonés**, **Coreano (Hangul)**, técnicamente hablando, Vim soporta texto escrito en **UTF-8** y **Unicode**.

![Codificación](/Imagenes/Codificacion.png)

Vamos a poder seleccionar el texto "**visualmente**" antes de que "*operen*" en él, ej. copiar, remover, substituir, mover la posición a la izquierda o derecha, cambiar la capitalización de las letras o el formato del texto incluso preservando la indentación del mismo.  También la selección y operaciones en bloques de texto rectangulares.

**Vim** tiene comandos que completan su entrada de información sea con comandos, nombres de fichero, o palabras.

Del mismo modo tiene "*autocommands*" para la ejecución automática de los comandos (ej. Descompresión automática de ficheros comprimidos).
Reconoce automáticamente el tipo de ficheros (**DOS**, **mac**, **Unix**) y también le permite el guardar el archivo en cualquier otro formato ¡no hay necesidad de usar unix2dos para usar en Windows nunca más!

Tiene un "*historial*" para los comandos y las búsquedas, así que puedes llamar nuevamente los comandos o el patrón de búsqueda anteriores para editarlos.

Permite "*grabar*" una serie de acciones de edición para poder ejecutarlas nuevamente cuando se realizan tareas repetitivas.

Tiene límites de memoria mucho más grandes para la longitud de línea y el tamaño del almacenador intermediario (buffer) en comparación con **VI** normal.

Permite corregir de múltiples almacenadores intermediarios y puedes partir la pantalla en muchas *sub-ventanas* (**horizontal** o **verticalmente**), así que vas a poder ver muchos ficheros o muchas partes de algunos ficheros.

Tiene un lenguaje de escritura incorporado para poder extenderlo fácilmente.

Permite el usar desplazamientos relativos para los comandos de búsqueda, así que se puede poner el cursor inmediatamente en el lugar *después* del texto encontrado.

Permite para salvar la información de una sesión de edición en un fichero ("*viminfo*") lo cual permite que sean usados en una subsecuente sesión de edición, ej.  la lista de almacenadores intermediarios, de las marcas de fichero, de los registros, comandos y de la historia de las búsquedas.

Puede expandir las tabulaciones dentro del texto usando caracteres de espacio (**expandtab**, **retab* **).

Permite el encontrar texto en ficheros usando un índice con las "*etiquetas*" (**tags* ***) junto con muchos otros comandos que manipulan la lista de etiquetas.

Muestra el texto en color según su "*lenguaje de programación*".  Tu mismo puedes definir el "**lenguaje**" ("**sintaxis**") de los ficheros.
Viene con muchísimos ficheros de sintaxis para la coloración del texto
en los lenguajes de programación comunes (**Ada**, **C**, **C++**, **Eiffel**, **FORTRAN**, **Haskell**, **Java**, **lisp**, **Modula**, **PASCAL**, **prolog***, **Python**, **scheme**, **SQL**, **Verilog**, **VisualBasic**, **Ensamblador**, **Ruby**, **Javascript**), programas de matemáticas (**arce**, **Matlab**, **Mathematica**, **SAS**), texto que use marcado específico (**DocBook**, **HTML**, **LaTeX**, **PostScript**, **SGML-LinuxDoc**, **TeX**, **WML**, **XML**, **Markdown**, **Json**), retornos de programas (**diff**), ficheros de la configuración de programas (**Apache**, **autoconfig**, **BibTeX**, **CSS**, **CVS**, **IDL**, **LILO**, **mail**, **samba**,**Grub**, **Nginx**), lenguajes de escritura del procesador de comandos (**Shell**) y  de configuración (shells: **sh**, **csh**, **ksh**, **zsh**), lenguajes de procesamiento de texto (**awk**, **gawk**, **Perl**, **sed**, **yacc**), ficheros de sistema (*printcap*, *Xdefaults*) y por supuesto para **Vim** y sus textos de ayuda.

Ademas de que tiene otras extensiones como snipets, o verificadores de sintaxis que lo hacen mucho mas potente y mas cercano a un **IDE**, de ahí que les este dando una pequeña entrada sobre lo extraordinario que me resulta este editor.

En este momento me encuentro trabajando en algunas extensiones precisamente con este editor para hacerlo mas robusto y poder usarlo mas como un **IDE** para los lenguajes **C**, **C++**, **LaTeX**, **Python**, **Bash**, **Java**, **Javascript**, **Web** entre otros. Al mismo tiempo estoy recolectando algunos scripts que me resalten sintaxis en varias librerías entre ellas esta **Gtk**, **Gdk**, **MPI**, **OpenGL**, **ANSI-C**, me encuentro trabajando en la actualización de **Gtk**, **Gdk**, **Ncurses** y la de **Linux Kernel-API**.

## Iniciando con vim
Ya vimos por que **vim** es un editor muy potente y que ademas dispone de muchos mandatos, demasiados para ser explicados en este libro. Esta parte está dedicada para describir suficientes mandatos para que seas capaz de aprender fácilmente a usar **vim** como un editor de propósito general.

Es importante recordar que está parte es pensada para enseñar con la práctica. Esto significa que es necesario ejecutar los mandatos para aprenderlos adecuadamente. Si únicamente se lee el texto, se olvidarán los mandatos.

Para poder iniciar a usar el editor primero deberemos descargarlo para esto les dejare los siguiente enlaces:

1. [Pagina Principal](http://www.vim.org/)
2. [Preguntas Frecuentes](http://vimdoc.sf.net/)
3. [Código](https://github.com/vim/vim)

Como siempre mi recomendación sera la siguiente:

- Compilar unicamente si cumples con las dependencias de construcción y sabes lo que haces.
- De otro modo te recomiendo instalar **vim** con el gestor de paquetes de la distribución que estés ocupando:

    Para **Fedora** deberás usar el siguiente comando:
    > **dnf install vim**
    
    Para **Ubuntu** o **Debian** deberás usar el siguiente comando:
    > **apt install vim** ó **apt-get install vim**
    
    Nota: Hay un reporte sobre que no funcionan algunos plugins de vim para ello tendremos que instalar los siguiente:
    > **apt install vim-nox** ó **apt-get install vim-nox**
    
    Para **ArchLinux** deberás usar el comando siguiente:
    > **pacman -S vim**

    Para **Suse** deberás usar el comando siguiente:
    > **zypper install vim**

Una vez realizado todo esto seguiremos viendo como funciona **vim**. 

La ultima versión de **vim** es la **7.4.1990** hasta Julio 2016.

Para iniciar a ocupar el editor tendrás que hacerlo desde una terminal ejecutando lo siguiente:

```bash
$ vim <archivo>
```

De manera básica vim tiene varios modos entre ellos.
- **Normal**
- **Visual**
- **Insertar**
- *Entre algunos mas.*

Cuando entras a **vim** inicias el modo normal:
![VimModes](/Imagenes/VimTutorial/VimModes.png)

Pero al teclear algunas letras puedes acceder a algunos modos, aun que te parezca muy difícil al comienzo veras que te vas a acostumbrar muy pronto.

Para entrar al modo edición tendrás que teclear la letra "**i**".

![VimModes](/Imagenes/VimTutorial/Tecla-I.svg)

Esto mismo inmediatamente te cambiara de modo para que puedas iniciar la edición del documento.

Y para entrar al modo visual tendrás que teclear la letra "**v**".

![VimModes](/Imagenes/VimTutorial/Tecla-V.svg)

Esto mismo inmediatamente te cambiara de modo para que puedas seleccionar algunas parte de tu texto a tu gusto.

### Iniciando.
Ahora seguramente ya habrás incursionado en **vim** pero no sabes ni como salir ni guardar tus cambios. 
Para eso deberas pulsa la tecla "**Esc**" para asegurarte de que estas en modo **Normal**:

![VimModes](/Imagenes/VimTutorial/Tecla-Esc.svg)

Para salir de archivo sin guardar nada deberás pulsar las teclas:
**:q! <Enter>**
![VimModes](/Imagenes/VimTutorial/Salir-Sin-Guardar.svg)

Para salir del archivo guardando los cambios deberás pulsar las teclas: **:wq <Enter>**
![VimModes](/Imagenes/VimTutorial/Salir-Y-Guardar.svg)

Si lo que quieres es solo guardar tu archivo sin salir lo lograras pulsando las siguiente teclas:  **:w <ENTER>**
![VimModes](/Imagenes/VimTutorial/Solo-Guardar.svg)

### Moviendo el cursor.
Para mover el cursor, pulse las teclas **H**,**J**,**K**,**L** de la forma que se indica.

![Teclas de Movimiento](/Imagenes/VimTutorial/Moverse.svg)

Como  puede verse en la imagen la tecla **H** está a la izquierda y mueve el cursor a la izquierda, la tecla **L** está a la derecha y mueve el cursor a la derecha, la tecla **J** parece una flecha que apunta hacia abajo y mueve el cursor abajo por ultimo la tecla **K** parece una flecha que apunta hacia arriba y mueve el cursor arriba.

### Agregar texto al archivo.
Este editor es considerado como un editor modal, esto significa que puede tener diferentes comportamientos dependiendo del modo en el que nos encontremos y como vimos antes los 2 modos básicos son: **modo normal** y **Modo insertar**.
Desde el primer momento en el que ingresamos al editor nos topamos con el **modo normal**. Para ocupar el **modo inserción** teclearemos la letra "**i**":

![VimModes](/Imagenes/VimTutorial/Tecla-I.svg)

Y es así como ya podremos ingresar texto en nuestro archivo, ahora podrás iniciar la edición sin problemas hasta el momento en el que tecles <Esc>:

![VimModes](/Imagenes/VimTutorial/Tecla-Esc.svg)

### Borrando caracteres.
Existen muchas combinaciones para realizar el borrado entre las mas usuales se encuentra las opciones "**x**", "**dw**", "**dd**", "**d$**", "**d#**" y "de".

Donde:
- **x** Elimina un solo caracter.
- **dw** Elimina desde el cursor hasta el final de la palabra, incluyendo el espacio.
- **dd** Elimina toda una linea entera.
- **d$**