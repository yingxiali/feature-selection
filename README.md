# Instructions for running the R code

This is the electronic appendix (R code)
to our paper, Benchmark study of feature selection strategies for multi-omics data.


The directory contains 3 main types of files, 

The first one is down_data, whose function is to download the data needed for this paper from OpenML using "datset_ids.RData".

The second one is AnalysisCluster, whose function is to  perform the benchmark study using the functions from the
Functions_AnalysisCluster files.

The third one is Functions_AnalysisCluster, which contains various feature selection processes and classification processes

# feature-selection

AnalysisCluster.R performs the benchmark study using the function
Functions_AnalysisCluster.R, Functions_AnalysisCluster.R for rank methods.

AnalysisCluster_1.R performs the benchmark study using the function
Functions_AnalysisCluster_1.R, Functions_AnalysisCluster_1.R for Lasso.

AnalysisCluster_2.R performs the benchmark study using the function
Functions_AnalysisCluster_2.R, Functions_AnalysisCluster_2.R for Rfe.

AnalysisCluster__3.R performs the benchmark study using the function
Functions_AnalysisCluster_3.R, Functions_AnalysisCluster_3.R for GA.
