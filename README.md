# Employee Attrition Prediction  

## 📌 Project Overview  
Employee attrition (or turnover) is a major concern for organizations, as retaining skilled employees saves cost and improves productivity.  
This project aims to **predict whether an employee will leave the company or not** using **Machine Learning techniques** based on HR and employee-related data.  

The goal is to provide insights that help HR teams in decision-making by identifying key factors that influence attrition.  

---

## 🎯 Objectives  
- Analyze employee-related data and identify factors contributing to attrition.  
- Build predictive machine learning models to classify employees as **likely to stay** or **likely to leave**.  
- Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.  
- Provide data visualizations for better insights.  

---

## 🗂 Dataset  
- **Source:** IBM HR Analytics Employee Attrition Dataset (public dataset)  
- **Features include:**  
  - Demographics: Age, Gender, Marital Status  
  - Job-related: Department, Job Role, Years at Company, Work-Life Balance, Job Satisfaction  
  - Compensation: Salary, Percent Salary Hike, Stock Option Level  
  - Performance & Work: Overtime, Training Times, Performance Rating  
- **Target Variable:** `Attrition` (Yes/No)  

---

## ⚙️ Technologies Used  
- **Language:** Python 🐍  
- **Libraries:**  
  - Data Analysis: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  
  - Model Building: Logistic Regression, Decision Trees, Random Forest, Gradient Boosting  

---

## 🛠️ Steps Performed  
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**  
   - Attrition distribution  
   - Correlation heatmap  
   - Key insights on Overtime, Job Role, Work-Life Balance, Salary  

3. **Model Building**  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  

4. **Model Evaluation**  
   - Confusion Matrix  
   - Accuracy, Precision, Recall, F1-Score  
   - ROC Curve & AUC  

---

## 📊 Results  
- The **Random Forest Classifier** achieved the best performance with high accuracy and balanced recall/precision.  
- Key factors affecting attrition:  
  - Overtime  
  - Job Role  
  - Monthly Income  
  - Years at Company  
  - Work-Life Balance  

---

## 📷 Sample Visualizations  
- Attrition Count Plot  
- Correlation Heatmap  
- Feature Importance Graph  
- ROC Curve  

---

## 🚀 How to Run the Project  
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/employee-attrition-prediction.git
   cd employee-attrition-prediction
