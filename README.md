# Machine Learning Laboratory - Project Assignment 2 🌳🧠

Welcome to the repository for **Project Assignment 2** of the **Machine Learning Laboratory** course! This project was completed as part of our coursework at **Hacettepe University** during the **Spring 2025** semester. 🚀  

## Project Overview 📝

This assignment focuses on implementing a **Decision Tree** classifier on a structured dataset that contains financial information of individuals. We applied a full **machine learning pipeline** starting from data preprocessing and missing value imputation, all the way to model training and performance evaluation.

The notebook is divided into several key parts, each handling a specific aspect of the pipeline:

- **Handling Missing Values**: Using **median imputation** for numerical features (e.g., Income, Credit Score, Loan Amount, Assets Value).
- **Categorical Data Analysis**: Checked and confirmed no missing values in categorical fields.
- **Exploratory Data Analysis**: Understanding the distribution of key features.
- **Model Implementation**: Trained a **Decision Tree** classifier from scratch and evaluated performance.

---

## Key Features 🌟

- **Dataset**: A financial dataset with both numerical and categorical variables. Some fields include:
  - Income
  - Credit Score
  - Loan Amount
  - Assets Value
  - Number of Dependents
  - Previous Defaults
  - Gender, Education Level, Marital Status, Loan Purpose, Employment Status, etc.
- **Missing Value Handling**:
  - Median imputation for continuous features.
  - Special strategy planning for discrete features like `Number of Dependents` and `Previous Defaults`.
- **Model**:
  - Decision Tree Classifier implemented and evaluated using standard metrics.
- **Tools & Libraries**:
  - Python 3.9.6
  - Pandas, NumPy
  - Scikit-learn
  - Matplotlib / Seaborn (for visualization)

---

## Repository Structure 🗂️

- `assignment2.ipynb`: Main Jupyter Notebook containing all the code, data analysis, and model implementation.
- `README.md`: This file, providing an overview of the project and instructions.

---

## How to Run the Project 🛠️

### 1. Clone the Repository:
```bash
git clone https://github.com/merttcetn/ML-PA2.git
cd ML-PA2
```

### 2. Install Dependencies:
Make sure you're using Python 3.9.6, then install the required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

Open `assignment2.ipynb` and run each cell step-by-step to see the data analysis and results.

---

## Results 📈

- Numerical missing values were successfully handled using median imputation.
- Categorical fields were verified to be complete.
- The Decision Tree classifier was trained and evaluated on the cleaned dataset.
- Evaluation metrics such as **accuracy**, **precision**, **recall**, and **F1-score** were used to assess performance.
- Visualizations and summaries provided insight into model behavior and data characteristics.

---

## 📌 Note

This project is part of a **school assignment** and is intended for **educational purposes only**.
