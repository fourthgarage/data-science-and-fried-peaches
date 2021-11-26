# Diabetes prediction
In this project i loaded Pima Indians Diabetes Database from Kaggle, visualized and analyzed the data, plotted a pairwise dependencies. I chose AUC as a quality metric and tried to choose a suitable classification model. Considered metric methods, logistic regression and support vector machine. PFM and logistic regression algorythms - my native realization. Parzen, Random forest and svm - sklearn realization.
Results:
* Parzen window model: AUC=0.76
* PFM: AUC=0.82
* Random forest: AUC=0.83
* Logistic regression: AUC=0.84
* SVM classifier: AUC=0.87
The best result showed SVM classifier with SVM features. I fitted SVC, then added distances to support vectors as new features and fitted SVC again
