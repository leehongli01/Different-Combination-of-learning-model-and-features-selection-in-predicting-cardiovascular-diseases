# Different-Combination-of-learning-model-and-features-selection-in-predicting-cardiovascular-diseases
This is just a exploration of learning models and features selection in predicting outcome based on the dataset of cardiovascular patients from Kaggle. Do not use it for any medical field.
# Result
![image](https://github.com/user-attachments/assets/17e4c2a0-45b6-443c-ac33-fd0876c89f86)
# flow chart
![image](https://github.com/user-attachments/assets/4b7b8ef0-28ab-43c8-b447-2a89f191fb2a)
# Training models
<b>Naive Bayes (Gaussian)</b>: A probabilistic classifier based on Bayes' theorem, 
suitable for binary classification tasks. It assumes independence between features.

<b>AdaBoost Classifier</b>: An ensemble technique that combines multiple weak 
classifiers to form a strong classifier by focusing on incorrectly classified instances. 
It iteratively adjusts the weights of these instances to improve performance.  

<b>Logistic Regression</b>: A statistical model that uses a logistic function to model a 
binary dependent variable. It predicts the probability of the presence of the disease.  

<b>Decision Tree Classifier</b>: A non-parametric model that splits the data into subsets 
based on feature values, creating a tree structure that represents the decisions and 
their possible outcomes. It is trained using PCA-transformed features.  
 
<b>Extra Trees Classifier</b>: Like Random Forest, this ensemble method constructs 
multiple decision trees but differs in that it selects cut points randomly for each 
candidate feature. It is also trained using RFE-selected features.  

<b>Recurrent Neural Network (RNN)<b/>: which is built to capture temporal 
dependencies in the dataset. The RNN model consists of a SimpleRNN layer with 
ReLU activation, followed by a Dense layer with a sigmoid activation function to 
output the probability of the binary class. The model is compiled using the Adam 
optimizer and binary cross-entropy loss function and trained over multiple epochs 
with a validation split to monitor performance.  
