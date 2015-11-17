# Overlap
This is a program to intersect two sets of genomic features.
There are two mandatory arguments, file 1 and file 2, which are two gff version 2 files including the genomic features the user wants to intersect.
This program will report a gff version 2 file corresponding to file 1 with additional information about the intersection with the features of file 2.

# Installation
We provide a pre-compiled binary for linux (64 bit architecture) called overlap, however if this does not work you can install overlap from the source.
For this you will need to have ocaml installed.

Then you just need to follow the steps below:

$ git clone https://github.com/sdjebali/Overlap.git

$ cd Overlap

$ make

This should produce an executable called overlap that you can use on two gff2 files of your choice-
Typing overlap with no argument will provide you with the help.
