# Introduction-to-Medical-Image-Analysis

This repository contains several interesting jupyter notebooks which can guide you to understand the basic idea of Medical Image Analysis

# Contents

## [Image Filtering](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Image%20Filtering%20and%20Segmentation/Image%20Filtering%20and%20Segmentation.ipynb)
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

## Image Segmentation with Shape Constraint
- segmentation from scribbles:
1. [GrabCut Segmentation for Brain images](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/%20Image%20Segmentation%20with%20Shape%20Constraint/GrabCut%20Segmentation.ipynb)
2. [Random walker Segmentation for Brain images](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/%20Image%20Segmentation%20with%20Shape%20Constraint/Random%20Walk%20Segmentation.ipynb)

- segmentation with contour regularity:
1. [Level Set Segmentation for Brain images](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/%20Image%20Segmentation%20with%20Shape%20Constraint/Level%20Set%20Segmentation.ipynb)
2. [Snakes Segmentation for Brain images](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/%20Image%20Segmentation%20with%20Shape%20Constraint/Snakes%20Segmentation.ipynb)

## [Point Distribution Model](https://github.com/Huiyu-Li/Introduction-to-Medical-Image-Analysis/blob/main/Point%20Distribution%20Model/Point%20Distribution%20Model.ipynb)

# How to use?
Requirments: Python3.5+

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