# Introduction-to-Medical-Image-Analysis

This repository contains several interesting jupyter notebooks which can guide you to understand the basic idea of Medical Image Analysis

# Contents

## [Image Filtering and Segmentation](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Filtering%20and%20Segmentation/Image%20Filtering%20and%20Segmentation.ipynb)
1. Load Images in NIfTI Format
2. Visualization Volumetric Images in Python
3. Interpolation
4. Separable Convolution Filters
5. Non Linear Separable Filter
6. Non Linear Non Separable Filters
7. Recursive Filters
8. Smoothing Filters
9. Gradient Filters
10. Image Contour Extraction
11. Mathematical Morphology
12. Distance Maps
13. Fast Marching

## Image Segmentation
1. [Validation of Segmentation Algorithms](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/Validation%20of%20segmentation%20algorithms.ipynb)
2. [GMM Brain Segmentation](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/GMM%20Brain%20Segmentation.ipynb)
3. [GMM Brain Segmentation with Bias Field Correction](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/GMM%20Brain%20Segmentation%20with%20Bias%20Field%20Correction.ipynb)
4. [K-means Brain Segmentation](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Segmentation/K-means%20Brain%20Segmentation.ipynb)

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