# Breast Cancer Prediction Using Machine Learning

This project demonstrates the use of machine learning techniques to classify tumors as **benign** or **malignant** based on the **Wisconsin Breast Cancer Dataset**. The workflow includes data visualization, preprocessing, dimensionality reduction using **Principal Component Analysis (PCA)**, and training multiple machine learning models.

## Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features**:
  - 30 numeric features derived from cell nuclei images (mean, standard error, and worst-case values).
  - Target: `Diagnosis` (0 = Benign, 1 = Malignant).
- **Instances**: 569 samples.

## Project Structure
The project is divided into three main steps, each implemented in a Jupyter Notebook:

1. **Data Visualization (`1DataVisualisation.ipynb`)**:
2. **Data Preprocessing (`2DataPreprocessing.ipynb`)**:
3. **Model Building (`3ModelBuilding.ipynb`)**:

## Models Used
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**

---

## Evaluation Metrics
The following metrics are used to evaluate model performance:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**
