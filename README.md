# 🛳 Titanic Survival Prediction – Exploratory Data Analysis (EDA)

## Project Overview  
The Titanic dataset is one of the most iconic datasets in data science, often used for beginner-to-intermediate machine learning and analysis tasks.  
In this project, I performed a **comprehensive Exploratory Data Analysis (EDA)** to investigate survival patterns across various demographic and social features such as **gender, passenger class, age, and family size**.  

---

## Objectives  
- Clean and prepare the Titanic dataset for analysis.  
- Perform univariate and bivariate analysis to understand survival distribution.  
- Visualize data trends using **Matplotlib** and **Seaborn**.  
- Apply **feature engineering** such as encoding categorical variables.  
- Extract insights about how **gender, class, and age influenced survival**.  

---

##  Tools & Libraries  
- **Pandas** → Data wrangling and cleaning  
- **NumPy** → Numerical computations  
- **Matplotlib** → Basic plotting and visualization  
- **Seaborn** → Advanced and aesthetic statistical plots  
- **Scikit-learn** → Label encoding and preprocessing  
- **Jupyter Notebook** → Documentation and execution  

---

##  Data Preprocessing Steps  
1. Handling Missing Values  
2. Feature Engineering  
3. Exploratory Data Analysis  

---

##  Visuals & Screenshots  

Here are some example plots generated during analysis:

### 🔹 Survival by Gender  
![Survived Men](https://github.com/rahmasaber123/TITANIC-EDA/blob/main/survived_men.png?raw=true)

### 🔹 Survival by Passenger Class  
![Survival by Class](https://github.com/rahmasaber123/TITANIC-EDA/blob/main/survival_based_on_class.png?raw=true)

### 🔹 Age Distribution of Survivors vs Non-Survivors  
![Age Distribution](https://github.com/rahmasaber123/TITANIC-EDA/blob/main/age.png?raw=true)



---

## 🔍 Insights & Findings  
- Women were much more likely to survive (`~74%`) compared to men (`~19%`).  
- First-class passengers had significantly higher survival rates than third-class.  
 

---

## 📂 Project Structure  
Titanic-EDA/
│
├── data/ # Dataset files
│ ├── titanic.csv # Training dataset
│ 
│
├── images/ # Visualizations & plots
│ ├── survival_gender.png
│ ├── survival_class.png
│ └── age_distribution.png
│
├── TitanicEDA.ipynb # Main Jupyter Notebook (EDA & visualizations)
├── requirements.txt # Required Python packages
├── README.md # Project documentation 

