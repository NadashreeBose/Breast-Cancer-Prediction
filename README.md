# Breast Cancer Diagnosis Prediction

## Objective:
The objective of this project is to develop a predictive model using machine learning algorithms to accurately classify breast cancer cases as malignant or benign based on a comprehensive set of input features. The goal is to enhance early detection capabilities, improve diagnostic accuracy, and contribute to the development of an efficient and reliable tool for breast cancer diagnosis, ultimately aiding healthcare professionals in making informed decisions and improving patient outcomes.

## Dataset:
The Breast Cancer Wisconsin dataset contains 569 samples of malignant and benign tumor cells. It consists of 30 real-value features computed from digitized images of cell nuclei. The features represent characteristics such as size, shape, and texture, which are important for diagnosing breast cancer.

### Attribute Information:
- **ID:** Unique identifier for each sample.
- **Diagnosis:** Target variable indicating whether a sample is benign (B) or malignant (M).
- **Mean, Standard Error (SE), and Worst features:** Characteristics of cell nuclei, such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

## Approach:
- **Data Analysis:** Exploratory data analysis (EDA) was performed to understand the structure and characteristics of the dataset. This included checking for null and duplicate values, visualizing the distribution of features, and analyzing correlations between features.
- **Preprocessing:** Data preprocessing steps such as label encoding for categorical variables, splitting data into training and testing sets, and feature scaling were performed to prepare the data for modeling.
- **Modeling:** Several machine learning algorithms including Logistic Regression, K Nearest Neighbors, Support Vector Machines (Linear and RBF kernels), Gaussian Naive Bayes, Decision Tree, and Random Forest were trained on the dataset.
- **Evaluation:** Each model was evaluated based on metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and classification reports were generated to assess the performance of the models.
- **Model Selection:** Based on evaluation results, Random Forest emerged as the best-performing model for this dataset, followed by SVC with RBF kernel and SVC with Linear kernel.

## Conclusion:
The trained Random Forest Classifier provides an effective solution for breast cancer diagnosis prediction. This project demonstrates the potential of machine learning algorithms in improving early detection and diagnostic accuracy in healthcare.
