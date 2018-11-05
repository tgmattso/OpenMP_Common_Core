

This directory contains exercises and solutions for a hands-on
OpenMP course.  Information about these programs can be found
in the comments and in the slides from the course.

To use these programs, copy the appropriate "def" file into
"make.def".  For example on a linux system running the gnu 
compilers, I'd type

  cp linux_gnu.def make.def

Then build the programs and test them

   make test

The solutions directory uses the same make.def file so to build
the solutions, just type "make test". 

We have tested these programs under Linux with the gnu and Intel compilers,
and on OS-X with the gnu environment loaded with Apple's xcode and homebrew
installations.  The Fortran STREAM codes at this time do not build on
Apple MacOS's xcode gcc installation due to an issue in linking with the
mysecond function.

We have not yet tested these programs with the PGI compiler (pgi.def) 
and Windows 7 with the Intel compiler (win_intel.def) so they may need 
some work. 
