# ARM-CPU-Application-code-and-drive
High performance computing application on Arm

Profile with Arm MAP

Arm MAP is a parallel profiler that shows which lines of code took the most time and why. It supports both interactive and 
batch modes for gathering profile data, and supports MPI, OpenMP and single-threaded programs. Syntax-highlighted source code with
performance annotations, enable to drill down to the performance of a single line, and a rich set of zero-configuration metrics
help you visualize memory usage, floating-point calculations and MPI usage across processes.

Writing Code for ROM

Build ROM images for embedded applications to deploy writing code for ROM. Write code for ROM, shows different methods for simple
and complex images. Sample initialization code is given, as well as information on initializing data, stack pointers, interrupts.

Using scatter loading to build complex images.

A scatter loading application that runs under the ARMulator, and also uses sprintf() from the Embedded C library. displays the
linker-generated scatter symbols on the screen. More complex scatter loading application that runs from Flash memory on an 
ARM Development Board (PID7T).

Writing the device drivers

Hardware is the main area of the porting operation, and is completely application dependent. The device drivers provided with 
the PID Angel port can provide a starting point, but in many cases the developer must completely recode the source files. 
The simplest approach is to use the main functions defined in the PID code and rewrite the underlying functionality.

