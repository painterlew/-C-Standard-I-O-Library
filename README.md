# C++-Standard-I-O-Library

1. Purpose:
In this program, I design my own core input and output functions of the C/C++ standard I/O library, namely stdio.h.

2. Motivate:
The Unix-based operating systems such as Linux, Mac OS/X, and Solaris provide system calls for file I/O:
open( ), read( ), write( ), and lseek( ). However, their problems are two-fold: (1) they are block-based
data but not on character-based data transfers, and (2) they are OS-dependent and thus cannot be used in
other platforms including Windows. This is the motivation of preparing the C/C++ standard I/O library.
Also, through this project, I practiced and got familar with IO system calls.

