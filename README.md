# SSOO-tarea01 Nombre:Fabián Alexis Vidal Torres Correo:fabian.vidalt@alumnos.uv.cl

Introduccion:En esta seccion se indicará el como se llevo a cabo la resolución de los ejericios planteados en esta tarea , indicando las herramientas y fuentes de informacion consultadas para el desarrollo de cada punto respectivo.

Preguntas:

A)Mediante un servidor de Linux instalado en virtual box, se efectuó el uso de la herramienta man [comando], se realizaron pruebas para los distintos comandos que se debian ejecutar, a su vez también, se recopilo información de internet de distintas páginas pero principalmente en https://ed.team/.

B)En este ejercicio se buscó primeramente información en páginas de internet, posterirmente se hicieron pruebas en el servidor de la máquina virtual.A continuación se adjuntan las url de los sitios web consultados:
https://desktop.arcgis.com/es/arcmap/latest/extensions/data-reviewer/metacharacters-used-to-build-regular-expressions.htm
https://www.youtube.com/

C) Para la solucion de este problema se utilizó la herramienta brace expantion con el siguiente formato de entrada :

Comando : mkdir 2021-{01..12}-{01..31}

Se puede vizualizar que se crean varios direcotrios utilizando el comando "mkdir", estos directorios llevan el nombre de una combinación de cadena de caractéres.Inciando con "2021-", esta cadena se combina con cadenas de textos que representan números entre un rango del 1 al 12 siendo estos los meses de año, estos números posteriormente se combinan con otras cadenas de textos con números que van desde el 1 al 31, los cuales representan los 31 días de un mes.
Como resultado final se tiene la creacion de 12x31 directorios con distintos nombres cada uno, indicando todos los dias del año.

D) Para la resolucion de este ejricio se recopílo informacion de la siguiente pagina:
https://codigofacilito.com/articulos/pipes

Mediante el uso de pipes se ejecutan los comandos que ayudan a filtrar la infomracion que se desea saber.

E)Con el uso de la maquina virtual en un ambiente de linux, se procedió a ejecutar el comando "pintenv", este comando facilito la visualización del contenido de las variables locales que se querian saber, posteriormente se recopiló información de páginas de internet para verificar el resultado entregado.

F)Para el desarrollo de este ejercicio se decidió optar por un bucle for, el cual lista los parámetros de entrada del script,el factor fundamental en este código son el uso de las variables en bashya que, conociendo el significado de las variables especiales en el enotrno de bash se pueden rescatar los valors de cada parametro de entrada.

$0 = representa el valor del primer parametro en la consola.
$1 = representa el valor del segundo parametro en la consola.
...
$* = representa la lista de parametros ingresada por el usuario.
$$ = representa el PID del proceso en ejecución

De esta manera mediante una variable y un ciclo for se lista los paramnetros ingresados por consola.Posteriormente con el uso de pipes y los comandos echo y head el cual muestra el contenido de las primeras 10 lineas de un archivo se imprime el contenido solicitado.
Información de las variables recopilada en: https://atareao.es/tutorial/scripts-en-bash/variables-en-bash/
