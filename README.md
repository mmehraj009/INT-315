# 🎓 University Dropout Prediction using PySpark

## 📌 Overview

This project focuses on predicting student dropout risk using machine learning techniques implemented with **PySpark**. By analyzing academic and demographic data, the model identifies students who are likely to discontinue their studies, enabling early intervention and improved retention strategies.

---

## 🚀 Features

* Data preprocessing and cleaning (handling missing values)
* Categorical feature transformation using `StringIndexer`
* Feature vector creation using `VectorAssembler`
* Machine learning model using **Random Forest Classifier**
* Model evaluation using:

  * ROC-AUC
  * F1 Score
* Visualization of dropout vs retained students

---

## 🧠 Technologies Used

* Python 3.11
* Apache Spark (PySpark 4.1.1)
* Machine Learning (MLlib)
* Matplotlib (for visualization)

---

## 📂 Dataset

A **synthetic dataset** is used in this project to simulate real-world student data. It includes:

* Gender
* Region
* Program Type
* Attendance
* Grades
* Dropout Status (0 = Retained, 1 = Dropped Out)

---

## ⚙️ Project Workflow

1. **Data Loading**

   * Create dataset using PySpark DataFrame

2. **Data Cleaning**

   * Handle missing attendance and grade values using mean imputation

3. **Feature Engineering**

   * Convert categorical variables into numeric format
   * Combine features into a single vector

4. **Model Building**

   * Train a Random Forest classifier

5. **Evaluation**

   * Evaluate model using ROC-AUC and F1 Score

6. **Visualization**

   * Generate bar chart showing dropout vs retained students

---

## 📊 Results

* **ROC-AUC Score:** 1.000
* **F1 Score:** 1.000

> ⚠️ Note: Since the dataset is small, the model may overfit. Results may differ with real-world data.

---

## 🖥️ Installation & Setup

### 1. Install Dependencies

```bash
pip install pyspark matplotlib
```

### 2. Run the Project

```bash
pyspark
```

Paste the script and execute
OR

```bash
spark-submit dropout.py
```

---

## 📸 Output

* Model predictions with probabilities
* Evaluation metrics (ROC-AUC, F1 Score)
* Bar chart visualization of student distribution

---

## 📁 Project Structure

```
.
├── dropout.py
├── README.md
└── report.docx
```

---

## 🎯 Applications

* Early identification of at-risk students
* Academic performance monitoring
* Institutional decision-making support
* Educational data analytics

---

## 🔮 Future Improvements

* Use real-world datasets (e.g., Open University dataset)
* Implement Pipeline API for scalability
* Hyperparameter tuning
* Feature importance analysis
* Integration with dashboards

---

## 👨‍💻 Author

**Meftahul Mehraj**

---

## 📄 License

This project is for educational purposes.
