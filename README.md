# Chandra_pipeline

Pipeline for creating and fitting maps of clusters using standard CIAO and Python. 

Methods include adaptive binning, circle with minimum number of counts, contbin (from Jeremy Sanders), ggm and directional gradient kernels, hardness, unsharp masks.

Xray modelling scripts created for SPEX and XSPEC.




## Setup
**1.[Install Anaconda installer in Ubuntu 18.04LTS:](https://docs.anaconda.com/anaconda/install/linux/)**

**2[.Run the following code in a terminal to install ciao and caldb and some associated software in a conda environment named “ciao-4.14”.](https://cxc.cfa.harvard.edu/ciao/download/)**

$conda create -n ciao-4.14 -c https://cxc.cfa.harvard.edu/conda/ciao -c conda-forge ciao sherpa ds9 ciao-contrib caldb_main marx jupyter jupyterlab numpy astropy scipy scikit-learn pandas seaborn


**3.Activate the new conda environment.**

$source activate ciao-4.14
