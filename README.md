# 🛍️ Purchase Prediction using Decision Tree Classifier

This project uses a **Decision Tree Classifier** to predict whether a user will purchase a product based on their **age**, **gender**, and **annual salary**.

---

## 💡 Project Motivation

I was curious about how companies target users for ads and wanted to explore which features influence user buying behavior. So, I built a machine learning model that predicts purchase decisions using a decision tree.

---

## 📊 Dataset Features

| Column        | Description                                 |
|---------------|---------------------------------------------|
| `User ID`     | Unique identifier for each user             |
| `Gender`      | Gender of the user (Male/Female)            |
| `Age`         | Age of the user                             |
| `AnnualSalary`| User’s annual income                        |
| `Purchased`   | Whether the user made a purchase (0 or 1)   |

The target variable is: **`Purchased`**

---

## 🧠 ML Model

We use a **Decision Tree Classifier** from `sklearn` to train a supervised classification model.

### ✅ Model Includes:
- Data Preprocessing
- Label Encoding for Gender
- Train-test split
- Decision Tree Training
- Accuracy Score
- Confusion Matrix
- Visualization of the Tree (optional using `graphviz` or `plot_tree`)

---

## 🛠️ Libraries Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Graphviz (optional)

---

