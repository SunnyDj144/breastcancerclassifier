# 🧬 Breast Cancer Classification using SVM

This project demonstrates a basic machine learning classification task using the **Support Vector Machine (SVM)** algorithm to predict whether a tumor is **benign** or **malignant** based on the **Breast Cancer Wisconsin dataset**.

---

## 📌 Objective

To create a machine learning model that can classify breast cancer tumors using supervised learning techniques, aiding in early detection and treatment planning.

---

## 🧠 Dataset

- Dataset used: `Breast Cancer Wisconsin` from `sklearn.datasets`
- Features: Measurements of cell nuclei present in breast cancer biopsies
- Labels: `0` = Malignant, `1` = Benign

---

## 🚀 Workflow

1. Load dataset from `sklearn.datasets`
2. Split the data into training and test sets
3. Build a Support Vector Machine classifier (`SVC` with linear kernel)
4. Train the model using training data
5. Predict results on the test set
6. Evaluate model accuracy using `accuracy_score`

---

## 📊 Sample Output

Actual Value: benign Prediction: benign
Actual Value: malignant Prediction: malignant
...
Accuracy: 0.9649

yaml
Copy
Edit

---

## 🧰 Technologies Used

- Python
- scikit-learn
- NumPy
- SVM (Support Vector Machine)
- Accuracy Score (Evaluation Metric)

---


👨‍💻 Author
Prakashraj Kotapuri



📄 License
This project is licensed under the MIT License.
