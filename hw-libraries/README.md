# hello world library

This is a basic demostration of how to use `CMake` to compile and install 
libraries.

## Library installation and uninstallation

To compile and install the library:

    $ cd hw-libraries
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ make install

Note that the default installation path is `/usr/local`. You can change this 

    $ make DESTDIR=<YOUR DIR> intall


To uninstall the library:
    
    $ rm `cat install_manifest.txt`

## Example

In the `example` directory there is a demo of how to use the library that we 
just intalled. You can use `CMake` to compile it. Or simply run

    $ gcc -lhw -o main main.c

    
