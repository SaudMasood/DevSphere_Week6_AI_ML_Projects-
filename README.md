 <div align="center">
<img src=<p>
"https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=850&lines=Welcome+to+my+Week+6+AI%2FML+Projects;Student+Success+Prediction+System;House+Price+Prediction+System;Building+Intelligent+Solutions+with+Python" alt="Animated project introduction"/>


<p>
<img src="https://img.shields.io/badge/Program-DevSphere%20Internship-2563EB?style=for-the-badge" alt="DevSphere"/>
<img src="https://img.shields.io/badge/Week-06-7C3AED?style=for-the-badge" alt="Week 6"/>
<img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/AI-Artificial%20Intelligence-9333EA?style=for-the-badge" alt="AI"/>
<img src="https://img.shields.io/badge/ML-Machine%20Learning-0F766E?style=for-the-badge" alt="ML"/>
</p>

**Developed by Saud Masood | BSCS Graduate | Flutter Developer | AI/ML Engineer**

</div>

---

## 📌 About the Repository

Welcome to my **DevSphere Internship — Week 6: Artificial Intelligence and Machine Learning** repository.

This repository contains two Python-based predictive projects developed to demonstrate practical machine learning workflows, including dataset preparation, preprocessing, model training, evaluation, visualization, and user-input predictions.

The projects are maintained in a single repository, with their datasets, prediction outputs, evaluation results, notebook, and report files available in the repository root as shown in the current repository structure.

### 🎯 Project Objectives

- Apply data preprocessing and missing-value handling.
- Implement classification and regression algorithms.
- Explore neural-network concepts through an MLP classifier.
- Compare machine learning models using appropriate evaluation metrics.
- Perform model tuning and evaluate model performance.
- Visualize results using charts and graphs.
- Accept user input to generate predictions.
- Save relevant datasets and results in CSV format.
- Document the work professionally using GitHub and project reports.

> **Dataset disclaimer:** The student and house-price datasets used in these projects are synthetic datasets generated for educational purposes. They are not verified real-world records.

