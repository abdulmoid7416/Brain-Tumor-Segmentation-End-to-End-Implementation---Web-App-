# Brain-Tumor-Segmentation-End-to-End-Implementation---Web-App-

This is a complete End to End Brain Tumor Segmentation project. Here we developed a tumor segmentation Web Application based on a modified version of the original U-NET architecture (from the paper "U-Net: Convolutional Networks for Biomedical Image Segmentation") using PyTorch framework. 

Notable modifications to original U-NET are:
- usage of "same" padding rather than "no" padding,
- usage of batch normalisation
- a different input image size



# Training Data
The training data can be acquired from kaggle (Link: "U-Net: Convolutional Networks for Biomedical Image Segmentation" )

This dataset contains brain MR images together with manual FLAIR abnormality segmentation masks.
The images were obtained from The Cancer Imaging Archive (TCIA).
They correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.



# USAGE:

The repository contains two folders, namely - Training module, and the Front-End.
- The Training module contains an ipynb file, through which the model is trained.
- The Front End folder contains two folders, i.e. static and templates, where static contains the css and js files (each contained in its specific folders), and templates holds the html files. In addition, it also contains a python file called app.py, which is used to enable web application in the server.
