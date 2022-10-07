# Face Recognition
The project uses Principal Component Analysis(PCA) to find the eigenfaces of a set of images and then uses the eigenfaces to recognize faces in a test set of images.   

## Skree Plot
We obseve ~95% of the variance in the data is explained by the first 60 eigenfaces.
Display image:
![Skree Plot](skree.png)

## Classifiers
The classifiers used are:
- K-Nearest Neighbors
- Support Vector Machine
- Random Forest
- Logistic Regression
- Decision Tree

## Results
The accuracy results are as follows:
- K-Nearest Neighbors: 77.5 %
- Support Vector Machine(RBF): 7.5 % 
- Decision Tree: 50 %
- Random Forest: 75 %
- Random Forest(PCA): 85 %
- Logistic Regression: 85 %

