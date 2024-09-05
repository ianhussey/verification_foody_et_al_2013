# A critical reanalysis of Foody et al. (2013) and Foody et al. (2015)



## Instructions to reproduce analyses

Knit the following .Rmd files in RStudio in the following order. Kniting the files will produce .html reports of the results as well as saving .pdf figures and .csv tables to disk.

- `code/foody et al 2013 publication/analysis_no_corrections.Rmd`
  - This file runs the analyses on the data extracted from the 2013 article without applying any alpha corrections.
- `code/foody et al 2013 publication/analysis_bonferroni_corrections.Rmd`
  - This file runs the same analyses on the same data, with the exception of applying bonferroni corrections.
- `code/foody et al 2015 publication/analysis_no_corrections.Rmd`
  - This file runs the analyses on the data extracted from the 2015 article without applying any alpha corrections.
- `code/foody et al 2015 publication/analysis_bonferroni_corrections.Rmd`
  - This file runs the same analyses on the same data, with the exception of applying bonferroni corrections.
- `code/multiverse/multiverse.Rmd`
  - This file loads from disk the results of each permutation of the analyses and creates multiverse plots from them.
- `code/comparisons with previous publications/analysis/analysis.Rmd`
  - This file plots data from previously published studies on distress inductions that included a negative control condition (i.e., post-delay measurement without an intervention). 





