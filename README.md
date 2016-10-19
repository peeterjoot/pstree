# pstree
import of http://www.thp.uni-due.de/pstree/

-*-Text-*-

Introduction:
-------------

   This is pstree V 2.39. It is a small program that shows the ps
   listing as a tree (as the name implies...). It has several options
   to make selection criteria and to change the output style.

   It should compile under most unixes, tested are AIX, Linux, HP-UX,
   A/UX, SunOS, Solaris, (Free|Open|Net)BSD, MacOSX/Darwin, and others.

   Under AIX & Linux, pstree directly reads the process table using
   getproc()/getuser() or the /proc file system. Under all other
   Un*xes pstree reads the output of /bin/ps.

   If process group information is available, process group leaders
   are marked with a '=' instead of '-'.

Compilation:
------------

   Take an ANSI C compiler, eg., gcc, and just enter

   $ [g]cc -O -o pstree pstree.c

   There is no Makefile.

Installation:
------------

   Put pstree into appropriate bindir, e.g., /usr/local/bin.
   Optionally, put the manpage pstree.1 to, e.g., /usr/local/share/man/man1.

   Have fun, 

        Fred

Changes:
--------

   See pstree.c
