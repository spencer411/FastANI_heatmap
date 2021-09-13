# FastANI_heatmap
This repository contains R code for building a heatmap and histogram with the output of FastANI.

the R code here can be run directly on the FastANI output file: https://github.com/ParBLiSS/FastANI

Because FastANI cannot compute lower ANI values, anything that lacks a pariwse comparisons in the output file will automatically be changed to a value of 70. So please note this needs to be addressed in the figure caption if comparing such highly diverse isolates.

The color break here is set to 95, the species delimination threshold, but can be manipulated based on the needs of the study.

Example figure below with *Staphylococcus schleiferi* isolates:

<img width="997" alt="heatmap" src="https://user-images.githubusercontent.com/43999021/133120697-10be7952-e8ca-4d4e-a300-3421d73e0127.png">

