# README: Kaggle Survey - Salary Classification

## Overview
This project involves analyzing and classifying yearly salary buckets based on survey data from the **2019 Kaggle ML & DS Survey Challenge**. The task focuses on using machine learning classification techniques, particularly **Logistic Regression**, to predict the salary bucket of survey respondents based on their responses.

## Dataset
- **Kaggle_Salary.csv**: This dataset contains survey results, including encoded salary buckets (`Q10_buckets`), and label-encoded salary categories (`Q10_Encoded`), derived from the original survey.
- The dataset includes:
  - 19,717 participants.
  - 246 columns, representing the survey questions.

## Project Components

### 1. Data Cleaning
The dataset contains missing values and categorical data. The cleaning process involves:
- Handling missing values based on certain assumptions.
- Converting categorical data into numerical data using **label encoding**.
- Justification of data cleaning methods and their impact on model performance.

### 2. Exploratory Data Analysis and Feature Selection
Key insights were generated through data visualization techniques to understand the importance of various features in predicting the salary bucket. Methods used include:
- **Correlation analysis** to identify relationships between variables.
- **Feature engineering** to create new features and optimize model performance.
- **Dimensionality reduction** (e.g., PCA) and **feature selection** methods were explored to reduce the complexity of the dataset.

### 3. Model Implementation
A **Logistic Regression** classifier was implemented using **10-fold cross-validation** to assess the performance. Key metrics include:
- **Accuracy** comparison across folds.
- Calculation of the **average accuracy** and its **variance** to understand the model's performance.

### 4. Model Tuning
The model's performance was improved through **hyperparameter tuning** using **Grid Search**. Metrics such as **accuracy**, **precision**, **recall**, and **F1-score** were used to compare the models and choose the best-performing one.

### 5. Testing & Discussion
The final model was applied to the test set, with discussions on:
- **Overfitting vs. Underfitting** and how to balance the two.
- Model performance on the **training** vs **testing** sets.
- Potential improvements for the model and future work.

## Key Tools & Libraries
- **Python 3.x**
- **Pandas**, **Numpy**, **Matplotlib**, **Scikit-learn**
- **Logistic Regression** for classification.
- **Grid Search** for hyperparameter tuning.

## How to Run the Project
1. Install the necessary Python libraries (e.g., `Pandas`, `Scikit-learn`).
2. Open `code.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook sequentially to execute the analysis and view the results.

## Results
The project concludes with a trained and tuned model that predicts salary buckets based on survey responses with significant accuracy. The discussion includes recommendations for further improvements and insights into how the model's results can inform decision-making for salary predictions.

## Submission
- Jupyter Notebook file: `lastname_studentnumber_assignment2.ipynb`
- PowerPoint/PDF presentation summarizing findings: `lastname_studentnumber_assignment2.pdf`

## License
This project is for academic purposes related to the MIE 1624 course at the University of Toronto.
