# Gaussian-Naive-Bayes-Classifier
Experimenting with Gaussian Naive Bayes for classification tasks using Scikit-learn

1.Project Overview: This project involves experimenting with the Gaussian Naive Bayes classifier to predict class labels based on feature probabilities. The project uses the provided grading dataset (Data-NB.xlsx) and the Iris dataset to evaluate the model's performance.

2.Data Preprocessing: The grading dataset includes nominal variables such as Gender, Attendance, and Grade, which are encoded appropriately. The Iris dataset is also used, with features including Sepal length, Sepal width, Petal length, Petal width, and Species.

3.Model Training: The datasets are split into training and testing subsets (using an 80-20 or 70-30 ratio). A Gaussian Naive Bayes classifier is trained on the training data, and its performance is assessed on the test data.

4.Performance Evaluation: The model's performance is evaluated using accuracy and the confusion matrix for the grading dataset. For the Iris dataset, a classification report is generated, showing metrics such as precision, recall, and F1-score.

5.Comparison with Other Classifiers: The performance of the Gaussian Naive Bayes classifier is compared with that of Random Forest and Gradient Boosted Trees (from a previous assignment) on the same datasets. The comparison includes an analysis of the reasons behind any observed performance differences.

6.Correlation Matrix Visualization: For both datasets, the correlation matrix is visualized to check and verify the assumptions of the Naive Bayes algorithm, which assumes feature independence.

7.Implementation and Results: The implementation includes code snippets for importing required libraries, encoding nominal variables, training the classifier, and evaluating its performance. The results, including accuracy, confusion matrix, and classification report, are documented.
