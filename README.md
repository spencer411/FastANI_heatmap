# FastANI_heatmap
This repository contains R code for building a heatmap and histogram with the output of FastANI.

the R code here can be run directly on the FastANI output file: https://github.com/ParBLiSS/FastANI

Because FastANI cannot compute lower ANI values, anything that lacks a pariwse comparisons in the outputfile will automatically be changed to a value of 70. So please note this needs to be addressed in the figure caption if comparing diverse isolates.

The color break here is set to 95, the species delimination threshold, but can be manipulated based on the needs of the study.

Example output figure below with *Staphylococcus schleiferi*:

![fastani_figure](https://user-images.githubusercontent.com/43999021/133113988-6f158758-68df-43dd-a8d0-0ac1770fbaf8.gif)
