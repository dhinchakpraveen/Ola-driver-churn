# Ola Driver Churn Prediction

This project aims to **predict driver churn at Ola Cabs** using historical driver data. By analyzing demographic, performance, and tenure attributes, the project builds predictive models to identify drivers likely to leave and support proactive retention strategies.

---

## 📌 Problem Statement

Ola faces **high driver churn**, which negatively impacts:

- Driver morale  
- Customer experience  
- Driver acquisition and training costs  

This project seeks to:  

- Identify **key factors influencing driver departures**  
- Build a **predictive model** for driver attrition  
- Provide **data-driven insights** for retention strategies  

---

## 📊 Dataset

The project uses the dataset: **`ola_driver.csv`**  
It contains **monthly driver information** for **2019 and 2020** with attributes grouped as follows:

- **Demographics**:  
  - City, Age, Gender (Male: 0, Female: 1)  

- **Tenure**:  
  - Joining Date, Last Working Date  

- **Performance**:  
  - Quarterly Rating, Monthly Business Value, Grade, Income  

- **Additional**:  
  - Education Level, Joining Designation  

---

## 🏗️ Project Structure

The project consists of **Python scripts** that perform the following tasks:

1. **Data Exploration & Cleaning**  
   - Inspect dataset structure and characteristics  
   - Handle missing values using **KNN imputation**  

2. **Feature Engineering**  
   - Aggregate driver data (e.g., income and rating growth)  
   - Encode categorical variables (**one-hot encoding**)  

3. **Data Balancing**  
   - Address class imbalance in the churn variable  

4. **Modeling**  
   - Implement **Ensemble Learning** (Bagging, Boosting)  
   - Apply **hyperparameter tuning** for optimization  

5. **Evaluation**  
   - Generate **classification reports**  
   - Plot **ROC-AUC curves**  

6. **Insights**  
   - Interpret results  
   - Provide **actionable recommendations** for reducing churn  

---

## 🚀 Future Work

- Experiment with **deep learning approaches**  
- Incorporate **real-time churn prediction pipelines**  
- Deploy model as an **API service**  

---

## 📂 Repository Contents


- `notebooks/` → Exploratory data analysis & model building  
- `scripts/` → Python scripts for preprocessing, modeling, evaluation  
- `README.md` → Project documentation  

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit a pull request.  

---

## 📜 License

This project is licensed under the **MIT License**.  
