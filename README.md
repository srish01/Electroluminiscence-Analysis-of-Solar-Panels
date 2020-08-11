# EL-Analysis

This repository contains 2 jupyter notebooks that deals with Electroluminescence Image Analysis of a PV module under Accelerated Lifecycle Testing.

## 1. EL Analysis FINAL 
In this jupyter notebook, REC monthly images are first preprocessed and then fed into Autoencoder system. Background subtraction, median filtering, barrel distortion removal are done in preprocessing phase. Autoencoder is further used to capture most essential information from the images.

## 2. EL Statistics
This notebook contains histogram based analysis of monthly REC panel images. For a high level perspective, pixel intensities are divided in 15 bins. Broadly, pixels are also divided into 3 categories black, grey and white to estimate the pixel numbers in each categories on monthly basis. 
