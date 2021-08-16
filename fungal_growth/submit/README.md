In order to run the project correctly you must run the included files in the following order 

1. eda.Rmd - containing the exploration of the various datasets
2. diff_exp.Rmd - containing the analysis for the first research question (which genes are differentially expressed)
3. feature_selection_linear.Rmd - containing the analysis for the second research question (which k-mers are important)

It is important to run the files in this order, because some .Rmd, write csv files on the "data" folder, that are then used by other .Rmd files.