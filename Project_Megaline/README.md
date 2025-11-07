# Applying Machine Learning to Megaline Phone Plans

Project Description:
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. 

You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model.  

Develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset. 

Project Instructions:
Strengths

1. Open each file and Inspect its Data Integrity.
2. Split the source data into a training set, a validation set, and a test set with a random state for reproducibility.
3. Investigate the quality of different models (DecisionTree, RandomForest, and LogisticRegression) by changing hyperparameters. Briefly describe the findings of the study.
4. Check the quality of the model using the test set. Evaluate based on a 0.75 threshold.
5. Additional task: sanity check the model using a DummyClassifier.

Hints:
- Cast calls and messages to integers (they’re counts) rather than floats.
- Experiment with class_weight='balanced' in your RandomForest to boost recall on the minority (Ultra) class.
- Derive new features (e.g. data per minute, messages per call) to provide more predictive signal.
- Examine feature_importances_ to understand which behaviors most influence the model’s recommendations.
