# Minecraft em python

Status: Em desenvolvimento

## Objetivo

+ Fazer uma copia do minecraft em python
+ Aprender um pouco mais sobre a linguagem 

## Gifs e Fotos do projeto

## Como começar

1) Instale o Python 3.6 ou mais recente. https://www.python.org/downloads/

2) Open cmd/terminal and type:
    <code>pip install ursina</code> 
<br>

Se você deseja ver ou instalar a versão mais recente você pode achar no GitHub, link abaixo:
<code>pip install https://github.com/pokepetter/ursina/archive/master.zip</code>
ou
<code>pip install git+https://github.com/pokepetter/ursina.git</code>
Lembre-se de que as coisas <strong>podem</strong> quebrar.

Se você quiser editar facilmente o código-fonte, é recomendado clonar o git
repo e instale como desenvolva assim. Certifique-se de ter git installed. ( https://git-scm.com/ )
<code>git clone https://github.com/pokepetter/ursina.git</code>
<code>python setup.py develop</code>

Além disso, instale qualquer uma das dependências opcionais que você deseja da lista abaixo,
ou instale-os todos com:
<code>pip install ursina [extras]</code>



On some systems you might have to use pip3 instead of pip in order to use Python 3 and not the old Python 2.
If the pip command is not found, you can use:
<code>python -m pip install ursina</code>

### Dependencias

    • python 3.6+
    • panda3d
    • screeninfo, for detecting screen resolution
    • pillow, for texture manipulation

    • psutil, for measuring memory usage (optional)
    • hurry.filesize, for converting bytes to megabytes (optional)
    • imageio, for recording and converting to gifs (optional)
    • psd-tools3, for converting .psd files (optional)
    • blender, for converting .blend files (optional)

    Optional dependencies must be installed manually.

## Referencia para a criação do projeto

Feito com base no video abaixo
+ https://www.youtube.com/watch?v=DHSRaVeQxIk
