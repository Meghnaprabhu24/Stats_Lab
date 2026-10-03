# 📊 Statistics Lab

A collection of **Statistics Lab experiments implemented in Python using Jupyter Notebooks**.
The experiments use the **Pima Indians Diabetes Dataset** to demonstrate statistical analysis, data preprocessing, hypothesis testing, confidence intervals, regression, classification, and clustering techniques.

## 📌 Repository Overview

This repository contains **8 practical experiments** covering different concepts used in statistics and data science.

### Dataset Used

All experiments are based on the **Pima Indians Diabetes Dataset**.

The dataset contains **768 observations and 9 variables**:

| Feature                    | Description                                         |
| -------------------------- | --------------------------------------------------- |
| `Pregnancies`              | Number of times pregnant                            |
| `Glucose`                  | Plasma glucose concentration                        |
| `BloodPressure`            | Diastolic blood pressure                            |
| `SkinThickness`            | Triceps skin fold thickness                         |
| `Insulin`                  | 2-Hour serum insulin                                |
| `BMI`                      | Body Mass Index                                     |
| `DiabetesPedigreeFunction` | Diabetes pedigree function                          |
| `Age`                      | Age of the individual                               |
| `Outcome`                  | Diabetes outcome: `0 = No Diabetes`, `1 = Diabetes` |

> **Note:** In some experiments, zero values in measurements such as Glucose, BloodPressure, SkinThickness, Insulin, and BMI are treated as missing/invalid values and handled during preprocessing.

---

## 🧪 Experiments

| Experiment       | Notebook                                                       | Topic / Work Covered                                                  |
| ---------------- | -------------------------------------------------------------- | --------------------------------------------------------------------- |
| **Experiment 1** | [`Exp1.ipynb`](./Exp1.ipynb)                                   | Basic statistical analysis of the Pima Indians Diabetes Dataset       |
| **Experiment 2** | [`Stats_Experiment_No_2.ipynb`](./Stats_Experiment_No_2.ipynb) | Descriptive statistics, numerical-variable analysis and visualization |
| **Experiment 3** | [`Stats_Experiment_No_3.ipynb`](./Stats_Experiment_No_3.ipynb) | Data preprocessing, standardization and distance/similarity measures  |
| **Experiment 4** | [`Stats_Experiment_No_4.ipynb`](./Stats_Experiment_No_4.ipynb) | Statistical inference, hypothesis testing and confidence intervals    |
| **Experiment 5** | [`Stats_Experiment_No_5.ipynb`](./Stats_Experiment_No_5.ipynb) | Bootstrap sampling and bootstrap confidence intervals                 |
| **Experiment 6** | [`Stats_Experiment_No_6.ipynb`](./Stats_Experiment_No_6.ipynb) | Regression analysis and residual analysis                             |
| **Experiment 7** | [`Stats_Experiment_No_7.ipynb`](./Stats_Experiment_No_7.ipynb) | Classification using Logistic Regression and K-Nearest Neighbors      |
| **Experiment 8** | [`Stats_Experiment_No_8.ipynb`](./Stats_Experiment_No_8.ipynb) | Dimensionality reduction using PCA and clustering                     |

---

## 🛠️ Technologies Used

* **Python 3**
* **Jupyter Notebook / Google Colab**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **SciPy**
* **Scikit-learn**

---

## 📚 Concepts Covered

The experiments provide hands-on practice with:

* Data loading and exploration
* Descriptive statistics
* Mean, variance and standard deviation
* Data preprocessing
* Handling invalid/missing values
* Feature standardization
* Euclidean distance
* Manhattan distance
* Cosine similarity
* Statistical inference
* Hypothesis testing
* Confidence intervals
* Bootstrap sampling
* Regression analysis
* Regression residuals
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Model evaluation
* Principal Component Analysis (PCA)
* Clustering
* Data visualization

---

## 🚀 How to Run

### Option 1 — Google Colab

1. Open any `.ipynb` file from this repository.
2. Open the notebook in Google Colab.
3. Upload the required `diabetes.csv` dataset when prompted.
4. Run the notebook cells sequentially.

### Option 2 — Local Jupyter Notebook

Clone the repository:

```bash
git clone https://github.com/Meghnaprabhu24/Stats_Lab.git
cd Stats_Lab
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the required experiment notebook and run the cells sequentially.

---

## 📁 Repository Structure

```text
Stats_Lab/
│
├── Exp1.ipynb
├── Stats_Experiment_No_2.ipynb
├── Stats_Experiment_No_3.ipynb
├── Stats_Experiment_No_4.ipynb
├── Stats_Experiment_No_5.ipynb
├── Stats_Experiment_No_6.ipynb
├── Stats_Experiment_No_7.ipynb
├── Stats_Experiment_No_8.ipynb
└── README.md
```

---

## 📊 About the Pima Indians Diabetes Dataset

The **Pima Indians Diabetes Dataset** is a commonly used dataset for studying statistical analysis and machine learning classification. It contains medical diagnostic measurements along with a binary diabetes outcome.

In this repository, the dataset provides a common foundation for applying statistical concepts progressively—from basic data exploration and descriptive statistics to inference, regression, classification, dimensionality reduction, and clustering.

---

## 🎯 Learning Objectives

By completing these experiments, you can understand how statistical concepts are applied to a real-world dataset and gain practical experience with:

1. Exploring and summarizing datasets.
2. Preparing data for statistical analysis.
3. Applying statistical measures and inference techniques.
4. Estimating uncertainty using confidence intervals and bootstrap methods.
5. Building and interpreting regression models.
6. Applying classification algorithms.
7. Evaluating model predictions.
8. Reducing dimensionality using PCA.
9. Applying clustering techniques to structured data.
10. Visualizing and interpreting analytical results.

---

## ⚠️ Disclaimer

This repository is intended for **academic and educational purposes**. The analyses performed on the Pima Indians Diabetes Dataset should not be interpreted as medical diagnosis or clinical advice.

---

## 👩‍💻 Author

**Meghna Prabhu**

GitHub: [@Meghnaprabhu24](https://github.com/Meghnaprabhu24)

---

⭐ If you find this repository useful, consider giving it a star!
