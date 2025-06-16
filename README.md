# Decision-Tree-Classifier

COMPANY:CODTECH IT SOLUTIONS

NAME: KURUVA SHASHI KIRAN

INTERN ID:CT06DM211

DOMAIN: MACHINE LEARNING

DURATION:6 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

This Python file implements a Decision Tree Classifier for the famous Iris dataset, which appears to be part of a CODTECH internship task. Here's a comprehensive breakdown of what the code does:
Purpose and Dataset
The script creates a machine learning model to classify iris flowers into three species (setosa, versicolor, virginica) based on four flower measurements: sepal length, sepal width, petal length, and petal width.
Key Components
Data Preparation:

Loads the built-in Iris dataset from scikit-learn
Converts data to pandas DataFrame for easier manipulation
Checks for missing values (none found in Iris dataset)
Splits data into training (70%) and testing (30%) sets with stratification

Model Configuration:

Uses DecisionTreeClassifier with entropy criterion for splitting
Sets maximum depth to 4 to prevent overfitting
Applies random state for reproducible results

Model Training and Evaluation:

Trains the decision tree on the training data
Makes predictions on the test set
Calculates accuracy score
Generates detailed classification report with precision, recall, and F1-scores
Creates a confusion matrix visualization using seaborn heatmap

Visualization Features:

Decision Tree Visualization: Shows the complete tree structure with splitting conditions, feature names, and class predictions
Confusion Matrix Heatmap: Visual representation of prediction accuracy across classes
Feature Importance Plot: Bar chart showing which features are most important for classification

Analysis Output:

Feature importance rankings to understand which measurements are most decisive
Comprehensive performance metrics for model evaluation

Technical Highlights
The code is well-structured with clear step-by-step comments, uses best practices like stratified splitting to maintain class distribution, and provides multiple visualization methods to understand both the model's decision-making process and its performance. The entropy criterion and depth limitation help create an interpretable model that balances accuracy with simplicity.
