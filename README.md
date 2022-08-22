# DigitClassifier
This repository is a collection of machine learning exercises, largely based on 'Hands-On Machine Learning with Scikit-Learn, Keras &amp; TensorFlow'
Translation.ipynb finds improved accuracy by augmenting the data with translated images.
SVM Tuning.ipynb tests GridSearchCV, RandomizedSearchCV, and HalvingGridSearchCV for searching for the optimal hyperparameters of an SVC model.
MLP.ipynb trains a small MLP written in Keras. Cross validation is performed in two stages: one rough search to narrow the search space, and a second more specific search to pick the final hyperparameters.
Ensemble.ipynb combines KNeighborsClassifier, RandomForestClassifier, ExtraTreesClassifier, and SVC models as a LogisticRegression blender and as a VotingClassifier. The voting classifer achieves the highest accuracy of 0.9891.
