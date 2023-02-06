# Facial Recognition
Recognize faces using Machine Learning algorithms in Python.

## Libraries Used
1. OpenCV for reading the image files
2. NumPy for mathematical computation
3. Matplotlib for plotting images
4. scikit-learn for ready-made training and testing different Machine Learning models.

## Algorithm
1. We extract the zip files and read the 400 images files using OpenCV.
2. PCA is applied to reduce the large number of dimensions, which both
speeds up training and helps the models focus on the important bits.
3. Two train-test split strategies are used:
    1. even-odd row split
    2. 70-30% split
4. Different models are used for training:
    1. KNN
    2. SVM with three different kernels
    3. Gauusian Naive Bayes