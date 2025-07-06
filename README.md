# 💸 PyTorch Customer Churn Prediction Neural Network

---

## About This Project

This **solo personal project**, completed in **November 2024**, was born from my desire to master the world of AI Engineering. Having previously worked with TensorFlow, I wanted to dive deeper into PyTorch's customization capabilities and gain hands-on experience with its core functionalities through trial and error.

The goal was to build a neural network to predict customer churn using the **Kaggle "Telco Customer Churn" dataset** (available [here](https://www.kaggle.com/blastchar/telco-customer-churn)). This project allowed me to explore various approaches, from an initial attempt to a more refined strategy involving advanced data preprocessing to overcome common challenges like **class imbalance** and **model overfitting**.

---

## Project Overview

This project targets customer churn prediction through a neural network developed in PyTorch.

1.  **Initial Approach:** I began by loading, basic preprocessing (scaling, train/test/validation split), and converting the data to PyTorch tensors. After defining a multi-layered neural network and setting up loss and optimizer functions, the initial model was trained and evaluated.
    * **Challenge:** The original model suffered from **overfitting** and achieved a modest 76% accuracy, barely outperforming the 73% baseline accuracy of random guessing (due to unbalanced classes).

2.  **Refined Approach:** Recognizing that class imbalance was the primary culprit for poor performance, I implemented an **updated data preprocessing strategy**. This involved:
    * **Upsampling** the minority class to balance the dataset.
    * Carefully handling missing values.
    * Redefining and retraining the model architecture.
    * **Result:** The new approach significantly mitigated overfitting, drastically reduced model loss, and ultimately led to a **92% accuracy** on churn predictions.

---

## Key Achievements

* **Engineered a PyTorch neural network** that accurately predicts customer churn, achieving **92% test-set accuracy**.
* **Leveraged upsampling** and advanced data preprocessing to effectively **address class imbalance** and **mitigate model overfitting**.
* Hands-on experience in PyTorch, moving beyond theoretical understanding to practical application.

---

## Technologies Used

* **Python**
* **PyTorch**
* **Pandas**
* **NumPy**
* **Scikit-learn**

---

## In This Repo

* Primary Jupyter Notebook
* Telco Customer Churn Dataset
* Final Exported Model

---

Feel free to explore the repository and the code! If you have any questions, don't hesitate to reach out.
