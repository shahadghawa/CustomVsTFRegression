This repository compares a custom implementation of linear regression using gradient descent with a TensorFlow-based implementation. The goal is to evaluate the efficiency and accuracy of manually tuning weights and biases in contrast to automated optimizers such as Adam.

The comparison covers the following key steps:

1.	Data Loading and Preprocessing:
Using the California Housing Dataset, the data is loaded, preprocessed, and normalized as necessary to prepare it for model training.
2.	Custom Linear Regression Implementation:
	•	Implements forward and backward passes manually to compute the loss and gradients.
	•	Uses Gradient Descent for weight and bias updates, focusing on how manual tuning of these parameters can impact performance.
	•	The model is iteratively updated based on the calculated gradients, optimizing towards minimizing the Mean Squared Error (MSE).
	3.	TensorFlow-Based Linear Regression:
	•	A similar linear regression model is built using the Keras API in TensorFlow.
	•	The model utilizes the Adam Optimizer to automatically handle the parameter updates during the training process, serving as a benchmark for comparison.
	4.	Evaluation and Comparison:
	•	Both models are evaluated based on Mean Squared Error (MSE).
	•	Visualizations are included to compare the predictions of both models with the actual data.
	•	The results highlight the trade-offs between manual parameter tuning and the use of an automated optimizer like Adam, with a focus on accuracy and computational efficiency.
