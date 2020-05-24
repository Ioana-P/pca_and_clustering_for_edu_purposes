# Unsupervised Learning:
# Using Dimensionality Reduction (PCA and Truncated SVD / LSA) as well as some examples of clustering
Upon request from a few students in their final cohort, I ran a short tutorial recapping content on Principal Component Analysis, Singular Value Decomposition and on on a couple of different types of clustering.
The Jupyter Notebooks are left un-refactored on purpose for showing code application to students. 

Both of the notebooks illustrate a process of performing dimensionality reduction on different canonical datasets, respectively:
 - sklearn's wine dataset
 - sklearn's 20 Newsgroups dataset
 
 
 The Learning Outcomes from this session:
 
  * students will understand the mathematical method behind Principal Component Analysis and be able to explain it
  * students will be able to explain how Singular Value Decomposition differs from PCA
  * students can apply both of these techniques to different types of data, having just gone through two examples of their usage
  * students can see how classification models can be used with decomposed data (both via PCA and LSA)
  * students can apply at least one clustering method and explain the process by which it divides data, as well as state why clustering will not always return good results
 
 Index:
 
newsgroups_clustering.ipynb - contains examples of text preprocessing and analysis as well as LSA via Sklearn's TruncatedSVD
pca_cluster_glass_data.ipynb - PCA and clustering performed on sklearn's glass dataset;
glass.csv - sklearn's glass dataset;
archive - directory for discarded notebooks
