# Data Science portfolio

Welcome to my portfolio! This repository showcases my expertise in machine learning, data analysis, and programming through a collection of projects. Each project demonstrates my ability to solve real-world problems. Below, you'll find an overview of my work, including goals, methodologies, and results.

---

## **Projects**

### **1. Feature Selection for Alzheimer’s Diagnosis Using the DARWIN Handwriting Dataset**
#### **Description**
This project focuses on identifying the most representative handwriting features for predicting Alzheimer’s Disease (AD) using the DARWIN dataset. The dataset includes 450 features from 25 handwriting tasks performed by 174 participants (89 AD patients and 85 healthy controls). The goal is to reduce dimensionality, avoid overfitting, and improve model performance.

#### **Skills**
- Feature selection (Ridge, Lasso, Random Forest, etc.)
- Hyperparameter tuning (GridSearchCV)
- Model evaluation (ROC-AUC, accuracy, sensitivity, specificity)
- Data visualization (Matplotlib, Seaborn)

#### **Packages/Tech Used**
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

#### **Results**
- **Best Model**: Random Forest with bootstrapping feature selection (AUC = 1.0).
- **Most Predictive Task**: "Copy the details of a postal code."
- **Key Insight**: Copy and memory tasks were more effective than graphic tasks for AD classification.

#### **Code Link**: [Feature Selection for Alzheimer’s Diagnosis](P01_feature_selection_Alzheimer-disease.ipynb)

---

### **2. Optimized Frame Selection for Fish Behavioral Analysis**
#### **Description**
This project optimizes frame selection for analyzing fish movement in long-duration videos. Instead of processing every frame, a lightweight YOLO detection and clustering approach (DBSCAN) is used to extract the most representative frames per hour. This reduces computational load while capturing dominant behavioral patterns.

#### **Skills**
- Temporal downsampling
- Object detection (YOLO)
- Clustering (DBSCAN)
- Data preprocessing and optimization

#### **Packages/Tech Used**
- Python, OpenCV, Ultralytics, Scikit-learn, Pandas, NumPy

#### **Results**
- Efficiently selected key frames for fish position analysis.
- Reduced computational cost by avoiding processing every frame.
- Enabled accurate thermal zone counting for behavioral fever studies.

#### **Code Link**: [Optimized Frame Selection for Fish Behavioral Analysis](P02_frame_selection_for_fish_behavioral_analysis.ipynb)

---

### **3. SQL Project: Analysis of Data Jobs in 2023**
#### **Description**
This project analyzes job postings for Machine Learning Engineers and Data Scientists in 2023. Using SQL, I explored trends in job locations, salaries, required skills, and remote work opportunities. The dataset includes job postings, company details, and skill requirements.

#### **Skills**
- SQL querying and analysis
- Data aggregation and filtering
- Trend analysis and visualization

#### **Packages/Tech Used**
- SQL, GitHub, VS Code

#### **Results**
- Identified top-paying jobs in Canada and remote roles.
- Analyzed in-demand skills for Machine Learning Engineers and Data Scientists.
- Provided insights into salary trends and job market dynamics.

#### **Code Link**: [SQL Project: Analysis of Data Jobs in 2023](project03_SQL-data-jobs-analysis)

---

### **4. Exercises: Classification and Regression**
#### **Description**
This project includes two machine learning tasks:
1. **Binary Classification**: Using the Parkinson’s Disease Detection dataset, I built a model to differentiate between healthy individuals and those with Parkinson’s based on voice features.
2. **Regression**: Using the Medical Cost dataset, I predicted healthcare insurance costs based on demographic and lifestyle factors.

#### **Skills**
- Binary classification (Logistic Regression, Random Forest)
- Regression analysis (Linear Regression, Gradient Boosting)
- Feature importance analysis
- Model evaluation (accuracy, RMSE, R²)

#### **Packages/Tech Used**
- Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

#### **Results**
- **Classification**: Achieved high accuracy in detecting Parkinson’s Disease using voice features.
- **Regression**: Identified key factors (e.g., smoking, age) influencing healthcare costs.

#### **Code Link**: [Exercises: Classification and Regression](P04_parkinson-classification_medical_regression.ipynb)

---

## 💡 **Skills**
- **Programming Languages**: Python, SQL
- **Machine Learning**: Feature selection, classification, regression, clustering
- **Data Analysis**: Data cleaning, feature engineering, data visualization
- **Tools & Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow, OpenCV, Matplotlib, Seaborn
- **Other Skills**: Git, GitHub, Jupyter Notebooks, VS Code

---

## 📦 **Packages & Technologies Used**
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-learn, TensorFlow, YOLO
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Other Tools**: Git, OpenCV, SQL

---

## 📊 **Results**
- Achieved **>90% accuracy** in Alzheimer’s diagnosis using Random Forest.
- Reduced computational load by **80%** in fish behavioral analysis.
- Identified **top-paying jobs** and in-demand skills in the 2023 data job market.
- Predicted healthcare costs with **high accuracy** using regression models.

---

## 📫 **Contact Me**
If you’d like to connect or discuss potential opportunities, feel free to reach out:
- **LinkedIn**: [Massiel Copara](https://www.linkedin.com/in/massiel-copara-utec/)
- **Email**: [coparach@ualberta.ca](#)
- **Portfolio Website**: [Website](https://massielc.github.io/#)

---

Thank you for visiting my portfolio! I hope you find my work insightful and impactful. Let’s connect and create something amazing together! 😊
