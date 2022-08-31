# BME548L Final Project - Skin Cancer Classification with CNN and Physical Layers

## Abstract 
Skin cancer is the most prevalent type of cancer, and can be deadly if left untreated. In recent years, deep learning approaches have been implemented to automate skin cancer detection and classification using dermoscopic images, however, the process still requires human intervention to capture accurate and high quality dermoscopic images. This study aims to automate the physical components of the dermoscopy  to see if optimizing for these components will increase model performance results. After optimizing for the color channels, illumination patterns, and lens blur with a convolutional neural network (CNN), the results suggest training the lens blur with the CNN improves classification performance, from 0.70 AUC and 70% accuracy to 0.73 AUC and 74% accuracy. This study can be extended to a larger aim of creating inexpensive, portable and fully automated imaging systems to detect skin cancer.

This repo contains: 

* FINAL_EDA.ipynb - Exploratory data analysis of ISIC Melanoma metadata and images
* FINAL ML Imaging Models.ipynb - Models and findings

## Built With

* [Google Colab](https://colab.research.google.com/)

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Tensor Flow](https://www.tensorflow.org/)
- [Kears](https://keras.io/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

### Data

The dataset used for this project was a subset of the International Skin Imaging Collaboration Challenge (ISIC 2020), which contains 33,126 dermoscopic images of skin lesions and their respective ground truth labels of being benign or malignant, from over 2,000 patients found on the [ISIC 2020 Challenge Dataset](https://challenge2020.isic-archive.com/).

## Contact
Michelle Li - michelle.li851@duke.edu or michelleli1999@berkeley.edu
