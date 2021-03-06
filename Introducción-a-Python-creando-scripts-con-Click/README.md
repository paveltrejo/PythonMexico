# Taller: Introducción a Python creando scripts con $ Click_

| Impartido por | Twitter | Telegram | Github |
| ------------- | ------- | -------- | ------ |
| **Perla Godinez** | @Perla_GCastillo | Perla Castillo | @PerlaGCastillo |
| **Jose Carlos Melgoza** | @Jose_Carlos_Mz | Jose Carlos Melgoza | - |
| **Ricardo Torres** | @rctorr | @rctorr | @rctorr |


Durante este taller vamos ver una introducción al lenguaje de programación Python por medio de la creación de scripts para crear nuestros propios comandos que podrán ser utilizados desde la terminal.

Se crearán scripts muy básicos, pero que permitirán aprender a usar varios elementos del lenguaje Python y que podrán aplicar en sus propias necesidades.

## Requisitos:

- Contar con un editor de código instalado como puede ser Sublime Text, Atom, Brackets, Notpadd++, Vim, Emacs y otro que sea de tu preferencia.
- Instalar Python 3 en tu laptop, para ello sugerimos descargar Miniconda para Python 3.7 para tu sistema operativo e instalarlo con las opciones por default.
- `Miniconda`: Para instalar Python en las plataformas Windows, Mac OS y Linux con características homogéneas.
https://conda.io/miniconda.html (Para descargas)
https://conda.io/docs/user-guide/install/index.html (Instrucciones de instalación para cada sistema operativo)

- `$ Click _`: Módulo de Python que nos ayudará a simplificar la creación de scripts http://click.pocoo.org/5


## Temario:
### [Script 1. hola.py tuNombre](script_01_hola_python/)

Realizamos 5 versiones de este script, donde veremos desde com imprimir información a la salida estándar, hasta como leer los argumentos de la linea de comandos y agregar opciones como la famosa --help.

### [Script 2. holaclick.py TUNOMBRE](script_02_hola_click/)
Acá reazamos sólo 2 versiones y es similar al script `hola.py`, pero usando el módulo [`click`](http://click.pocoo.org/5).

### [Script 3. l.py PATH](script_03_lista_archivos/)
Este script es similar al comando `ls` de Linux o Mac o al `dir` de Windows e imprimirá en la salida estándar la lista de archivos del directorio indicado por PATH, haremos 2 versiones, en la segunda versión la salida será en formato CSV usando la opción `--to-csv.`

### [Script 4. genpass.py](script_04_genera_constrasena/)
Este script genera una clave segura usando como base el alfabeto inglés en mayúsculas, minúsculas y digitos.


## Presentaciones:
[Sesión 1](presentaciones/Crea-tus-propios-comandos-en-Python-1.pdf)

[Sesión 2](presentaciones/Crea-tus-propios-comandos-en-Python-2.pdf)

## El intérprete de Python
El intérprete de Python es una gran herramienta disponible en todo momento para ejecutar pruebas de código de forma inmediata, debido a que Python es un lenguaje interpretado.

### iPython
`iPython` es un shell interactivo que añade funcionalidades extra al modo interactivo incluido con Python, como resaltado de líneas y errores mediante colores, una sintaxis adicional para el shell, autocompletado mediante tabulador de variables, módulos y atributos; entre otras funcionalidades.


Instalando ipython:
```$ pip install ipython```

# referencias

- https://es.wikipedia.org/wiki/IPython