---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)
2. [AI Project — Student Success Prediction](#-project-1-ai-student-success-prediction--recommendation-system)
3. [ML Project — House Price Prediction](#-project-2-machine-learning-house-price-prediction-system)
4. [Repository Files](#-repository-files)
5. [Technology Stack](#-technology-stack)
6. [Installation and Setup](#-installation-and-setup)
7. [Running the Projects](#-running-the-projects)
8. [Google Colab Instructions](#-google-colab-instructions)
9. [Evaluation Metrics](#-evaluation-metrics)
10. [Output Files](#-output-files)
11. [Developer Profile](#-developer-profile)
12. [Disclaimer](#-disclaimer)

---

## 🔍 Project Overview

| Project | Category | Main Purpose |
|---|---|---|
| AI Student Success Prediction & Recommendation System | Classification and neural-network concepts | Predict a synthetic pass/fail outcome and provide study recommendations |
| House Price Prediction System | Regression | Estimate a synthetic house price from property features |

Both projects demonstrate the process of preparing data, training models, evaluating results, and using trained models to make predictions from new inputs.

---

## 🧠 Project 1: AI Student Success Prediction & Recommendation System

### 📖 Description

The AI Student Success Prediction & Recommendation System is an educational classification project that estimates whether a student is likely to pass based on selected academic features.

The system combines data preprocessing, multiple classification models, an MLP neural network, model evaluation, visualizations, and an interactive prediction workflow.

After the user enters student information, the trained model predicts a class and the application provides simple rule-based study recommendations.

### ✨ Key Features

- Synthetic student dataset generation.
- Missing-value handling and feature preprocessing.
- Training and testing data separation.
- Logistic Regression classification.
- Decision Tree classification.
- Random Forest classification.
- MLP neural-network classification.
- Random Forest hyperparameter tuning using `GridSearchCV`.
- Classification metrics and confusion matrix.
- Model performance visualizations.
- Interactive student input and prediction.
- Rule-based study recommendations.
- CSV export of generated data and prediction results.

### 📊 Dataset Description

The student dataset contains these main columns:

| Column | Description |
|---|---|
| `StudyHours` | Study hours represented in the dataset |
| `Attendance` | Student attendance percentage |
| `PreviousScore` | Previous academic score |
| `Passed` | Synthetic target label indicating pass or fail |

The dataset is generated programmatically and includes missing feature values for preprocessing practice.

### ⚙️ Workflow

```text
Student Dataset
      ↓
Data Inspection and Preprocessing
      ↓
Train/Test Split
      ↓
Classification Model Training
      ↓
Model Evaluation and Tuning
      ↓
Performance Visualizations
      ↓
User Input
      ↓
Pass/Fail Prediction
      ↓
Study Recommendations and CSV Output
```

### 📈 Evaluation

The classification models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

These metrics help compare model performance on the held-out test data.

---

## 🏠 Project 2: Machine Learning House Price Prediction System

### 📖 Description

The House Price Prediction System is a regression project that estimates the price of a house using property-related input features.

It demonstrates data preparation, regression model training, model comparison, evaluation, visualization, and interactive price prediction.

The included dataset is generated using a synthetic pricing formula and is intended to demonstrate the machine learning workflow.

### ✨ Key Features

- Synthetic house-price dataset generation.
- Data cleaning and duplicate handling.
- Missing-value imputation.
- Train/test data splitting.
- Linear Regression.
- Decision Tree Regressor.
- Random Forest Regressor.
- Comparison of regression model performance.
- MAE, MSE, RMSE, and R² evaluation.
- Actual-versus-predicted visualization.
- Feature importance or coefficient visualization.
- Correlation heatmap.
- Interactive property inputs.
- CSV export of model evaluation and prediction results.

### 📊 Dataset Description

| Column | Description |
|---|---|
| `Area_sqft` | Property area in square feet |
| `Bedrooms` | Number of bedrooms |
| `Bathrooms` | Number of bathrooms |
| `HouseAge` | House age used by the dataset |
| `Distance_km` | Distance feature used by the dataset |
| `Price` | Synthetic target price |

### ⚙️ Workflow

```text
House Price Dataset
      ↓
Data Inspection and Cleaning
      ↓
Missing-Value Imputation
      ↓
Train/Test Split
      ↓
Regression Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Visualizations
      ↓
User Input
      ↓
House Price Estimate
      ↓
CSV Output
```

### 📈 Evaluation

The regression models are evaluated using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R²:** Coefficient of Determination

The implemented workflow selects a model based on test-set RMSE.

> **Important:** Predictions are based on synthetic data and must not be treated as real estate valuations.

---

## 📂 Repository Files

The following files are visible in the current repository screenshot.

| File | Purpose |
|---|---|
| `README.md` | Project documentation |
| `LICENSE` | Repository license |
| `devsphere_animated_banner.gif` | Animated banner asset |
| `house_prices_week6.csv` | Synthetic house-price dataset |
| `house_price_prediction_result.csv` | House price prediction output |
| `model_evaluation_results.csv` | Model evaluation results |
| `student_performance_week6.csv` | Synthetic student performance dataset |
| `student_prediction_result.csv` | Student prediction output |
| `week_6_artificial_intelligence_and_machine_learning...` | Combined project notebook or related file; confirm the complete filename on GitHub |
| `Saud_Masood_DevSphere_Week_6_AI_ML_Final...` | Uploaded project report file; confirm whether it is the Word or PDF version |

**Note:** The screenshot shows truncated filenames for the report and notebook. Their exact extensions and full filenames should be confirmed in GitHub before linking to them.

### 🗂️ Logical Project Organization

For clarity, the repository content represents these two project areas:

```text
DevSphere_Week6_AI_ML_Projects/
│
├── README.md
├── LICENSE
├── devsphere_animated_banner.gif
│
├── AI Student Success Prediction
│   ├── Student performance dataset
│   ├── Student prediction results
│   └── AI classification notebook/code
│
├── ML House Price Prediction
│   ├── House prices dataset
│   ├── House price prediction results
│   ├── Model evaluation results
│   └── ML regression notebook/code
│
└── Project Reports
    ├── Word report
    └── PDF report
```

This is a logical grouping for documentation, not a claim that the repository currently contains those subfolders.

---

## 🛠️ Technology Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib"/>
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn"/>
<img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
</p>

| Technology | Purpose |
|---|---|
| Python | Implementation of AI and ML workflows |
| Pandas | Data handling and preprocessing |
| NumPy | Numerical operations and synthetic data generation |
| Scikit-learn | Model training, preprocessing, tuning, and evaluation |
| Matplotlib | Visualization and plotting |
| Seaborn | Statistical charts and correlation visualization |
| Google Colab | Cloud-based notebook execution |
| Git and GitHub | Version control and repository hosting |

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

Replace `YOUR_GITHUB_USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/DevSphere_Week6_AI_ML_Projects.git
cd DevSphere_Week6_AI_ML_Projects
```

### 2. Install Dependencies

If the repository contains `requirements.txt`:

```bash
pip install -r requirements.txt
```

Otherwise, install the main libraries used by these projects:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Check Python

```bash
python --version
```

Use a Python version supported by the installed dependencies.

---

## ▶️ Running the Projects

The exact execution commands depend on the locations and names of your uploaded Python files.

If you organize the Python scripts into the following paths, use these commands:

**AI project**

```bash
python AI_Student_Success_Prediction/ai_student_success.py
```

**ML project**

```bash
python ML_House_Price_Prediction/house_price_prediction.py
```

If the code currently exists only in the combined notebook, open that notebook in Google Colab or Jupyter and execute its cells in order.

---

## ☁️ Google Colab Instructions

1. Open the repository on GitHub.
2. Locate the combined Week 6 notebook.
3. Download the `.ipynb` file or open it in Google Colab.
4. Install any missing dependencies.
5. Run each cell from top to bottom.
6. Review the model evaluation metrics and generated charts.
7. Enter values when the interactive prediction code prompts you.
8. Download the generated CSV results if required for submission.

If a notebook expects a local CSV path, verify that the dataset is available in Colab or modify the notebook to generate or upload the dataset before running the relevant cells.

---

## 📊 Output Files

The repository screenshot shows these CSV files:

| Output file | Purpose |
|---|---|
| `student_performance_week6.csv` | Student dataset used for the AI project |
| `student_prediction_result.csv` | Saved student prediction result |
| `house_prices_week6.csv` | House-price dataset used for the ML project |
| `house_price_prediction_result.csv` | Saved house price prediction result |
| `model_evaluation_results.csv` | Model evaluation results |

Use the actual CSV contents to report numerical results. Do not assume a particular accuracy, F1-score, RMSE, or R² without checking the generated files.

---

## 📚 Learning Outcomes

This Week 6 work demonstrates practice with:

- Data preprocessing and missing-value imputation.
- Classification and regression models.
- Neural-network classification concepts.
- Training/testing data separation.
- Hyperparameter tuning with cross-validation.
- Model evaluation and comparison.
- Data visualization.
- Interactive prediction workflows.
- CSV data and result management.
- Python notebook development and GitHub documentation.

---

## 👨‍💻 Developer Profile

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=7C3AED&center=true&vCenter=true&width=650&lines=Saud+Masood;BSCS+Graduate;Flutter+Developer;AI%2FML+Engineer" alt="Animated developer profile"/>

### Saud Masood

**BS Computer Science (BSCS) Graduate**

**Flutter Developer | AI/ML Engineer**

📧 **Email:** [saudmasood974@gmail.com](mailto:saudmasood974@gmail.com)

**Internship:** DevSphere Internship Program  
**Domain:** Artificial Intelligence & Machine Learning  
**Submission:** Week 6 — AI and ML Projects

</div>

---

## ⚠️ Disclaimer

These projects are intended for educational and internship demonstration purposes.

- The student dataset is synthetic and cannot reliably determine a real student's future success.
- The house-price dataset is synthetic and does not represent verified real estate market data.
- Model performance on generated data does not establish real-world accuracy.
- Predictions should not be used as the basis for high-stakes educational, financial, or property decisions.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:1D4ED8,100:020617&height=130&section=footer" width="100%" alt="Decorative footer banner"/>

**Built by Saud Masood**

*DevSphere Internship Program · Week 6 · AI & Machine Learning*

**Learn • Build • Evaluate • Improve**

</div>
