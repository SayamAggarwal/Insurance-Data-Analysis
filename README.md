# 🏥 Insurance Claim Analysis - EDA

## 📌 Project Overview  
This project explores a **Health Insurance Claim dataset** to identify patterns in claims, medical expenses, age groups, BMI, smoking habits, and regional impacts.  
The goal is to practice **data cleaning, wrangling, visualization, and exploratory data analysis (EDA)** while uncovering insights about healthcare costs.  

---

## 📂 Dataset  
- Source: [Health Insurance Dataset (Kaggle)](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- Size: ~1300 records  
- Columns:  
  - `age` → Age of primary beneficiary  
  - `sex` → Gender (male/female)  
  - `bmi` → Body Mass Index  
  - `children` → Number of dependents covered by insurance  
  - `smoker` → Smoking status (yes/no)  
  - `region` → Residential area (northeast, northwest, southeast, southwest)  
  - `charges` → Individual medical costs billed by health insurance  

---

## 🔍 Analysis Performed  
- **Data Cleaning**: Checked missing values, encoded categorical variables  
- **Demographics**: Analyzed age and gender distribution  
- **Charges Analysis**: Compared average charges by age, gender, and smoking status  
- **BMI & Health**: Explored correlation between BMI and insurance charges  
- **Children Factor**: Studied the effect of dependents on medical expenses  
- **Regional Trends**: Compared insurance charges across different regions  

---

## 📈 Key Findings  
- 💸 **Smokers pay significantly higher charges** than non-smokers.  
- 👵 Charges increase steadily with **age**, with a sharp rise after 50 years.  
- ⚖️ Higher **BMI correlates with higher charges**, especially for obese individuals.  
- 👨‍👩‍👧 Number of children has **minimal direct effect** on charges.  
- 🌍 Regional differences exist but are **less significant** compared to smoking and BMI.  

---

## 🛠️ Tech Stack  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📌 How to Run  
1. Clone this repo:  
   ```bash
   git clone git@github.com:SayamAggarwal/Insurance-EDA.git
2. Open the Insurance_EDA.ipynb notebook in Jupyter/Colab.

3. Run all cells to reproduce the analysis.
