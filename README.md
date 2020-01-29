# Image-Classification

## Dataset Description
* Dataset used : Cifar10
* The dataset consists of 50000 train and 10000 test color images of size 32 X 32. The images are divided into 10 categories as follows:
1. airplane										
2. automobile										
3. bird										
4. cat										
5. deer										
6. dog										
7. frog										
8. horse										
9. ship										
10. truck

## Approach
* Imported the dataset
* Reshaping of images.
* SVM : Applied PCA and SVM
* CNN : Built a CNN model using Keras (Refer for more information : https://arxiv.org/pdf/1611.04905)

## Results
* Accuracy using SVM : 55.35%
* Accuracy using CNN : 85.57%
