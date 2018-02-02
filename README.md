# GTK+ 3 Tutorial
This GTK+ 3 tutorial is a collection of examples on how to build GUI apps using the GTK+ 3 toolkit. The examples are written in the C 
programming language. Each example shows how a particular widget can be used.

## Installing GTK+ 3

The GTK+ library and its dependencies must be installed on your system first in order to compile code that uses GTK+

On Linux:
```
  sudo apt-get install libgtk-3-dev
```

On Windows using MSYS2:
```
  pacman -S mingw-w64-x86_64-gtk3
```
  
## Compilation

The code can be compiled as follows:

On Linux:
```
  gcc -Wall -O -o example example.c `pkg-config --cflags --libs gtk+-3.0`
```

On Windows using MSYS2:
```
  gcc -Wall -O -o example.exe example.c `pkg-config --cflags --libs gtk+-3.0`
```

