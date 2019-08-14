# Isabelle-Simard

## Project repository

### Is combining different metrics of rs-fMRI more predictive of age than using only FNC?

I originally wanted to use my thesis data to build this pipeline. However, a war with ethics is keeping me away from it at the moment. My original idea is to asses if using multiple metrics of rs-fMRI (i.e. FNC, power spectra and statistical maps) is more predictive of recidivism in offenders than using only data from one metric. Hence, in the absence of my data of interest, I am going to build on the machine learning exercise that we did in class to see if combining FNC, power spectra and statistical maps of rs-fMRI is more predictive of age than only using FNC.

### Project Aims

1. Script and perform a machine learning model to predict age using rs-fMRI FNC
2. Script and perform a machine learning model to predict age using rs-fMRI power spectra
3. Script and perform a machine learning model to predict age using rs-fMRI neural activity
4. Script and perform a machine learning model to predict age using rs-fMRI FNC, power spectra and neural activity
5. Compare models 1, 2, 3 and 4 to see which one is the most predictive of age


### Dataset

* [MAIN Nilearn tutorial data](https://osf.io/5hju4/)
* Taken from this [publication](https://www.ncbi.nlm.nih.gov/pubmed/29531321)
* Already pre-processed using fmriprep see details [here](https://osf.io/wjtyq/)
* 155 participants watched a Disney movie passively (resting-state) while being in the scanner


### Tools/Language used

* Nilearn
* Python

### Machine learning model architecture
* Features shape for FNC = 155 x 2016

### Learning Aims

1. Learn how to use Nilearn
2. Reproduce age prediction Nilearn machine tutorial using FNC as predictor
3. Learn how to script other metrics of resting-state fMRI (i.e. power spectra and spatial maps) in Nilearn
4. Be able to use power spectra and spatial maps as marching learning predictors in Nilearn
5. Be able to script a machine learning algorithm that uses 3 different metrics of resting-state (i.e. FNC, power spectra and machine learning) as a predictor of a variable

### To-Do

- [X]  Read Nilearn documentation
- [X]  Data exploration and visualization
- [ ]  Re-run script age prediction machine learning tutorial using FNC
- [ ]  Read documentation on how to model spatial maps in Nilearn
- [ ]  Read documentation on how to model power spectra in Nilearn
- [ ]  Modify ML tutorial script to predict age using neural activity
- [ ]  Modify ML tutorial script to predict age using power spectra
- [ ]  Modify ML tutorial script to predict age using a combination of FNC, neural activity and power spectra
- [ ]  Read on techniques to statistically compare accuracy of machine learning algorithm
- [ ]  Statistically compare the performance of the 4 algorithms built


### Current issues

### Deliverables for Brainhack School 2019

### Further scope

