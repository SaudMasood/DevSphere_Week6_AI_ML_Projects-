 <div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,40:1D4ED8,100:7C3AED&text=DevSphere%20Week%206&fontSize=42&fontColor=FFFFFF&fontAlignY=38&desc=Artificial%20Intelligence%20%26%20Machine%20Learning&descAlignY=60&descSize=17" width="100%" alt="DevSphere Week 6 animated banner"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=850&lines=Welcome+to+my+AI%2FML+Projects;Student+Success+Prediction+System;House+Price+Prediction+System;Learning+Machine+Learning+by+Building" alt="Animated introduction"/>

<p>
<img src="https://img.shields.io/badge/Program-DevSphere%20Internship-2563EB?style=for-the-badge" alt="Internship"/>
<img src="https://img.shields.io/badge/Week-06-7C3AED?style=for-the-badge" alt="Week 6"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Artificial%20Intelligence-9333EA?style=for-the-badge" alt="Artificial Intelligence"/>
<img src="https://img.shields.io/badge/Machine%20Learning-0F766E?style=for-the-badge" alt="Machine Learning"/>
</p>

**Saud Masood**  
BSCS Graduate | Flutter Developer | AI/ML Engineer

[Contact Me](mailto:saudmasood974@gmail.com)

</div>

---

## 📌 About This Repository

Welcome to my **DevSphere Internship Program — Week 6: Artificial Intelligence and Machine Learning Projects** repository.

This repository brings together two predictive projects implemented with Python and machine learning concepts:

1. **AI Student Success Prediction & Recommendation System**
2. **Machine Learning House Price Prediction System**

The projects demonstrate a complete educational workflow covering dataset preparation, data preprocessing, model training, evaluation, visualization, and interactive predictions.

The repository also includes CSV datasets, prediction results, model evaluation results, project documentation, and a notebook or code file for the combined Week 6 work.

### 🎯 Objectives

- Practice data cleaning and preprocessing.
- Implement classification and regression algorithms.
- Explore neural-network concepts.
- Compare models using suitable evaluation metrics.
- Visualize model performance and predictions.
- Accept user input for predictions.
- Export datasets and results to CSV files.
- Document and organize project work on GitHub.

