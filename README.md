# Dataset
The dataset used  is a land-use Scene dataset, which is obtained through Landsat 
satellite. The dataset contains 21 classes, namely agricultural, airplane, baseball diamond, beach 
buildings, chaparral, dense residential, forest, freeway, golf course, harbor, intersection, medium 
residential, mobile home park, overpass, parking lot, river, runway, sparse residential, storage 
tanks, tennis courts. only six classes is used , the classes are agriculture,
baseball diamond, beach, buildings, forest, parking lot
The training datasets contain 350 images for each class and the testing dataset contains 50 images classes.
Dataset is downloaded from Kaggle.
Dataset Yi Yang and Shawn Newsam, "Bag-Of-Visual-Words and Spatial Extensions for Land-Use Classification," ACM
SIGSPATIAL International Conference on Advances in Geographic Information Systems (ACM
GIS), 2010
## The aim of this project is used to implement SVM and KNN for Multi class classification of Satellite Images
# Support Vector Machine
Support vector machine is a supervised machine learning algorithm that can be used for both 
regression and classification problems, it is a kernel-based algorithm, SVM can be linear and 
nonlinear, when the data points can be separate using a straight line is called a linear well as when 
the data points cannot be separate using a straight line is called Non-linear SVM. SVM is a binary
classifier, for multiclass it uses the concept of one vs one or one vs rest classifier.
The concept of  SVM is used to create a hyperplane that maximizes the margin between the class
* The equation of a hyperplane is given as below: -
       WTX+b=0
# K-Nearest Neighbors(KNN)
KNN (k-nearest Neighbors) is a supervised machine learning algorithm, which required labeled 
/target data along with the features, to produce correct output when the unlabeled data is given. 
KNN can be used to solve both classification and regression problems.
KNN is a non-parametric learning algorithm.KNN is based on distance metric.Some distance metrics used in KNN are Euclidean distance, Manhattan distance.
KNN stores the training data and does not learn much at the training phase, all the training 
data are used while doing the classification

# Accuracy 
* SVM model porvide an accuracy of 62 percent.
* KNN model provide an accuracy of 47 percent
