# Introduction-to-Medical-Image-Analysis

This repository contains several interesting jupyter notebooks which can guide you to understand the basic idea of Medical Image Analysis

# Contents

## [Image Filtering and Segmentation](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Filtering%20and%20Segmentation/Image%20Filtering%20and%20Segmentation.ipynb)
#### Load Images in NIfTI Format
#### Visualization Volumetric Images in Python
#### Interpolation
#### Separable Convolution Filters
#### Non Linear Separable Filter
#### Non Linear Non Separable Filters
#### Recursive Filters
#### Smoothing Filters
#### Gradient Filters
#### Image Contour Extraction
#### Mathematical Morphology
#### Distance Maps
#### Fast Marching

## Image Segmentation
#### [Validation of Segmentation Algorithms](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/Validation%20of%20segmentation%20algorithms.ipynb)
#### [GMM Brain Segmentation](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/GMM%20Brain%20Segmentation.ipynb)
#### [GMM Brain Segmentation with Bias Field Correction](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/GMM%20Brain%20Segmentation%20with%20Bias%20Field%20Correction.ipynb)
#### [K-means Brain Segmentation](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/K-means%20Brain%20Segmentation.ipynb)

# How to use?
## Using a Python virtual environment
We recommend using a Python virtual environment, but that of course, is up to you. 
### create a Python virtual environment
```
conda create --name virt_conda
```
!NOTE: This command you need to use it only once when you create the virtual environment. After the creation, you only need to activate/deactivate the virtual environment.
### activate the virtual environment
```
source activate virt_conda 
```
!NOTE: Make sure to activate the environment, before proceeding with the installation of the dependency packages.
### leave the virtual environment
```
conda deactivate
```
## Install the package
The dependencies are included as part of the requirements.txt file in each directory, so there is no need for a dedicated installation step.
pip3 install requirments.txt