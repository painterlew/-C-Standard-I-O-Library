# -C-Standard-I-O-Library
UW Bothell - CSS 503 - Spring 2016 - design own core input and output functions of the C++ standard I/O library

1. Purpose
In this programming assignment, we will design our own core input and output functions of the C/C++
standard I/O library, namely stdio.h.
2. Unix I/O

The Unix-based operating systems such as Linux, Mac OS/X, and Solaris provide system calls for file
I/O: open( ), read( ), write( ), and lseek( ). However, their problems are two-fold: (1) they are block-based
data but not on character-based data transfers, and (2) they are OS-dependent and thus cannot be used in
other platforms including Windows. This is the motivation of preparing the C/C++ standard I/O library.
