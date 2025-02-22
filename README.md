# Diabetes Classification Using K-Nearest Neighbors (KNN)

# Introduction
Diabetes is a systemic metabolic disease characterized by high blood glucose levels, which can damage organ functions over time. It occurs when the body is unable to produce or use insulin effectively. There are two main types of diabetes:
1. Type 1 Diabetes: An autoimmune condition where the immune system attacks insulin-producing cells in the pancreas.
2. Type 2 Diabetes: A more common form where the body becomes resistant to insulin or does not produce enough insulin, often linked to lifestyle factors such as obesity and lack of physical activity.

This project aims to classify diabetes using the K-Nearest Neighbors (KNN) algorithm based on medical data. The dataset used in this project is the Pima Indians Diabetes Dataset, sourced from Kaggle. This dataset originates from a study conducted by the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) and focuses on identifying factors contributing to high diabetes prevalence among the Pima Indian population in the U.S.

# Research Methodology

1. Data Collection
- The dataset includes medical records of Pima Indian women aged 21 and above.
- Features include blood sugar levels, BMI, and other relevant health indicators.
- The dataset was obtained from Kaggle and originally collected through medical screenings.

2. Data Preprocessing
To ensure the dataset is clean and ready for analysis, the following preprocessing steps were applied:
- Data Cleaning: Identifying and handling missing or duplicate data.
- Data Balancing: Ensuring an equal number of diabetic and non-diabetic samples (250 each) to prevent model bias.
- Data Splitting: Dividing the dataset into training and testing sets for model evaluation.

3. Model Implementation
- The K-Nearest Neighbors (KNN) algorithm is used for classification.
- The model is trained using labeled data from the dataset.
- Performance metrics such as accuracy, precision, and recall are evaluated.

# Importance of This Study
Understanding diabetes risk factors is crucial for early detection and prevention. By leveraging machine learning and predictive modeling, this project aims to:
1. Identify patterns in diabetes cases.
2. Enhance early detection through predictive analysis.
3. Contribute to global diabetes management strategies.

# How to Use This Project

1. **Clone this repository:**
   ```bash
   git clone https://github.com/azkalltlhn/Diabetes-Classification-KNN-Algorithm.git

2. **Install the required dependencies::**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn

3. Load the Dataset: Ensure the dataset is available in CSV format.
4. Run the Model: Execute the Python script or Jupyter Notebook to train and test the model.
5. Evaluate Results: Analyze the classification report and accuracy metrics.

# Conclusion
This project provides valuable insights into diabetes classification using machine learning. By identifying key risk factors, it supports early diagnosis and prevention efforts, contributing to public health improvement.
