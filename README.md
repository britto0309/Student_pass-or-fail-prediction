# Student_pass-or-fail-prediction

# 🎓 Student Pass/Fail Prediction using Random Forest

## 📌 Project Overview

This project predicts whether a student is likely to **Pass** or **Fail** using the **Random Forest Classifier** algorithm from **Scikit-learn**.

The model is trained on a sample dataset containing student academic information such as **Study Hours, Attendance, Assignments Completed, and Previous Marks**. Based on these features, the model predicts the student's result.

The project also visualizes **Feature Importance**, a **Confusion Matrix**, and **one Decision Tree** from the Random Forest.

---

# 🎯 Objectives

* Build a student performance prediction model using Random Forest.
* Train the model using student academic data.
* Predict whether a student will Pass or Fail.
* Visualize the importance of each feature.
* Display a Confusion Matrix to evaluate predictions.
* Visualize one Decision Tree from the Random Forest.

---

# 🧠 Machine Learning Algorithm

**Algorithm Used:** Random Forest Classifier

Random Forest is a supervised machine learning algorithm used for classification and regression tasks. It builds multiple Decision Trees using different subsets of the training data and combines their predictions using majority voting.

Compared to a single Decision Tree, Random Forest generally provides:

* Higher accuracy
* Better generalization
* Reduced overfitting
* More robust predictions

---

# 📂 Dataset

The project uses a manually created dataset containing **15 student records**.

### Input Features

* Study Hours (Hours per Day)
* Attendance (%)
* Assignments Completed
* Previous Marks

### Target Variable

* Result (Pass / Fail)

---

# ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

# 📚 Libraries Used

```python
pandas
matplotlib
scikit-learn
```

---

# 🔄 Project Workflow

1. Create the student dataset.
2. Encode the target variable (Pass/Fail).
3. Train the Random Forest Classifier.
4. Accept student details from the user.
5. Predict whether the student is likely to Pass or Fail.
6. Display the Feature Importance graph.
7. Display the Confusion Matrix.
8. Visualize one Decision Tree from the Random Forest.

---

# 🔢 Data Preprocessing

The target variable **Result** contains categorical values:

* Pass
* Fail

These values are converted into numerical values using **LabelEncoder** before training the model.

---

# 📊 Model Evaluation

### Training Accuracy

The program calculates the training accuracy to measure how well the model fits the training data.

### Confusion Matrix

The Confusion Matrix compares:

* Actual Results
* Predicted Results

It helps evaluate the classification performance of the model.

---

# 🌳 Decision Tree Visualization

A Random Forest contains multiple Decision Trees.

This project displays **one Decision Tree** from the forest to help visualize how decisions are made during prediction.

---

# 📈 Feature Importance

The Feature Importance graph shows which features contribute the most to the prediction.

Example features include:

* Study Hours
* Attendance
* Assignments Completed
* Previous Marks

Features with higher importance have a greater influence on the model's predictions.

---

# 🚀 Features

* Student Performance Prediction
* Random Forest Classification
* Label Encoding
* Interactive User Input
* Feature Importance Visualization
* Confusion Matrix Visualization
* Decision Tree Visualization

---

# ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Student-Pass-Fail-Prediction-Random-Forest.git
```

### Navigate to the project folder

```bash
cd Student-Pass-Fail-Prediction-Random-Forest
```

### Install required libraries

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python student_prediction.py
```

---

# 💻 Sample Input

```
Study Hours per Day: 6
Attendance (%): 90
Assignments Completed: 8
Previous Marks: 85
```

---

# 📤 Sample Output

```
Training Accuracy: 100.00%

Prediction:

Student is likely to PASS
```

### Another Example

#### Input

```
Study Hours per Day: 2
Attendance (%): 55
Assignments Completed: 2
Previous Marks: 40
```

#### Output

```
Prediction:

Student is likely to FAIL
```

---

# 📈 Output Visualizations

The project generates three graphical outputs:

### 1. Feature Importance Graph

Shows the contribution of each feature to the prediction.

```markdown
![Feature Importance](feature_importance.png)
```

---

### 2. Confusion Matrix

Displays the comparison between actual and predicted results.

```markdown
![Confusion Matrix](confusion_matrix.png)
```

---

### 3. Decision Tree Visualization

Displays one of the Decision Trees from the Random Forest.

```markdown
![Decision Tree](decision_tree.png)
```

---

# 📁 Project Structure

```
Student-Pass-Fail-Prediction-Random-Forest
│
├── student_prediction.py
├── README.md
├── requirements.txt
├── feature_importance.png
├── confusion_matrix.png
├── decision_tree.png
└── .gitignore
```

---

# 📖 Learning Outcomes

Through this project, you will learn:

* Random Forest Classification
* Decision Tree Ensembles
* Label Encoding
* Model Training and Prediction
* Feature Importance Analysis
* Confusion Matrix Interpretation
* Decision Tree Visualization
* Interactive Machine Learning Applications

---

# 🔮 Future Improvements

* Train the model using a larger real-world student performance dataset.
* Include additional features such as participation, quiz scores, and extracurricular activities.
* Split the dataset into training and testing sets to evaluate generalization performance.
* Save and load the trained model using Joblib or Pickle.
* Build a web application using Streamlit or Flask.

---

# 👨‍💻 Author

**Britto Domnic Aro J**

Machine Learning Enthusiast | Python Developer | AI Learner

---

# ⭐ If you found this project useful, consider giving this repository a Star on GitHub!
