# 🎓 Student Performance Prediction

<p align="center">
  <b>A Comparative Study of Machine Learning Algorithms for Student Academic Performance Prediction</b>
</p>

<p align="center">

# 🚀 80.21% Project Accuracy

### 🏆 Best Model: Soft Voting Ensemble

</p>

---

## 📌 Project Overview

This Machine Learning project analyzes student academic and behavioral data to predict different student performance outcomes.

The project uses the **xAPI-Edu-Data dataset**, containing **480 student records and 17 attributes**. Multiple Machine Learning algorithms are implemented and compared for both **regression and classification tasks**.

The final improved model achieved an accuracy of **80.21%** using a **Soft Voting Ensemble**.

---

## 🎯 Project Objectives

* Implement and understand multiple supervised Machine Learning algorithms.
* Perform regression and classification using student academic and behavioral data.
* Predict student-related outcomes such as:

  * Discussion participation
  * Gender classification
  * Parent School Satisfaction
* Compare model performance using accuracy and classification metrics.
* Improve the classification model to achieve higher accuracy.
* Provide predictions based on user input.

---

## 📊 Dataset Information

| Feature              | Details                    |
| -------------------- | -------------------------- |
| **Dataset**          | xAPI-Edu-Data              |
| **Total Records**    | 480                        |
| **Total Attributes** | 17                         |
| **Domain**           | Education                  |
| **Type**             | Academic & Behavioral Data |

### Key Features

* Gender
* Nationality
* Place of Birth
* Educational Stage
* Grade
* Section
* Topic
* Semester
* Parent Relation
* Raised Hands
* Visited Resources
* Announcements View
* Discussion Participation
* Parent Survey Response
* Parent School Satisfaction
* Student Absence Days
* Student Performance Class

---

## 🤖 Machine Learning Algorithms Used

This project implements the following algorithms:

1. **Linear Regression**
2. **Logistic Regression**
3. **Decision Tree Classifier**
4. **Random Forest Classifier**
5. **Support Vector Machine (SVM)**
6. **K-Nearest Neighbors (KNN)**
7. **Naive Bayes**
8. **Soft Voting Ensemble ⭐**

---

## ⚙️ Project Workflow

```text
Load Dataset
      ↓
Data Preprocessing
      ↓
Feature Selection
      ↓
Categorical Data Encoding
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Improvement
      ↓
Final Prediction
```

---

## 📈 Model Performance

| Model                        |   Accuracy |
| ---------------------------- | ---------: |
| Support Vector Machine (SVM) |     73.96% |
| K-Nearest Neighbors (KNN)    |     71.88% |
| Naive Bayes                  |     73.96% |
| **Soft Voting Ensemble ⭐**   | **80.21%** |

---

# 🏆 Best Project Accuracy: 80.21%

<p align="center">
  <b>🎯 Achieved using an Improved Soft Voting Ensemble Model</b>
</p>

The final model combines:

* Tuned Support Vector Machine
* Gaussian Naive Bayes
* Logistic Regression

The improved model uses the following key engagement features:

* `raisedhands`
* `Discussion`
* `VisITedResources`
* `AnnouncementsView`

This feature combination helped reduce noise and improve the final prediction accuracy.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Scikit-learn**
* **NumPy**
* **Matplotlib**
* **Google Colab / Jupyter Notebook**

---

## 📂 Project Structure

```text
Student-Performance-Prediction/
│
├── xAPI-Edu-Data.csv
├── Student_Performance_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/student-performance-prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd student-performance-prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

### 4. Run the Project

Open the Jupyter Notebook or upload the project to **Google Colab** and run all cells.

---

## 🔮 Predictions Performed

The project can perform predictions for:

### 📌 Linear Regression

Predicts:

> **Discussion Participation**

Based on:

> **Number of Raised Hands**

### 📌 Logistic Regression

Predicts:

> **Gender**

Based on student engagement data.

### 📌 Decision Tree

Predicts:

> **Parent School Satisfaction**

Using academic and behavioral features.

### 📌 Random Forest

Predicts:

> **Gender**

Using an ensemble of decision trees.

### 📌 SVM, KNN & Naive Bayes

Predict:

> **Parent School Satisfaction**

Using features such as:

* Topic
* Raised Hands
* Discussion
* Performance Class
* Student Absence Days

### 📌 Improved Ensemble Model ⭐

Predicts:

> **Parent School Satisfaction**

With the **highest project accuracy of 80.21%**.

---

## 📊 Evaluation Metrics

The models are evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report

---

## 🚀 Future Improvements

* Hyperparameter optimization for additional models.
* Feature engineering and advanced feature selection.
* Deploy the model as a web application.
* Add an interactive dashboard for student predictions.
* Use larger educational datasets.
* Integrate real-time student performance analysis.

---

## 👨‍💻 Author

### **DHINAKAR R**

**B.E. Computer Science and Engineering (Cyber Security)**

---

## ⭐ Support

If you found this project useful, please consider giving the repository a **⭐ Star**!

---

<p align="center">
  Made with ❤️ by <b>DHINAKAR R</b>
</p>
