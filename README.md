# fasta2GTF

by Daniel J leite


drdanieljleite@gmail.com

_________________________________
Requirements
============
The script has been written for Python3.7. 

It uses BioPython which can be install as shown here (https://biopython.org/wiki/Download).

Description
===========
This python3.7 script takes a fasta file and generates a GTF file. For each of the sequences present in the fasta file, three lines are generated in the GTF file, relating to gene, transcript and exon.


Usage
=====
fasta2GTF.py only requires a fasta file as an input (```-i```) and the specified location of the output GTF (```-o```). The help option (```-h```) in the command line also shows these requirements.


