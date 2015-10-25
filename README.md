# Bioinformatics-Tools
General scripts for dealing with sequencing files and data extraction

<b>countTA.pl</b>

A perl script that takes a fasta file and counts the number TA sites. 
This is useful for Transposon Sequencing when we want to know the ratio of transposon insertions 
(which happen at TA sites) to TA sites for a given region. For example, the ratio is used in the essentails 
analysis which calculates the p-value for a region given insertion representation</br>

<b>getCoordsGBK.py</b>

A python script that takes a genbank file and outputs a file with all the gene ids and their genomic start and end coordinates. This script is useful for creating genomic tracks in Gviz (R package).

