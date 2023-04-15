# Honey-bee-vs-bumble-bee-classifier
This project is a supervised learning model that aims to distinguish between honey bees and bumble bees. The model is built using a dataset of images of honey bees and bumble bees, each labeled with its corresponding genus. The dataset is loaded into a pandas dataframe and preprocessed to extract features for each image. The features include both color and texture features, which are extracted using the HOG (Histogram of Oriented Gradients) technique.

The extracted features are then used to train a Support Vector Machine (SVM) classifier. The dataset is split into training and testing sets using the train_test_split function from sklearn's model_selection module. The SVM classifier is trained on the training set and evaluated on the testing set using the accuracy_score function from sklearn's metrics module.

The performance of the classifier is further evaluated using the ROC curve and AUC (Area Under the Curve) metrics. The ROC curve is a plot of the true positive rate (TPR) against the false positive rate (FPR) for different classification thresholds. The AUC metric represents the area under the ROC curve and provides a single value to evaluate the performance of the classifier.

Overall, this project demonstrates the use of supervised learning techniques for image classification tasks, with a specific application to distinguishing between honey bees and bumble bees. The model achieves high accuracy and demonstrates good performance based on the ROC curve and AUC metrics.
