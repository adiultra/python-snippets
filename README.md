# Python Snippets for Atom

## Install :

`apm install python-snippets`

#Note :fire:

This package is Under considerable development. Please don't Be too excited. Also You can help if you want to. :smile:

## Features

- Some important python 3.0 snippets of regular usage.

- Also includes tkinter snippets for gui-programming in python.


## Snippets list

> The tkinter snippets assume that you have imported tkinter as tk
> `import tkinter as tk`

```css
    #  Normal missing Functionality

  'def'
    'body': '''
    def ${1:fname}(${2:arg}):
        ${3:pass}
    '''
  'defi'
    'body': '''
    def __init__(self, ${1:arg}):
        ${2:pass}
    '''
  'print'
    'body': 'print($1)'


    # tkinter snippets
  'button'
    'body': 'tk.Button(${1:root}, text="$2")'

  'label'
    'body': 'tk.Label(${1:root}, text="$2")'

  'frame'
    'body': 'tk.Frame(${1:root})'

  'entry'
    'body': 'tk.Entry(${1:root})'

  'grid'
    'body': 'grid(row=$1, colomn=$2)'

  'sticky'
    'body': 'sticky=tk.$1'

  'checkbutton'
    'body': 'tk.Checkbutton(${1:root}, text="$2")'

  'mainloop'
    'body': 'mainloop()'
```
