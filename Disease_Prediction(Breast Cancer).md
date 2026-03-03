Disease Prediction (Breast Cancer)
File: disease_prediction.ipynb

Objective
To predict whether a tumor is malignant or benign based on medical features derived from breast cancer diagnostic data.

Dataset Overview
The project uses the Scikit-learn Breast Cancer dataset.

	1. Total Samples: 569 patients.

	2. Features: 30 medical measurements (e.g., mean radius, texture, perimeter, area, smoothness, etc.).

	3. Target: Binary classification (Malignant vs. Benign).

Machine Learning Models
The following models were evaluated:

	1. Logistic Regression: Achieved 95.6% accuracy.

	2. Random Forest Classifier: Achieved 96.4% accuracy.

Key Results
	1. Top Performer: Random Forest performed slightly better than Logistic Regression.

	2. Conclusion: The Random Forest model was preferred not only for its higher accuracy but also for its ability to reduce false negatives, which is critical in medical scenarios to avoid missing actual cancer cases.