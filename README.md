# AIML-INTERNSHIP-TASK-5
AIML Internship Task 5 Solution
Task 5: Decision Trees and Random Forests
Objective
The objective of this task is to learn and implement tree-based machine learning models for classification. The task includes training a Decision Tree Classifier, analyzing overfitting, implementing a Random Forest Classifier, interpreting feature importance, and evaluating model performance using cross-validation.
Tools and Libraries Used
Python
Pandas
Matplotlib
Scikit-learn
Dataset
Breast Cancer Dataset from Scikit-learn
Steps Performed
1. Data Loading
Loaded the Breast Cancer dataset using Scikit-learn.
2. Data Splitting
Split the dataset into training and testing sets using an 80:20 ratio.
3. Decision Tree Classifier
Trained a Decision Tree model.
Evaluated its accuracy.
Visualized the decision tree structure.
4. Overfitting Analysis
Limited tree depth using max_depth=3.
Compared performance with the original model.
5. Random Forest Classifier
Trained a Random Forest model with 100 trees.
Evaluated accuracy and compared with Decision Tree results.
6. Feature Importance
Extracted feature importance values from the Random Forest model.
Visualized the top important features.
7. Cross Validation
Performed 5-fold cross-validation.
Calculated the average validation score.
Results
Model
Accuracy
Decision Tree
~93%
Decision Tree (max_depth=3)
~95%
Random Forest
~97%
Average Cross Validation Score: ~95%
Key Learnings
Decision Trees are simple and easy to interpret.
Deep trees may overfit the training data.
Random Forest reduces overfitting by combining multiple decision trees.
Feature importance helps identify the most influential features.
Cross-validation provides a more reliable estimate of model performance.
Conclusion
Random Forest achieved higher accuracy and better generalization compared to a single Decision Tree. Ensemble methods such as Random Forest are effective for improving prediction performance and reducing overfitting.
