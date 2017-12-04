# Digit_fashion_MNIST
Digit and fashion MNIST dataset using scikit learn library. 

Author: Zolzaya Khurelbaatar 2017/12/04

Here, I've done my homework assignment using Digit MNIST dataset and Fashion MNIST dataset. 

Digit MNIST: training set: 60,000 testing set: 10,000
Fashion MNIST: training set: 60,000 testing set: 10,000 

I used 3 classifier: Naive bayes, Support Vector Machine(SVM) and Multi-Layer Perceptron (MLP)
And I used scikit learn which is machine learning library. 

Workflow of Digit_MNIST:
1. Import .png raw image dataset (there have another format MNIST data such .csv)
2. Normalized (I used a mean normalizer that means data mean 0, standard deviation 1,
mathematic equation is  {X-X(mean)/std} you can found detail from wikipedia)
3. I compute covariance matrix. You can used formula or numpy library np.cov function
4. I found eigenvectors and eigenvalues from covariance matrix. 
5. Dimensionally reduction, I used PCA with 400 components. 
6. Classification task. I used 3 classifier with default parameters. For MLP, important parameter 1 layer and 100 neurons
7. Classification report each of the classifier and compared each other. 

Workflow of Fashion_MNIST:
Over all the process is a like above workflow. Only changed training and testing datasets. 

Thank you :). 
 



