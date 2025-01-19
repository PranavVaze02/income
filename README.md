
---
# Income Prediction

This project predicts income levels based on demographic and socio-economic features using machine learning techniques. The analysis involves data preprocessing, feature engineering, and classification modeling, with results visualized for better insights.

---

## **Project Overview**

The goal of this project is to:

- Analyze socio-economic factors affecting income levels.
- Classify individuals into two income categories: `<=50K` and `>50K`.
- Build and evaluate machine learning models for income prediction.
- Extract and visualize insights for decision-making.

---

## **Dataset**

The dataset consists of demographic and employment-related features for individuals. It has been preprocessed to handle missing data and encode categorical variables.

### **Dataset Details**
- **File**: `income_evaluation.csv`
- **Target Variable**: Income (`<=50K` or `>50K`)
- **Columns**:
  - **age**: Age of the individual.
  - **workclass**: Employment type (e.g., Private, Self-employed).
  - **education**: Education level attained.
  - **marital-status**: Marital status.
  - **occupation**: Occupation type.
  - **race**: Race of the individual.
  - **sex**: Gender of the individual.
  - **hours-per-week**: Weekly working hours.
  - **native-country**: Country of origin.

---

## **Methodology**

### **1. Data Preprocessing**
- **Cleaning**:
  - Removed missing or irrelevant data.
  - Encoded categorical variables using one-hot and label encoding.
- **Feature Scaling**:
  - Applied normalization to numeric features for better model performance.

### **2. Machine Learning**
- **Features**: Demographic and employment-related attributes.
- **Labels**: Binary income classification (`<=50K`, `>50K`).
- **Models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- **Evaluation**:
  - Used accuracy, precision, recall, and F1 score to evaluate models.

### **3. Visualization**
- Used Python visualization libraries (Matplotlib and Seaborn) to explore:
  - Distribution of income categories.
  - Correlation between features and income.
  - Feature importance derived from tree-based models.

---

## **Results**

- The **Random Forest** model achieved the highest accuracy in predicting income categories.
- Insights:
  - Weekly working hours and education level are strong predictors of income.
  - Gender and occupation type also significantly impact income distribution.

---

## **How to Run This Project**

### **Requirements**
- Python 3.8 or above
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### **Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/PranavVaze02/income.git
   ```
2. Navigate to the project directory:
   ```bash
   cd income
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook INCOME.ipynb
   ```

---

## **Project Files**

- **income_evaluation.csv**: Raw dataset used for analysis.
- **INCOME.ipynb**: Jupyter Notebook containing the full analysis and modeling.
- **README.md**: Documentation for the project.
- **requirements.txt**: List of dependencies required to run the project.

---

## **Conclusion**

This project demonstrates how machine learning can be used to analyze demographic data and predict income levels. By understanding the factors affecting income, stakeholders can make informed decisions for social and economic improvements.

---

## **Acknowledgments**

- **Dataset**: Publicly available dataset for income classification tasks.
- **Libraries**: Python, Scikit-learn, Pandas, Matplotlib, Seaborn.
- **Tools**: Jupyter Notebook.

---