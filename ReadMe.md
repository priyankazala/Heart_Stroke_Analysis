```markdown
# Heart Stroke Analysis

This project aims to analyze the risk of stroke occurrence in patients using machine learning classification models. Stroke is a leading cause of death and disability worldwide, and early detection and prevention are crucial in improving patient outcomes.

### Introduction

Stroke is a severe medical condition that can result in death or permanent disability. According to the World Health Organization (WHO), it is the second leading cause of death globally, accounting for approximately 11% of total deaths. This project focuses on analyzing various factors associated with strokes to develop classification models for predicting the occurrence of strokes.

### Problem Statement

The major challenge in heart disease detection is its early detection. Existing instruments for predicting heart disease may be expensive or not efficient enough to accurately calculate the risk of heart disease in individuals. This project aims to leverage machine learning algorithms to analyze a dataset containing patient information and identify hidden patterns that can assist in health diagnosis.

The dataset used in this project consists of 12 columns, including 10 input variables describing patient characteristics and one output variable ("stroke") indicating the occurrence of a stroke (0 - no stroke, 1 - stroke). The objective is to develop classification models to predict stroke occurrence based on these variables.

### Pre-processing

To address the issue of class imbalance, where the majority class (no stroke) significantly outweighs the minority class (stroke), we utilized the Synthetic Minority Oversampling Technique (SMOTE) for oversampling the minority class. This approach helps generate synthetic samples to balance the class distribution without losing valuable information.

### Classification Models

In this project, we created and evaluated eight different classification models to predict stroke occurrence in patients:

1. Logistic Regression (LR)
2. Gaussian Naive Bayes (GNB)
3. Decision Tree (DT)
4. LightGBM (LGBM)
5. K-Nearest Neighbor (KNN)
6. XGBoost (XGB)
7. Random Forest (RF)
8. Support Vector Machine (SVM)

Each model was trained and tested on the dataset, and their performance metrics, including accuracy, were evaluated.

### Results

After evaluating the performance of all the models, we found that the accuracy of predicting stroke occurrence ranged from 75% to 98%, depending on the specific combination of features used. A thorough study of patient characteristics in the health record, including feature correlation analysis and step-by-step analysis, helped determine the best feature set for achieving higher accuracy.

### Repository Structure

- `data`: Contains the dataset used for analysis.
- `notebooks`: Jupyter notebooks containing the code for data preprocessing, model training, and evaluation.
- `models`: Saved trained models.
- `README.md`: This file providing an overview of the project.

### Instructions

1. Clone this repository to your local machine.
2. Install the required dependencies and libraries.
3. Open the Jupyter notebooks in the `notebooks` directory.
4. Follow the instructions in the notebooks to preprocess the data, train the models, and evaluate their performance.
5. Experiment with different feature sets and models to explore their impact on prediction accuracy.

### Running in Google Colab

To run this project in Google Colab:

1. Create a new notebook in Google Colab.
2. Upload the contents of this repository to your Google Drive.
3. Mount your Google Drive in the Colab notebook.
4. Navigate to the `notebooks` directory and open the desired notebook.
5. You can access the dataset from the `data` directory in your Google Drive.

### Conclusion

In conclusion, this project demonstrated the application of machine learning algorithms in predicting stroke occurrence based on patient characteristics. By analyzing a comprehensive set of features and utilizing various classification models, we achieved promising results in identifying stroke risks. The findings from this study can aid in early detection and prevention of strokes, ultimately improving patient outcomes and reducing mortality rates.

For more details, please refer to the individual Jupyter notebooks and their associated documentation within the project repository.
```