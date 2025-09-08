
# Prodigy InfoTech Data Science Internship Task 2

<br>  
<img src="https://github.com/Akshathahosamani/PRODIGY_DS_Task-2/blob/main/DS-2.png">  

Welcome to my submission for **Task 2** of the Data Science Internship at **Prodigy Infotech**.  
In this task, I performed **Data Cleaning and Exploratory Data Analysis (EDA)** on the Titanic dataset. The goal was to explore the dataset, clean missing or inconsistent values, and analyze patterns and relationships between variables to gain meaningful insights.

---

## 📌 Problem Statement

Datasets often contain missing values, duplicates, and noise, making them difficult to analyze directly. The objective of this task was to clean the dataset, conduct exploratory data analysis, visualize important relationships, and identify hidden trends. Using the Titanic dataset, the analysis aimed to uncover the impact of features like gender, age, class, and fare on passenger survival during the Titanic tragedy.

---

## 📊 Dataset

The dataset used for this task is the **Titanic Dataset**, a classic dataset for practicing EDA and predictive modeling. It includes passenger details such as:  

* Passenger ID, Name, Age, and Gender  
* Ticket class (Pclass) and Fare  
* Embarkation port (Embarked)  
* Survival status (Survived: 0 = No, 1 = Yes)  

👉 [Sample Dataset](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202)  

---

## 🛠 Tools and Libraries Used

The project was carried out in **Python** using **Jupyter Notebook**. The following libraries were used:  

* **Pandas & NumPy** → Data cleaning, preprocessing, and manipulation  
* **Matplotlib & Seaborn** → Data visualization and plotting  
* **Jupyter Notebook** → Interactive analysis and documentation  

---

## 🔎 Approach

1. **Data Cleaning**  
   * Handled missing values in columns like `Age` and `Embarked`  
   * Removed duplicate entries and unnecessary columns  
   * Converted categorical values into suitable formats for analysis  

2. **Exploratory Data Analysis (EDA)**  
   * Performed univariate analysis (distribution of age, fare, survival rates)  
   * Conducted bivariate analysis (relationships between gender, class, and survival)  
   * Checked correlations between numerical variables  

3. **Visualization**  
   * **Count Plots** – Gender vs Survival, Class vs Survival  
   * **Histograms** – Age distribution, Fare distribution  
   * **Heatmaps** – Correlation between features  
   * **Bar Charts** – Embarked port vs Survival  

---

## 📈 Results

The analysis revealed important insights:  

* **Gender** had a strong impact on survival – females survived at much higher rates than males.  
* **Class** also influenced survival – 1st class passengers had better chances compared to 3rd class.  
* **Age** showed patterns where children had higher survival rates than adults.  
* **Fare** was positively correlated with survival, indicating wealthier passengers had a better chance of survival.  
* Passengers from different **embarkation ports** had varying survival outcomes, though gender and class were the dominant factors.  

---

## ✅ Conclusion

This task highlights the importance of **data cleaning and exploratory data analysis** in deriving insights from raw datasets. By cleaning the Titanic dataset and visualizing relationships between variables, we discovered strong survival patterns influenced by gender, passenger class, and age. These findings not only help understand historical data but also provide a foundation for predictive modeling in future tasks.  

---

👩‍💻 **Developed by:** Akshatha Hosamani  
📅 Internship: Prodigy InfoTech – Data Science
