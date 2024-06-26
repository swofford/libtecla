# libtecla
### A fork of the _libtecla_ command-line editing library written by Martin Shepherd

This repo is a fork of the (still useful) _libtecla_ command-line editing library, written by Martin Shepherd at CalTech and most recently updated in 2014. I use _libtecla_ as an alternative to GNU Readline, thereby avoiding GPL contamination. Having the source as a git repo allows me to place minor compatibility fixes under version control (and perhaps these updates will be useful to others).

I have retained the original license from the [official download site](https://sites.astro.caltech.edu/~mcs/tecla/); see [LICENSE.TERMS](LICENSE.TERMS). This is a non-copyleft license ("X11") similar to the MIT license. I do not claim copyright on my changes. All code from version 1.6.3 and earlier retains the copyright of Martin C. Shepherd.

Dave Swofford
dave@phylosolutions.com

## Original README file follows:

This is version 1.6.3 of the tecla command-line editing library.

For the current official release, please direct your browser to:

  http://www.astro.caltech.edu/~mcs/tecla/index.html

The tecla library provides UNIX and LINUX programs with interactive
command line editing facilities, similar to those of the unix tcsh
shell. In addition to simple command-line editing, it supports recall
of previously entered command lines, TAB completion of file names, and
in-line wild-card expansion of filenames.  The internal functions
which perform file-name completion and wild-card expansion are also
available externally for optional use by programs, along with a module
for tab-completion and lookup of filenames in a list of directories.

Note that special care has been taken to allow the use of this library
in threaded programs. The option to enable this is discussed in the
Makefile, and specific discussions of thread safety are presented in
the included man pages.

For instructions on how to compile and install the library, please see
the INSTALL file, which should be in the same directory as this file.

Copyright and Disclaimer
------------------------
Copyright (c) 2000, 2001, 2002, 2003, 2004, 2012, 2014 by Martin C. Shepherd.

All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, and/or sell copies of the Software, and to permit persons
to whom the Software is furnished to do so, provided that the above
copyright notice(s) and this permission notice appear in all copies of
the Software and that both the above copyright notice(s) and this
permission notice appear in supporting documentation.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF THIRD PARTY RIGHTS. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR
HOLDERS INCLUDED IN THIS NOTICE BE LIABLE FOR ANY CLAIM, OR ANY SPECIAL
INDIRECT OR CONSEQUENTIAL DAMAGES, OR ANY DAMAGES WHATSOEVER RESULTING
FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT,
NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION
WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

Except as contained in this notice, the name of a copyright holder
shall not be used in advertising or otherwise to promote the sale, use
or other dealings in this Software without prior written authorization
of the copyright holder.
