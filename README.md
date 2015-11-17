# Overlap
This is a program to intersect two sets of genomic features.
There are two mandatory arguments, file1 and file2, which are two gff version 2 files including the genomic features to intersect.
The program will report a gff version 2 file corresponding to file 1 with additional information about the intersection with features of file 2.

# Installation
We provide a pre-compiled binary for linux (64 bit architecture) called overlap, however if this does not work you can install overlap from the sources.
For this you will need to have ocaml installed.

The steps are the following
$ git clone https://github.com/sdjebali/Overlap.git
$ cd Overlap
$ make
This should produce the executable called overlap that you can use on two gff2 files.
Typing overlap with no argument will provide you with the help.
