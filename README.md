# 🌱 Flourishing in the Workplace – A Data Science Exploration  
*Individual Project – Supervised by Dr. Franck Jaotombo (emlyon business school)*  

🔗 **[Project Folder (Google Drive)](https://drive.google.com/drive/folders/1UhVQDStFD7Qta_IiU1XctWvUqZee6WsM?usp=drive_link)**  

---

## 📌 Project Overview  
This project investigates the well-being and work-life balance of employees using a dataset of **248 individuals**. The goal is to analyze the factors influencing professional and personal flourishing through **Exploratory Data Analysis (EDA)**, **predictive modeling**, and **unsupervised learning** techniques.  

📄 **A PDF file with a detailed analysis of the project is included in the repository.**  

---

## 📋 Table of Contents  
- [Project Overview](#-project-overview)  
- [Key Features](#-key-features)  
- [How It Works](#-how-it-works)  
- [Technologies & Tools](#-technologies--tools)  
- [Model Performance](#-model-performance)  
- [Installation & Setup](#-installation--setup)  
- [Results](#-results)  
- [Future Improvements](#-future-improvements)  
- [References](#-references)  

---

## 🚀 Key Features  
- **Exploratory Data Analysis (EDA)**: Univariate and bivariate analysis of well-being factors (age, education, family status, etc.).  
- **Supervised Learning**:  
   - Multiple Linear Regression (Predicting Flow)  
   - Logistic Regression (Predicting Positivity Levels)  
   - KNN (Regression & Classification)  
- **Unsupervised Learning**:  
   - Principal Component Analysis (PCA)  
   - K-Means Clustering  
- **Visualization**: Analysis outputs visualized through bar charts, pie charts, and correlation matrices.  
- **Feature Engineering**: Handling multicollinearity, ANOVA testing, and encoding categorical variables.  

---

## ⚙️ How It Works  
1. **Data Overview**:  
   - Dataset of 248 individuals with 10 key variables.  
   - Variables include demographic info (age, gender, education) and well-being indicators (professional/private flourishing, positivity, and flow).  

2. **EDA Process**:  
   - Analyzed distribution of numerical/categorical variables.  
   - Measured correlations, ANOVA, and effect sizes (Cohen's d).  

3. **Modeling Approach**:  
   - **Flow Prediction** (Continuous Target):  
     - Models: Multiple Linear Regression, KNN Regression.  
   - **Positivity Prediction** (Categorical Target):  
     - Models: Logistic Regression, KNN Classifier.  

4. **Dimensionality Reduction & Clustering**:  
   - **PCA** reduces the dataset to two principal components (78.5% explained variance).  
   - **K-Means Clustering** segments the data into high and low well-being clusters.  

---

## 🛠️ Technologies & Tools  
- **Machine Learning Frameworks**: Scikit-Learn, StatsModels  
- **Languages**: Python  
- **Visualization**: Matplotlib, Seaborn  
- **Development Tools**: Jupyter Notebooks, Google Colab  
- **Version Control**: Git & GitHub  
- **Statistical Analysis**: ANOVA, Correlation (Pearson’s r), and Cohen’s d  
- **Clustering & Dimensionality Reduction**: PCA, K-Means  

---

## 📊 Model Performance  
- **Multiple Linear Regression**:  
   - Adjusted R²: **0.3121** (31.21% variability explained)  
   - Normalized RMSE: **15.84%**  
- **KNN Regression**:  
   - Adjusted R²: **0.2197**  
   - Normalized RMSE: **16.87%**  
- **Logistic Regression (Positivity Prediction)**:  
   - Accuracy: **74%**  
- **KNN Classifier**:  
   - Accuracy: **74%** (slightly overfitting majority classes)  

---

## 📥 Installation & Setup  
### 1. Clone the Repository  

- **A dataset and Jupyter notebook are included in the GitHub repository.**
- **Open the notebook and run each cell step-by-step.**   
- **Ensure to update the path to the dataset to match your local PC directory before running the notebook.**  

Example:  
```python
FILE_PATH = "path/to/your/local/datasets/"
```  

---

## 📈 Results  
- **Key Insights**:  
   - Higher education correlates with improved emotional well-being.  
   - Age, professional flourishing, and private flourishing strongly predict **flow**.  
   - Married or partnered individuals reported higher well-being scores.  
- **Clusters**:  
   - **Cluster 0**: High flourishing scores (correlated with age and experience).  
   - **Cluster 1**: Low flourishing scores (in need of targeted well-being initiatives).  

---

## 🔧 Future Improvements  
- **Feature Expansion**: Collect additional well-being indicators to enhance model performance.  
- **Deep Learning Models**: Experiment with neural networks for predicting emotional well-being.  
- **Class Balancing**: Address class imbalance in positivity predictions to improve recall for smaller categories.  
- **Real-Time Dashboards**: Develop interactive dashboards to visualize flourishing metrics dynamically.  

---

## 📚 References  
- [Csikszentmihalyi, M. (2009). *Flow: The Psychology of Optimal Experience.*](https://www.harpercollins.com/products/flow-mihaly-csikszentmihalyi?variant=40957940101154)  
- [Fredrickson, B. (2009). *Positivity.*](https://www.penguinrandomhouse.com/books/304407/positivity-by-barbara-l-fredrickson-phd/)  
- [OpenAI. ChatGPT: A Conversational AI Model.](https://www.openai.com/chatgpt)  
