# Single_Layer_Perceptron
Implementation of Single Perceptron for Titanic and Iris datasets with manual training, evaluation, and hyperparameter tuning using GridSearchCV.


🧠 Single Perceptron - Binary Classification Projects
This repository contains three implementations of a single-layer perceptron used for binary classification problems on different datasets, including Titanic and Iris, along with a custom perceptron from scratch for a simple classification task.

📌 Objectives
Implement a Single Perceptron from scratch in Python.

Train and evaluate the model on Titanic and Iris datasets.

Use GridSearchCV for hyperparameter tuning on the Iris dataset.

Evaluate using accuracy, precision, and recall.

📁 Projects Included
🔷 3a. Single Perceptron for Titanic Dataset
Preprocessed Titanic dataset (binary classification: survived or not).

Manually implemented perceptron.

Trained and tested model with metric evaluation.

🔷 3b. Custom Binary Classification Perceptron
Python script with:

Weight & bias initialization

Weighted sum & step activation function

Weight update rule

Tested on a basic linearly separable problem (e.g., OR or AND logic).

Model evaluation with accuracy, precision, and recall.

🔷 3c. Perceptron on Iris Dataset + GridSearchCV
Used Perceptron() model from sklearn.linear_model.

Applied GridSearchCV to tune hyperparameters like:

Learning rate (eta0)

Number of iterations (max_iter)

Penalty (l2, l1, etc.)

Evaluated classification performance on binary version of Iris dataset.

📊 Evaluation Metrics
Accuracy

Precision

Recall

Confusion Matrix (optional visuals)

💻 Tech Stack
Python

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn

🚀 Future Enhancements
Add multi-layer perceptron (MLP) with backpropagation

Use cross-validation for better evaluation

Extend to multiclass classification
