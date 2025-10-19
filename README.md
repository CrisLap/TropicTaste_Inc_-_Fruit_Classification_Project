# TropicTaste_Inc_-_Fruit_Classification_Project
Classification of exotic fruits with KNN

**TropicTaste Inc.**, a leader in exotic fruit distribution, aims to improve efficiency and accuracy in the fruit classification process. The goal is to develop a **machine learning model** capable of predicting the type of fruit based on numerical features.

The current exotic fruit classification process is manual and error-prone, making it inefficient and resource-intensive. An automated and precise system is crucial to optimize business operations and maintain high-quality standards.

By implementing an automated classification model, TropicTaste Inc. will be able to:

- **Improve Operational Efficiency:** Automating classification will reduce the time and resources required, increasing productivity.  
- **Reduce Human Errors:** A machine learning model will minimize classification mistakes, ensuring greater accuracy.  
- **Optimize Inventory Management:** Accurate classification will enable better inventory control, ensuring optimal storage conditions for each fruit type.  
- **Increase Customer Satisfaction:** Correct identification and classification of fruits will help maintain high quality standards, improving customer satisfaction.  

---

## Project Details

1. **Dataset:** A dataset containing various numerical features of different exotic fruits.  
2. **Algorithm:** Implementation of the **K-Nearest Neighbors (KNN)** algorithm for classification.  
3. **Output:** The model must correctly predict the type of fruit based on the provided data.  

---

## Project Requirements

### 1. Dataset Preparation
- Load and preprocess the exotic fruit data.  
- Handle missing values, normalize, and scale the data.  

### 2. KNN Model Implementation
- Develop and train the KNN model.  
- Optimize parameters to improve predictive accuracy.  

### 3. Performance Evaluation
- Use cross-validation techniques to evaluate the model's generalization ability.  
- Calculate performance metrics such as accuracy and classification error.  

### 4. Results Visualization
- Create charts to visualize and compare model performance.  
- Analyze and interpret results to identify potential areas for improvement.  

---

## Dataset Variables

The dataset is downloadable here: [fruits.csv](https://proai-datasets.s3.eu-west-3.amazonaws.com/fruits.csv)  

It contains the following variables:

1. **Fruit:** Type of fruit. This is the target variable we aim to predict.  
2. **Weight (g):** Weight of the fruit in grams. Continuous variable.  
3. **Average Diameter (mm):** Average diameter of the fruit in millimeters. Continuous variable.  
4. **Average Length (mm):** Average length of the fruit in millimeters. Continuous variable.  
5. **Peel Hardness (1-10):** Hardness of the fruit peel on a scale from 1 to 10. Continuous variable.  
6. **Sweetness (1-10):** Sweetness of the fruit on a scale from 1 to 10. Continuous variable.  

---

**Notes:**  
- Perform a thorough **exploratory data analysis (EDA)** before modeling.  
- Apply appropriate preprocessing techniques.  
- Measure model performance using metrics that best reflect predictive quality.  
- Accompany each analysis step with appropriate **visualizations** and provide clear comments, extracting useful insights from the data.

## Quick start
- Create and activate a Python environment (recommended Python 3.9+).
- Install dependencies: pip install -r requirements.txt
