# Email Classification using Support Vector Machines (SVC)
This project implements a machine learning pipeline to classify emails into various customer service categories using text data. It leverages Support Vector Classifiers (SVC) along with TF-IDF vectorization and SMOTE to address class imbalance. Additionally, Top-2 accuracy is introduced to improve performance interpretation in multi-class classification.

# Project Objectives
Classify incoming customer emails into predefined support categories.

Handle imbalanced classes using SMOTE.

Improve accuracy interpretation using Top-2 Accuracy.

Visualize category-specific performance gains.



# Features
TF-IDF Vectorization: Converts email text into numerical features.

Support Vector Classifier: Core model used for classification.

SMOTE: Addresses class imbalance by oversampling minority classes.

Top-2 Accuracy: Custom metric to assess if the correct class is among the top 2 predictions.

Visualization: Identifies which categories benefit most from Top-2 logic.

