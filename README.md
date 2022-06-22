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

**4. Download ACIS background event files (Full Release) from [here](https://cxc.cfa.harvard.edu/ciao/download/caldb.html)** 

unzip the files to ~/anaconda3/envs/ciao-4.14/CALDB (e.g. /home/zareef_otg/anaconda3/envs/ciao-4.14/CALDB)


**5.[Download and install HEASOFT Software:](https://heasarc.gsfc.nasa.gov/lheasoft/download.html)**

Select "Source Code" and check "PC - Linux - Ubuntu" in "STEP 1 - Select the type of software"

Select all in "STEP 2 - Download the desired packages" and click submit.

Follow this [INSTALLATION](https://heasarc.gsfc.nasa.gov/lheasoft/ubuntu.html) to install HEASOFT.


**6.[Downloda and install Contour binning and accumulative smoothing software](https://github.com/jeremysanders/contbin)**

Open terminal type "git clone https://github.com/jeremysanders/contbin"

Go to the downloaded folder directory.

Type "make" and press enter.

Then type make install and press enter.

