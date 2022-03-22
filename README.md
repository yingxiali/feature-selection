# Instructions for running the R code

This is the electronic appendix (R code) to the paper "Benchmark study of feature selection strategies for multi-omics data".

This repository contains 3 main types of files.

The first one is "down_data.R" whose function is to download the data needed for replicating the analyses presented in this paper from OpenML using the file "datset_ids.RData", which is also included in this repository.

The second one are the R files whose labels contain "AnalysisCluster". These allow for reproducing the benchmark study using the functions from the R files whose labels contain "Functions_AnalysisCluster".

The third one are the R files whose labels contain "Functions_AnalysisCluster". These feature functions which are used for applying the various considered feature selection and classification methods.


# Further details on the different R scripts

"AnalysisCluster.R" performs the benchmark study for the rank methods.

"AnalysisCluster_1.R" performs the benchmark study for Lasso.

"AnalysisCluster_2.R" performs the benchmark study for Rfe.

"AnalysisCluster__3.R" performs the benchmark study for GA.

Details on these approaches can be found in the paper.

