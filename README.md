# Acurracy-Model


This code demonstrates how to use a Decision Tree Classifier model to predict music genres based on features.

**Libraries**
The following libraries are imported:

pandas: Used to read and manipulate the dataset
DecisionTreeClassifier from sklearn.tree: Used to create the decision tree model
train_test_split from sklearn.model_selection: Used to split the dataset into training and testing sets
accuracy_score from sklearn.metrics: Used to evaluate the accuracy of the model predictions
**Data**
The music data is imported from a CSV file using the pd.read_csv function.

**Inputs and Outputs**
The input features are all columns in the dataset except for the 'genre' column, which is the output target.

**Training and Testing**
The dataset is split into training and testing sets using the train_test_split function. The testing set size is set to 20% of the total dataset.

**Model**
The model is created using the DecisionTreeClassifier function from sklearn.tree and trained on the training data using the fit method.

**Evaluation**
The accuracy of the model is evaluated using the accuracy_score function from sklearn.metrics by comparing the predicted genre labels on the testing set with the actual genre labels.

**Output**
The code outputs the accuracy score of the model on the testing set
