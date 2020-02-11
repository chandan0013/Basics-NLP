# Basics-NLP
General Python based text-document classification..
Performed modeling, feature extraction and feature selection for classification task.
We applied LSI to the TF-IDF matrix to map each document to a 50-dimensional vector. 

First task is to design binary classifier.
Used Linear Support Vector Machines (SVM), Gaussian Naive Bayes, and Logistic Regression classification algorithms to classify the documents in the dataset to two different categories, namely Computer technology and Recreational activity.

Second task is Multi-class classifier.
In this part of the project, we used Support Vector Machines (SVM), and Gaussian Naive Bayes classification algorithms to classify the documents in the dataset to four different categories, namely, comp.sys.ibm.pc.hardware, comp.sys.mac.hardware, misc.forsale, and soc.religion.christian. Gaussian naive bayes classification algorithm performs multiclass classification inherently, but for SVM the Binary classification techniques need to be extended. We performed a one versus one (OVO) classification on all 6 pairs of classes. We also performed a one versus rest (OVR) classification technique.
