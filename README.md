# Comp551KaggleProject
Quick, Draw! dataset from google, with added noise, classification amongst 30 categories or "empty" image.

For each iPython Notebook, it is sufficient to run each cell sequentially in
order to replicate our results, as detailed in our report on Gradescope. Each
notebook is independent. The data is included in the .zip file, so it does not
need to be added in any way.

# Files:

all/test_images.npy
Test images

all/train_images.npy
Train images

all/train_labels.csv
Train labels

Kaggle_Project_CNN.ipynb
Best performing CNN model contained in this notebook

SVM_Grid_Search.ipynb
Contains SVM on PCA, with a grid search for hyper parameters

Backprop.ipynb
Contains hand-coded neural network back-propogation class

SIFT_SVM.ipynb
SIFT features in SVM

SVM.ipynb
Simple SVM on the data

# Packages required:
Keras
OpenCV 3+
sklearn
pandas
numpy
matplotlib
multiprocessing
datetime
io
os