> **Data transparency:** The student and house-price datasets are synthetic. They are intended for learning and demonstration, not as verified real-world data.

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [AI Project](#-project-1-ai-student-success-prediction--recommendation-system)
- [Machine Learning Project](#-project-2-house-price-prediction-system)
- [Repository Files](#-repository-files)
- [Technology Stack](#-technology-stack)
- [Installation](#-installation-and-setup)
- [Execution Guide](#-execution-guide)
- [Google Colab](#-google-colab)
- [Evaluation Metrics](#-evaluation-metrics)
- [Generated Results](#-generated-results)
- [Learning Outcomes](#-learning-outcomes)
- [Developer Profile](#-developer-profile)
- [Disclaimer](#-disclaimer)

---

## 🔍 Project Overview

| Project | Machine Learning Task | Main Goal |
|---|---|---|
| AI Student Success Prediction & Recommendation System | Classification | Predict a synthetic student pass/fail outcome and offer study recommendations |
| House Price Prediction System | Regression | Estimate a synthetic house price from property features |

The projects use separate datasets and prediction workflows but are documented together in one GitHub repository.

---

## 🧠 Project 1: AI Student Success Prediction & Recommendation System

### 1. Project Description

The AI Student Success Prediction & Recommendation System is an educational classification project that estimates whether a student is likely to pass based on selected academic features.

The project combines data preprocessing, classification algorithms, an MLP neural network, model evaluation, visualizations, and user-input predictions.

The system uses a trained classifier to produce a prediction for supplied student information. It can also provide basic rule-based recommendations intended to encourage better study habits.

### 2. Main Features

- Synthetic student dataset generation.
- Missing-value handling.
- Training and testing data separation.
- Logistic Regression classifier.
- Decision Tree classifier.
- Random Forest classifier.
- MLP neural-network classifier.
- Random Forest hyperparameter tuning using `GridSearchCV`.
- Accuracy, precision, recall, and F1-score evaluation.
- Confusion matrix visualization.
- Model comparison charts.
- Feature importance visualization.
- Interactive student input.
- Pass/fail prediction and study recommendations.
- CSV output for student predictions.

### 3. Dataset Description

The student dataset uses the following main columns:

| Feature | Description |
|---|---|
| `StudyHours` | Study hours represented in the generated dataset |
| `Attendance` | Attendance percentage |
| `PreviousScore` | Previous academic score |
| `Passed` | Synthetic target label indicating pass or fail |

The dataset is generated for educational use and includes missing feature values for preprocessing practice.

### 4. AI Workflow

```text
Student Dataset
      ↓
Data Inspection
      ↓
Missing-Value Handling and Preprocessing
      ↓
Train/Test Split
      ↓
Classification Models
      ↓
Model Evaluation and Tuning
      ↓
Visualizations
      ↓
User Input
      ↓
Pass/Fail Prediction
      ↓
Study Recommendations and CSV Output
```

### 5. Expected Project Artifacts

- Student performance dataset.
- Trained classification models.
- Classification evaluation metrics.
- Confusion matrix and model comparison charts.
- Interactive prediction workflow.
- Saved prediction results.

The actual performance values should be taken from the executed notebook or generated evaluation files.

---

## 🏠 Project 2: Machine Learning House Price Prediction System

### 1. Project Description

The House Price Prediction System is a regression project that estimates a house price using property-related input features.

It demonstrates dataset preparation, missing-value imputation, regression model training, model comparison, evaluation, visualization, and interactive price estimation.

The included dataset is synthetically generated, so its predictions demonstrate the workflow rather than actual housing-market conditions.

### 2. Main Features

- Synthetic house-price dataset generation.
- Data inspection and duplicate handling.
- Missing-value imputation.
- Train/test splitting.
- Linear Regression.
- Decision Tree Regressor.
- Random Forest Regressor.
- Comparison of regression models.
- MAE, MSE, RMSE, and R² evaluation.
- Actual-versus-predicted visualization.
- Feature importance or coefficient visualization.
- Correlation heatmap.
- Interactive property inputs.
- CSV export of evaluation and prediction results.

### 3. Dataset Description

| Feature | Description |
|---|---|
| `Area_sqft` | Property area in square feet |
| `Bedrooms` | Number of bedrooms |
| `Bathrooms` | Number of bathrooms |
| `HouseAge` | House age represented in the dataset |
| `Distance_km` | Distance feature used in the dataset |
| `Price` | Synthetic target price |

### 4. ML Workflow

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
Evaluation and Model Comparison
      ↓
Visualization
      ↓
User Input
      ↓
House Price Estimate
      ↓
Prediction and Evaluation CSV Files
```

### 5. Evaluation

The regression workflow uses:

- **MAE — Mean Absolute Error:** Average absolute difference between actual and predicted values.
- **MSE — Mean Squared Error:** Average squared prediction error.
- **RMSE — Root Mean Squared Error:** Square root of MSE.
- **R² — Coefficient of Determination:** Measures model performance relative to a baseline based on the target mean.

The implemented workflow selects a model using test-set RMSE.

> **Important:** A low error on synthetic data does not prove that the model can accurately estimate real property prices.

---

## 📂 Repository Files

The following files are visible in the repository screenshot.

| File | Purpose |
|---|---|
| `README.md` | Main project documentation |
| `LICENSE` | Repository license |
| `devsphere_animated_banner.gif` | Animated banner asset |
| `house_prices_week6.csv` | Synthetic house-price dataset |
| `house_price_prediction_result.csv` | House price prediction output |
| `model_evaluation_results.csv` | Model evaluation results |
| `student_performance_week6.csv` | Synthetic student performance dataset |
| `student_prediction_result.csv` | Student prediction output |
| `week_6_artificial_intelligence_and_machine_lea...` | Combined Week 6 notebook or code file; verify the complete filename and extension |
| `Saud_Masood_DevSphere_Week_6_AI_ML_Final...` | Project report file; verify the complete filename and extension |

The last two names are shortened because GitHub truncates long filenames in the screenshot. Confirm their full names before creating direct links.

### 📊 Dataset and Results Summary

| File | Project | Role |
|---|---|---|
| `student_performance_week6.csv` | AI | Student input features and synthetic target |
| `student_prediction_result.csv` | AI | Saved student prediction |
| `house_prices_week6.csv` | ML | Property features and synthetic target price |
| `house_price_prediction_result.csv` | ML | Saved house price estimate |
| `model_evaluation_results.csv` | ML or combined evaluation | Saved evaluation data; verify its columns to confirm the exact contents |

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
| Python | Project implementation |
| Pandas | Data loading, manipulation, and preparation |
| NumPy | Numerical operations and synthetic data generation |
| Scikit-learn | Preprocessing, model training, tuning, and evaluation |
| Matplotlib | Charts and plotting |
| Seaborn | Statistical visualization and correlation analysis |
| Google Colab | Cloud notebook execution |
| Git and GitHub | Version control and repository hosting |

---

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/DevSphere_Week6_AI_ML_Projects.git
cd DevSphere_Week6_AI_ML_Projects
```

### Step 2: Install Dependencies

If your repository contains a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install the primary libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Step 3: Check Python

```bash
python --version
```

Use a Python version compatible with your installed dependencies.

---

## ▶️ Execution Guide

Your screenshot shows a combined Week 6 notebook or code file in the repository root, but its full name and extension are truncated. Open that file on GitHub to confirm how it should be executed.

### If the project is a Jupyter notebook

1. Download the `.ipynb` file.
2. Open Google Colab or Jupyter Notebook.
3. Upload or open the notebook.
4. Install any missing dependencies.
5. Execute the cells in order.
6. Review the printed evaluation metrics and charts.
7. Enter input values when prompted.
8. Save the generated CSV files if required.

### If the project is a Python script

Run the script using the Python interpreter:

```bash
python your_actual_filename.py
```

Replace `your_actual_filename.py` with the real filename in your repository.

**Important:** The command and execution method depend on the actual extension of the uploaded code file.

---

## ☁️ Google Colab

Google Colab can be used to run the notebook without setting up a local Python environment.

Recommended workflow:

1. Open the notebook from your GitHub repository.
2. Download it or upload it to Google Colab.
3. Install any required dependencies.
4. Verify that the dataset paths are correct.
5. Run all cells in sequence.
6. Review the model evaluation outputs.
7. Inspect the generated charts.
8. Test the interactive prediction sections.
9. Download the generated CSV outputs for your report.

If the notebook generates its own synthetic dataset, execute the dataset-generation cells before model training. If it expects existing CSV files, upload them or adjust the paths accordingly.

---

## 📈 Evaluation Metrics

### AI Classification

| Metric | Explanation |
|---|---|
| Accuracy | Proportion of correct predictions |
| Precision | Proportion of positive predictions that are correct |
| Recall | Proportion of actual positive cases identified |
| F1-score | Harmonic mean of precision and recall |
| Confusion matrix | Counts of correct and incorrect predictions by class |

### ML Regression

| Metric | Explanation |
|---|---|
| MAE | Average absolute prediction error |
| MSE | Average squared prediction error |
| RMSE | Square root of mean squared error |
| R² | Model fit relative to a baseline based on the target mean |

No numerical model-performance claims are included here. Use the values produced by your actual execution.

---

## 📊 Generated Results

The repository currently shows these CSV artifacts:

- `student_performance_week6.csv`
- `student_prediction_result.csv`
- `house_prices_week6.csv`
- `house_price_prediction_result.csv`
- `model_evaluation_results.csv`

These files allow you to inspect the generated data, prediction records, and evaluation results.

For a professional submission, verify the column names and values in each CSV. Include screenshots of the actual dataset preview, evaluation metrics, plots, and sample predictions if your internship requires evidence of execution.

---

## 📚 Learning Outcomes

Through these projects, I have worked with or demonstrated the following concepts:

- Data preprocessing and missing-value imputation.
- Classification and regression workflows.
- Neural-network classification concepts using an MLP.
- Training/test data separation.
- Cross-validation and hyperparameter tuning.
- Model evaluation and comparison.
- Data visualization and result interpretation.
- Interactive prediction workflows.
- CSV-based data and result management.
- Notebook development and GitHub project documentation.

---

## 👨‍💻 Developer Profile

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=7C3AED&center=true&vCenter=true&width=650&lines=Saud+Masood;BSCS+Graduate;Flutter+Developer;AI%2FML+Engineer" alt="Animated developer profile"/>

### Saud Masood

**BS Computer Science (BSCS) Graduate**

**Flutter Developer | AI/ML Engineer**

📧 **Email:** [saudmasood974@gmail.com](mailto:saudmasood974@gmail.com)

**Program:** DevSphere Internship Program  
**Domain:** Artificial Intelligence & Machine Learning  
**Submission:** Week 6 — AI and ML Projects

</div>

---

## ⚠️ Disclaimer

These projects are educational demonstrations.

- The student dataset is synthetic and cannot reliably determine an actual student's future success.
- The house-price dataset is synthetic and does not represent verified property-market data.
- Results on synthetic data do not establish real-world accuracy or reliability.
- House-price predictions should not be used for financial decisions or professional valuations.
- Always verify metrics and predictions from the actual executed code before reporting results.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:1D4ED8,100:020617&height=140&section=footer" width="100%" alt="Decorative footer banner"/>

**Built by Saud Masood**

*DevSphere Internship Program · Week 6 · Artificial Intelligence & Machine Learning*

**Learn • Build • Evaluate • Improve**

</div>
