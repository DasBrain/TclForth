##TclForth

A multi-platform desktop Forth. - Version 0.6.1

####Overview
TclForth uses Tcl/Tk as its native language. The Forth source code is compiled to Tcl procedures for execution in the Tcl run time system. Tcl commands and Forth words coexist as a symbiosis of Tcl and Forth. 


####Features#

* Universal desktop Forth, runs in Windows, OS-X, Linux, and more. 
* Native data types array, string, list, and dict.
* Native local variables.
* Native graphical toolkit based on Tk.
* Native database (Metakit).
* TclForth is provided as desktop apps for Windows and OS-X

Tcl view

* Arguments and results are transferred on a parameter stack. 
* Concatenative/postfix notation.

###Installation

TclForth is provided in two versions.

####Autonomous Version: [Release 0.6.1](https://github.com/wolfwejgaard/tclforth/releases) 

The executables are Tcl Starpacks with TclForth version 0.6.0.

* TclForth060.exe for Windows
* TclForth060.app for OS-X



####Experimental Version: [Release 0.6.0](https://github.com/wolfwejgaard/tclforth/releases) 

The executables for Windows and OS-X contain a Tcl runtime and a load routine for the external TclForth source. This allows easy changes of the systems.

* Download the executable and the source code
* Store the executable together with the source *folder*.
* Windows: Run tclforth.exe
* OS-X: Run tclforth.app

* Linux: Start tclforthx in a terminal. In the Tcl console:

```
    cd <source-directory>
    source tfmain.tcl
```

####Guide

See the [Wiki](https://github.com/wolfwejgaard/tclforth/wiki).

####Forum

See the [Issues](https://github.com/wolfwejgaard/tclforth/issues).


###Release Notes

#####Version 0.6.0

* Adapted to GitHub conventions:
* The TclForth systems are now provided as releases.
* Semantic versioning.

#####Version 0.57

* Console: New prompt, command line starts at the left border
* Console: Accepts pasting of source with multiple units/definitions 
* Forth: Command 'range' added to strings
* Wiki: updated

######Version 0.56

* Console: Continue the command string on a new line with \<Ctrl+Enter\>
* Console: Put immediate action on the command line inside [ ]
* Tcl: If TclForth is started in a terminal, the terminal becomes the Tcl console (e.g. Linux)
* Forth: Word 'mod' added (alias of %) 
* Debugged: list join ,   ."  






