::: {align="center"}
# 🚀 DevSphere Week 6 --- AI & Machine Learning Projects

`<img src="assets/devsphere_animated_banner.gif" alt="Animated DevSphere AI and Machine Learning banner" width="100%">`{=html}

### Intelligent Systems • Predictive Modeling • Data Visualization

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![AI](https://img.shields.io/badge/Domain-Artificial%20Intelligence-7C3AED)](#-project-1-ai-student-success-prediction--recommendation-system)
[![ML](https://img.shields.io/badge/Domain-Machine%20Learning-0F766E)](#-project-2-house-price-prediction-system)
[![Program](https://img.shields.io/badge/Program-DevSphere%20Internship-2563EB)](#-internship-information)
:::

------------------------------------------------------------------------

## 📌 About This Repository

This repository contains the two projects prepared for **Week 6 of the
DevSphere Internship Program** in Artificial Intelligence and Machine
Learning. Each project demonstrates a practical prediction workflow:
preparing data, training models, evaluating results, visualizing model
behavior, and accepting user input for predictions.

The repository is organized into separate folders so that the AI and ML
projects can be explored and run independently.

> **Dataset note:** The included datasets are synthetically generated
> for educational and demonstration purposes. Their results should not
> be interpreted as validated real-world student outcomes or real-estate
> valuations.

## 🗂️ Repository Structure

``` text
DevSphere_Week6_AI_ML_Projects/
├── README.md
├── requirements.txt
├── assets/
│   └── devsphere_animated_banner.gif
├── docs/
│   ├── Week_6_AI_ML_Project_Report.docx
│   └── Week_6_AI_ML_Project_Report.pdf
├── AI_Student_Success_Prediction/
│   ├── ai_student_success.py
│   ├── data/
│   │   └── student_performance_week6.csv
│   └── notebooks/
│       └── AI_Student_Success_Prediction.ipynb
└── ML_House_Price_Prediction/
    ├── house_price_prediction.py
    ├── data/
    │   └── house_prices_week6.csv
    └── notebooks/
        └── ML_House_Price_Prediction.ipynb
```

*The structure above describes the intended repository layout. Keep the
paths in sync if you rename or move files.*

------------------------------------------------------------------------

## 🧠 Project 1: AI Student Success Prediction & Recommendation System

### Objective

Build an educational AI demonstration that estimates whether a student
is likely to pass using study and performance-related inputs, then
provides simple study recommendations based on the supplied values.

### Main Features

-   Synthetic student dataset generation and CSV export.
-   Missing-value handling and train/test split.
-   Classification models, including Logistic Regression, Decision Tree,
    Random Forest, and an MLP neural network.
-   Random Forest hyperparameter search with cross-validation.
-   Classification evaluation using accuracy, precision, recall, and
    F1-score.
-   Visualizations for model comparison, confusion matrix, feature
    importance, and prediction probabilities.
-   Interactive user input for study hours, attendance, and previous
    score.
-   Rule-based study recommendations and export of a prediction result.

### Input Features

  Feature           Meaning
  ----------------- --------------------------------------------------
  `StudyHours`      Study hours represented in the generated dataset
  `Attendance`      Attendance percentage
  `PreviousScore`   Previous score used by the demonstration
  `Passed`          Synthetic target label used for classification

### How It Works

1.  Generate and inspect the synthetic dataset.
2.  Prepare features and target, handle missing values, and split the
    data.
3.  Train and evaluate classification models.
4.  Compare model metrics and tune the Random Forest model.
5.  Visualize evaluation results.
6.  Enter student values to obtain a prediction and recommendations.

**Project files**

-   Python script: `AI_Student_Success_Prediction/ai_student_success.py`
-   Notebook:
    `AI_Student_Success_Prediction/notebooks/AI_Student_Success_Prediction.ipynb`
-   Dataset:
    `AI_Student_Success_Prediction/data/student_performance_week6.csv`

------------------------------------------------------------------------

## 🏠 Project 2: Machine Learning House Price Prediction System

### Objective

Build a regression project that estimates a house price from
property-related inputs using several machine learning models, then
compares their performance on a held-out test set.

### Main Features

-   Synthetic housing dataset generation and CSV export.
-   Data inspection, duplicate handling, missing-value imputation, and
    train/test split.
-   Linear Regression, Decision Tree Regressor, and Random Forest
    Regressor.
-   Evaluation using MAE, MSE, RMSE, and R².
-   Model comparison and selection based on test RMSE.
-   Visualizations for model error, actual-versus-predicted prices, and
    feature relationships or importance.
-   Interactive user input for property details.
-   Export of model evaluation and prediction results.

### Input Features

  Feature         Meaning
  --------------- --------------------------------------------
  `Area_sqft`     Property area in square feet
  `Bedrooms`      Number of bedrooms
  `Bathrooms`     Number of bathrooms
  `HouseAge`      House age used by the generated dataset
  `Distance_km`   Distance feature used by the demonstration
  `Price`         Synthetic target price

### How It Works

1.  Generate and inspect the synthetic housing dataset.
2.  Clean the data and prepare the feature and target columns.
3.  Train regression models using a training split.
4.  Evaluate the models on the test split and compare the metrics.
5.  Plot the evaluation results and actual-versus-predicted values.
6.  Enter property details to receive a model-generated price estimate.

**Project files**

-   Python script: `ML_House_Price_Prediction/house_price_prediction.py`
-   Notebook:
    `ML_House_Price_Prediction/notebooks/ML_House_Price_Prediction.ipynb`
-   Dataset: `ML_House_Price_Prediction/data/house_prices_week6.csv`

> **Important limitation:** This house-price model learns from a
> synthetic formula, not verified market transactions. Its predictions
> are for demonstrating a machine learning workflow and must not be used
> as professional property valuations.

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   **Language:** Python
-   **Data handling:** Pandas, NumPy
-   **Machine learning:** scikit-learn
-   **Visualization:** Matplotlib, Seaborn
-   **Notebook environment:** Google Colab or Jupyter Notebook
-   **Version control:** Git and GitHub

The notebooks are suitable for Google Colab. The Python scripts can be
run locally after installing the required packages.

## ⚙️ Setup and Installation

### 1. Clone the repository

Replace `YOUR_GITHUB_USERNAME` with your GitHub username after
publishing the repository.

``` bash
git clone https://github.com/YOUR_GITHUB_USERNAME/DevSphere_Week6_AI_ML_Projects.git
cd DevSphere_Week6_AI_ML_Projects
```

### 2. Create and activate a virtual environment (optional)

``` bash
python -m venv .venv
```

**Windows**

``` bash
.venv\Scripts\activate
```

**macOS / Linux**

``` bash
source .venv/bin/activate
```

### 3. Install dependencies

``` bash
pip install -r requirements.txt
```

If a `requirements.txt` file is not included in your repository, install
the packages used by the code:

``` bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 4. Run a project

From the repository root, run either script:

``` bash
python AI_Student_Success_Prediction/ai_student_success.py
```

``` bash
python ML_House_Price_Prediction/house_price_prediction.py
```

The scripts may prompt for input in the terminal. Run each project
separately and follow the prompts. In Google Colab, open the relevant
`.ipynb` notebook and execute the cells in order.

## 📊 Outputs and Generated Files

Depending on the code version and the cells executed, project runs can
generate datasets, model evaluation tables, plots, and user-prediction
CSV files. Check the output paths printed by the script or notebook. Do
not add claims about specific performance scores to this README unless
they have been verified from an actual run.

For your internship submission, you can add screenshots of: - Dataset
preview and preprocessing. - Model training and evaluation. - Graphs and
visualizations. - A sample interactive prediction. - Final saved output
files.

Only add genuine screenshots and measured results from your own
execution.

## 📄 Project Report

The combined Week 6 report is intended to document both projects, their
methods, code, and spaces for actual execution screenshots.

-   Word report: `docs/Week_6_AI_ML_Project_Report.docx`
-   PDF report: `docs/Week_6_AI_ML_Project_Report.pdf`

If these report files are not present in the GitHub repository, add them
to the `docs/` folder or update these links to match the files you
upload.

------------------------------------------------------------------------

## 👨‍💻 Developer

**Saud Masood**\
**BS Computer Science (BSCS) Graduate**\
**Flutter Developer \| AI/ML Engineer**

📧 **Email:** <saudmasood974@gmail.com>

### Internship Information

-   **Program:** DevSphere Internship Program
-   **Domain:** Artificial Intelligence & Machine Learning
-   **Submission:** Week 6 --- AI and ML projects

## 🎯 Learning Outcomes

Through these projects, the work demonstrates practice with:

-   Data preparation and missing-value handling.
-   Classification and regression workflows.
-   Neural-network classification concepts.
-   Model comparison and evaluation metrics.
-   Cross-validation and hyperparameter tuning.
-   Data visualization and user-input predictions.
-   Organizing Python scripts, datasets, and notebooks in a GitHub
    repository.

## ⚠️ Disclaimer

These projects are educational demonstrations. The datasets are
synthetic, and model quality on synthetic data does not establish
real-world reliability. Student predictions are not definitive
assessments of a person's potential, and house-price estimates are not
financial or property advice.

------------------------------------------------------------------------

::: {align="center"}
**Built by Saud Masood**\
*DevSphere Internship Program · Week 6 · AI & Machine Learning*
:::
