# CODSOFT_3
The concept behind this prediction involves supervised machine learning for classification. Here's a breakdown of the process used to classify the Iris species:

1. Dataset and Features
The Iris dataset contains measurements of three Iris flower species: setosa, versicolor, and virginica. Each flower is described by four features:

Sepal length
Sepal width
Petal length
Petal width
The species is the target variable (label) to be predicted.

2. Goal
The goal is to train a machine learning model that can:

Learn patterns from the measurements.
Accurately classify a flower into its correct species based on the four measurements.
3. Model Selection: Random Forest
I used a Random Forest Classifier, which is an ensemble learning method. Here's how it works:

Decision Trees: The model builds multiple decision trees using subsets of the data.
Voting: Each tree predicts a species, and the majority vote determines the final prediction.
Randomness: By introducing randomness in both data selection and feature choice, the model reduces overfitting and improves accuracy.
4. Training Process
Splitting Data: The dataset was split into training (80%) and testing (20%) datasets.
Training: The model learns from the training data by finding patterns between the features and species labels.
Testing: The model's performance is evaluated using the test data to measure accuracy.
5. Prediction and Accuracy
The trained model predicts the species based on the measurements.
The model achieved 100% accuracy in this case, meaning it classified all test samples correctly.
6. Why It Works Well for Iris Dataset?
The Iris dataset is relatively small and well-separated, making it ideal for beginner classification tasks.
Each species has distinct measurements, so the model can easily identify patterns.
