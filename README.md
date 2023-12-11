# Makefile Template

Note: When using VSCode and Makefile Tool extension, disable Intellisense contribution in the /.vscode/c_cpp_properties.json file.
The extension doesn't work with the rescursive shell functions in this makefile.  The end result is red squiggles and header files not found in VSCode.

The main feature of this Makefile is Automatic Dependency Generation using gcc -M. (http://make.mad-scientist.net/papers/advanced-auto-dependency-generation/)
Using this Makefile you never need to change the Makefile when changing project files! :)

```sh
$ make 
$ make debug (default)
$ make release
$ make clean
```
