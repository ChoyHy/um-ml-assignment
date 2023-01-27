# Code
## Preparation for Anaconda

#Create New Conda environment with needed libraries#
conda create -n um-ml-1 python=3.9 intelpython3_full numpy pandas jupyter scipy matplotlib xlrd scikit-learn scikit-learn-intelex -c intel

conda install -c conda-forge wfdb pyarrow

#Create New Conda environment with file
conda env create -f .\environments.yml
conda activate um-ml-1
jupyter notebook

# Assignment

Document: https://docs.google.com/document/d/12Gdo317lVRz_cjC9YeRceklOVhsT6dWo/edit


# Knowledge

## Brief about ECG
https://www.youtube.com/watch?v=1Q8YSpMcO-8
https://www.youtube.com/watch?v=mUY2nWqdPxA

## Sample of Reading Heartrate from ECG
https://github.com/MIT-LCP/wfdb-python/blob/main/demo.ipynb

## Some materials and questions about datasets (need to consider)
https://docs.google.com/document/d/1xXC9Xx7qPqBOLbRrFt79nSMc_GW4Kyby2sCvp0wVAFc/edit

## Sample of respiration processing
https://github.com/catiamcepeda/Respiration-Guide

## Sample of research using the same dataset
https://ieeexplore.ieee.org/document/7756310

## Estimating heart rate using respiratory data (pulse oximeters)
https://ncbi.nlm.nih.gov/pmc/articles/PMC1478836/pdf/brjsmed00027-0052.pdf
