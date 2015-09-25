# mve15

`mve15` is an electronic summplemnt of paper 

> F. Zapletal and M. Šmíd, Mean-risk Optimal Decision of a Steel Company under Emission Control

Only computations involving non-confidential data are described here

## Description of Computations

1. Contents of files `input/odbyty.gdt` (not included here) and `input/puvolenky.ods` were manually combined into `gretl/data.gdt` (the version present here is without the overall demands - variables PLOCHE a DLOUHE - due to confidential status of this data)

2. `gretl/analysis.inp` was run

3. Resulting values were imposed into `computations.ods` (see `Legend` sheet)
    
4. `R/stript.R` was modified by means of results from `computations.ods#computations` and run to produce `sample.csv`, serving as input of an optimization.

