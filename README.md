# 📦 Return Prediction using Random Forest (Google Colab Project)

A simple machine learning project to **predict whether an item will be returned or not** using a Random Forest Classifier. The model is trained on a dataset uploaded by the user via Google Colab.

---

## 🚀 What this Project Does

- 📁 Uploads a CSV file using Google Colab
- 🧹 Preprocesses the data (converts `yes/no` to `1/0`)
- 🧠 Trains a `RandomForestClassifier`
- 📊 Evaluates model with **accuracy**, **precision**, **recall**
- 🔥 Displays a confusion matrix heatmap for better visualization

---

## 🧰 Tech Stack

- Python (3.8+)
- Google Colab
- pandas
- seaborn
- matplotlib
- scikit-learn

---

## 📋 CSV File Format Required

Your CSV file must contain:

- A column named **`returned`** with values `yes` or `no`
- All other columns should be numerical or preprocessed features

Example:

| feature1 | feature2 | returned |
|----------|----------|----------|
| 12.3     | 45.6     | yes      |
| 34.5     | 67.8     | no       |

---

## 📂 How to Use

### 🟢 Run on Google Colab

1. Open the notebook (`return_prediction.ipynb`) in [Google Colab](https://colab.research.google.com/)
2. Upload your dataset when prompted
3. Let the notebook do the rest 🚀

### 📦 Steps the Code Follows

```python
# Step 1: Upload a CSV file
# Step 2: Load and preview the data
# Step 3: Map 'yes'/'no' in the 'returned' column to 1/0
# Step 4: Split data into training and testing sets
# Step 5: Train the RandomForestClassifier
# Step 6: Predict and evaluate performance
# Step 7: Plot a confusion matrix heatmap
