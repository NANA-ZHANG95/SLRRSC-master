SLRRSC: Spectral clustering based on learning similarity matrix
Overview
aamain1.m:demo.
adparameter.m:调参
SLRRSC.m: Obtain the target similarity matrix Z
Cal_ARI.m/Cal_NMI.m /purity.m:聚类性能指标
func_simlarity.m:计算相似性矩阵similarity matrices using Gaussian kernels

simulation_model.m:生成模拟数据集
簇数估计

Directory

All the functions used in the proposed algorithm are located in the directory "Code".

**All the codes generating figures shown in the manuscript are located in the directory "Figure_generate".

All the resulting files are located in the directory "Results".

The scRNA-seq data sets used in the manuscript are located in the directory "single-cell data".



The 8 data sets are provided in the directory Data.

Specifically, the dataset of 
Data_Deng.mat refers to http://science.sciencemag.org/content/343/6167/193.

Data_Ting.mat refers to https://www.ncbi.nlm.nih.gov/pubmed/25242334.

Data_Treutlin.mat refers to https://www.ncbi.nlm.nih.gov/pubmed/24739965.

Data_Buettner.mat refers to https://www.ncbi.nlm.nih.gov/pubmed/25599176.

Data_Pollen.mat refers to https://www.nature.com/articles/nbt.2967.

