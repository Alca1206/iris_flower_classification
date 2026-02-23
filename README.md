# 🌸 Iris Flower Classification (PyTorch)

## 📌 Project Overview
This project applies Deep Learning to the classic Iris Flower classification problem. Using **PyTorch**, a custom artificial neural network was built and trained to classify Iris flowers into three distinct species (Setosa, Versicolor, and Virginica) based on their physical sepal and petal measurements.

## 📂 The Dataset
* **Source:** The classic Fisher's Iris dataset (`iris.data`).
* **Features:** 4 physical measurements (Sepal Length, Sepal Width, Petal Length, Petal Width).
* **Target:** 3 Species (Iris-setosa, Iris-versicolor, Iris-virginica).

## 🛠️ Tech Stack & Libraries
* **Deep Learning:** PyTorch (`torch`, `torch.nn`, `torch.optim`)
* **Data Processing:** Pandas, NumPy, Scikit-Learn (`StandardScaler`, `LabelEncoder`, `train_test_split`)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 🚀 Key Features & Workflow
1. **Exploratory Data Analysis (EDA):** Analyzed data distributions, checked for missing values, and handled duplicates.
2. **Data Preprocessing:** Standardized numerical features and encoded categorical text labels into PyTorch-compatible tensors.
3. **Model Training:** Built a Multi-Layer Perceptron (MLP) neural network using PyTorch. Trained the model over 200 epochs using the Adam optimizer and Cross-Entropy Loss.
4. **Model Evaluation:** Evaluated the model using strict classification metrics, including overall **Accuracy**, a **Classification Report** (Precision, Recall, F1-Score), and a **Confusion Matrix**.
5. **Model Exporting:** Successfully saved the trained model state dictionary (`iris_model.pth`) for future inference and deployment.

