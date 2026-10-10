 <div align="center">

# 🚀 DevSphere Week 6 — AI & Machine Learning Projects

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:1D4ED8,100:7C3AED&text=AI%20%26%20Machine%20Learning&fontSize=35&fontColor=FFFFFF&fontAlignY=38&desc=Intelligent%20Systems%20%7C%20Predictive%20Analytics%20%7C%20Data%20Science&descAlignY=58&descSize=15" width="100%" alt="Animated AI and Machine Learning header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&pause=1000&color=38BDF8&center=true&vCenter=true&width=800&lines=Welcome+to+my+Week+6+Internship+Projects!;Building+Intelligent+Prediction+Systems;AI+%7C+Machine+Learning+%7C+Python;Learning+by+Building+Real+Projects" alt="Animated typing introduction"/>

<p>
  <img src="https://img.shields.io/badge/Program-DevSphere%20Internship-2563EB?style=for-the-badge" alt="DevSphere Internship"/>
  <img src="https://img.shields.io/badge/Week-06-7C3AED?style=for-the-badge" alt="Week 6"/>
  <img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Domain-AI%20%26%20ML-0F766E?style=for-the-badge" alt="AI and ML"/>
</p>

**Two projects. One repository. A practical journey into Artificial Intelligence and Machine Learning.**

</div>

---

## 📌 About This Repository

Welcome to my **Week 6 AI & Machine Learning project repository**, developed as part of the **DevSphere Internship Program**.

This repository contains two separate Python-based projects that demonstrate the machine learning development workflow, from preparing datasets to training models, evaluating predictions, creating visualizations, and accepting user input.

The projects are organized into separate directories to keep their code, datasets, and notebooks easy to understand and maintain.

### 🎯 Project Objectives

- Apply data preprocessing and missing-value handling.
- Train and compare appropriate machine learning models.
- Explore neural-network concepts through an MLP classifier.
- Evaluate classification and regression models with suitable metrics.
- Visualize model performance and prediction results.
- Build interactive prediction workflows using user-provided input.
- Practice organizing Python projects and Google Colab notebooks for GitHub.

> **Dataset transparency:** Both projects use synthetically generated datasets. The results are educational demonstrations, not validated real-world predictions.

---

## 🧭 Table of Contents

- [Project Overview](#-project-overview)
- [Project 1 — AI Student Success Prediction](#-project-1-ai-student-success-prediction--recommendation-system)
- [Project 2 — ML House Price Prediction](#-project-2-machine-learning-house-price-prediction-system)
- [Technology Stack](#-technology-stack)
- [Repository Structure](#-repository-structure)
- [Installation and Setup](#-installation-and-setup)
- [Run the Projects](#-run-the-projects)
- [Google Colab Instructions](#-google-colab-instructions)
- [Evaluation Metrics](#-evaluation-metrics)
- [Outputs and Visualizations](#-outputs-and-visualizations)
- [Learning Outcomes](#-learning-outcomes)
- [Developer Profile](#-developer-profile)
- [Disclaimer](#-disclaimer)

---

## 🔍 Project Overview

<table>
<thead>
<tr>
<th>Project</th>
<th>Type</th>
<th>Primary Goal</th>
</tr>
</thead>
<tbody>
<tr>
<td>AI Student Success Prediction & Recommendation System</td>
<td>Classification and neural-network concepts</td>
<td>Predict a synthetic pass/fail outcome and offer study suggestions</td>
</tr>
<tr>
<td>House Price Prediction System</td>
<td>Regression</td>
<td>Estimate a synthetic house price from property features</td>
</tr>
</tbody>
</table>

---

## 🧠 Project 1: AI Student Success Prediction & Recommendation System

<div align="center">

<img src="https://img.shields.io/badge/AI-Student%20Success-7C3AED?style=for-the-badge&logo=brain" alt="AI student success project"/>

</div>

### 📖 Project Description

The **AI Student Success Prediction & Recommendation System** is an educational classification project designed to estimate a student's pass/fail outcome from selected academic inputs.

It combines data preprocessing, several classification algorithms, a multilayer perceptron neural network, model evaluation, visualizations, and an interactive prediction flow.

When a user provides study hours, attendance, and a previous score, the system uses the trained model to generate a prediction and provides simple rule-based study recommendations.

### 🎯 Objectives

- Generate and prepare a student performance dataset.
- Handle missing feature values.
- Train multiple classification models.
- Explore neural-network classification using an MLP.
- Compare model performance using classification metrics.
- Tune a Random Forest model using cross-validation.
- Visualize evaluation results.
- Accept user input for predictions and study recommendations.

### 🛠️ Main Features

**1. Dataset Preparation**

- Generate a synthetic dataset containing 600 student records.
- Include study hours, attendance, previous score, and a pass/fail target.
- Introduce missing feature values for preprocessing practice.
- Export the generated dataset as a CSV file.

**2. Data Preprocessing**

- Separate input features and target labels.
- Split the data into training and testing subsets.
- Impute missing numerical values using the median.
- Scale features where required by the model pipeline.

**3. Classification Models**

The project includes these model approaches:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- MLP Neural Network Classifier

**4. Hyperparameter Tuning**

The Random Forest model is tuned with `GridSearchCV` and cross-validation to compare selected parameter combinations.

**5. Model Evaluation**

The classification workflow evaluates models using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

**6. Visualizations**

Depending on the executed code, visualizations include:

- Model metric comparison
- Confusion matrix
- Random Forest feature importance
- Feature relationship scatter plot
- Predicted pass probability

**7. Interactive Prediction**

Users enter:

- Study hours
- Attendance percentage
- Previous score

The model predicts the likely synthetic pass/fail outcome. The application also generates basic study suggestions based on the input values and can save a prediction result to CSV.

### 📊 Dataset Features

| Column | Description |
|---|---|
| `StudyHours` | Study hours represented in the synthetic dataset |
| `Attendance` | Attendance percentage |
| `PreviousScore` | Previous academic score |
| `Passed` | Synthetic pass/fail target label |

### 📁 Project Files

- **Python script:** `AI_Student_Success_Prediction/ai_student_success.py`
- **Google Colab notebook:** `AI_Student_Success_Prediction/notebooks/AI_Student_Success_Prediction.ipynb`
- **Dataset:** `AI_Student_Success_Prediction/data/student_performance_week6.csv`

### 🔄 AI Workflow

```text
Synthetic Student Dataset
          ↓
Data Inspection & Preprocessing
          ↓
Train/Test Split
          ↓
Classification Model Training
          ↓
Model Evaluation & Tuning
          ↓
Visualizations
          ↓
User Input & Prediction
          ↓
Study Recommendations & CSV Output
```

---

## 🏠 Project 2: Machine Learning House Price Prediction System

<div align="center">

<img src="https://img.shields.io/badge/Machine%20Learning-House%20Price%20Prediction-0F766E?style=for-the-badge&logo=scikitlearn" alt="Machine learning house price project"/>

</div>

### 📖 Project Description

The **House Price Prediction System** is a regression project that estimates a property's price from selected property features.

It demonstrates how to generate and prepare a dataset, train different regression algorithms, compare evaluation metrics, visualize predictions, and use user input to obtain a model-generated estimate.

The included housing data is synthetic. It is intended to demonstrate the machine learning process, not to estimate actual market values.

### 🎯 Objectives

- Generate a synthetic house price dataset.
- Prepare features and target values.
- Handle missing feature values.
- Train and compare regression models.
- Evaluate prediction errors using standard regression metrics.
- Visualize actual and predicted prices.
- Select a model based on test-set RMSE.
- Accept property details from a user for prediction.

### 🛠️ Main Features

**1. Dataset Preparation**

- Generate a synthetic dataset containing 800 house records.
- Include property area, bedrooms, bathrooms, house age, distance, and price.
- Introduce missing feature values.
- Remove duplicate rows and prepare the dataset for training.
- Export the dataset to CSV.

**2. Data Preprocessing**

- Separate input features and the price target.
- Split the dataset into training and testing subsets.
- Impute missing numerical values using the median.
- Prepare a consistent preprocessing and model pipeline.

**3. Regression Models**

The project compares:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

**4. Model Evaluation**

The regression workflow uses:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

The model with the lowest test-set RMSE is selected by the implemented workflow.

**5. Visualizations**

Depending on the executed code, visualizations include:

- RMSE comparison chart
- Actual-versus-predicted price scatter plot
- Feature importance or absolute coefficient chart
- Feature correlation heatmap

**6. Interactive Prediction**

Users provide property details:

- Area in square feet
- Number of bedrooms
- Number of bathrooms
- House age
- Distance in kilometres

The selected trained model returns an estimated price based on the synthetic training data. The workflow can also save prediction and evaluation results to CSV files.

### 📊 Dataset Features

| Column | Description |
|---|---|
| `Area_sqft` | Property area in square feet |
| `Bedrooms` | Number of bedrooms |
| `Bathrooms` | Number of bathrooms |
| `HouseAge` | House age represented in the dataset |
| `Distance_km` | Distance feature used in the synthetic dataset |
| `Price` | Synthetic target price |

### 📁 Project Files

- **Python script:** `ML_House_Price_Prediction/house_price_prediction.py`
- **Google Colab notebook:** `ML_House_Price_Prediction/notebooks/ML_House_Price_Prediction.ipynb`
- **Dataset:** `ML_House_Price_Prediction/data/house_prices_week6.csv`

### 🔄 ML Workflow

```text
Synthetic Housing Dataset
          ↓
Data Inspection & Preprocessing
          ↓
Train/Test Split
          ↓
Regression Model Training
          ↓
MAE, MSE, RMSE & R² Evaluation
          ↓
Model Comparison
          ↓
Visualization
          ↓
User Input & Price Estimate
          ↓
CSV Results
```

---

## 💻 Technology Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,git,github,vscode" alt="Python development tools"/>

</div>

| Technology | Purpose |
|---|---|
| Python | Project implementation |
| Pandas | Dataset handling and data preparation |
| NumPy | Numerical operations and synthetic data generation |
| Scikit-learn | Preprocessing, model training, tuning, and evaluation |
| Matplotlib | Charts and plots |
| Seaborn | Statistical visualizations |
| Google Colab | Cloud notebook execution |
| Jupyter Notebook | Interactive Python development |
| Git and GitHub | Version control and project sharing |

---

## 📂 Repository Structure

```text
DevSphere_Week6_AI_ML_Projects/
│
├── README.md
├── requirements.txt
│
├── AI_Student_Success_Prediction/
│   ├── ai_student_success.py
│   ├── data/
│   │   └── student_performance_week6.csv
│   └── notebooks/
│       └── AI_Student_Success_Prediction.ipynb
│
├── ML_House_Price_Prediction/
│   ├── house_price_prediction.py
│   ├── data/
│   │   └── house_prices_week6.csv
│   └── notebooks/
│       └── ML_House_Price_Prediction.ipynb
│
└── docs/
    ├── Week_6_AI_ML_Project_Report.docx
    └── Week_6_AI_ML_Project_Report.pdf
```

*Ensure that the actual files in your GitHub repository match this structure. Remove or update any paths for files you have not uploaded.*

---

## ⚙️ Installation and Setup

### Step 1 — Clone the Repository

Replace `YOUR_GITHUB_USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/DevSphere_Week6_AI_ML_Projects.git
cd DevSphere_Week6_AI_ML_Projects
```

### Step 2 — Create a Virtual Environment (Optional)

```bash
python -m venv .venv
```

**Windows**

```bash
.venv\Scripts\activate
```

**macOS / Linux**

```bash
source .venv/bin/activate
```

### Step 3 — Install Dependencies

If the repository includes `requirements.txt`:

```bash
pip install -r requirements.txt
```

Otherwise, install the main libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Step 4 — Verify Python

```bash
python --version
```

Use a Python version supported by the installed library versions.

---

## ▶️ Run the Projects

### Run Project 1 — AI Student Success

From the repository root:

```bash
python AI_Student_Success_Prediction/ai_student_success.py
```

Follow the prompts in the terminal when the script requests student input.

### Run Project 2 — House Price Prediction

```bash
python ML_House_Price_Prediction/house_price_prediction.py
```

Follow the prompts to enter the property features.

**Note:** Run the projects independently. Dataset generation, model training, and interactive input occur according to the code's execution flow.

---

## ☁️ Google Colab Instructions

You can run either project in Google Colab without setting up a local Python environment.

1. Open the repository on GitHub.
2. Navigate to the relevant `notebooks/` folder.
3. Open the `.ipynb` notebook.
4. Download the notebook or upload it to Google Colab.
5. Install any missing dependencies in a notebook cell.
6. Run cells from top to bottom.
7. Review the printed evaluation metrics and generated charts.
8. Enter sample values when prompted by the interactive prediction section.
9. Download generated CSV files and charts if needed for your report.

If you upload only the notebook to Colab, make sure any referenced dataset paths are correct or allow the notebook to generate the dataset itself.

---

## 📈 Evaluation Metrics

### Classification Metrics — AI Project

| Metric | What It Measures |
|---|---|
| Accuracy | Proportion of correct predictions |
| Precision | Proportion of positive predictions that are correct |
| Recall | Proportion of actual positive cases identified |
| F1-score | Harmonic mean of precision and recall |
| Confusion matrix | Counts of correct and incorrect class predictions |

### Regression Metrics — ML Project

| Metric | What It Measures |
|---|---|
| MAE | Average absolute prediction error |
| MSE | Average squared prediction error |
| RMSE | Square root of mean squared error |
| R² | Model fit relative to a baseline based on the target mean |

Metrics must be taken from the actual executed code. This README intentionally does not claim specific scores.

---

## 📊 Outputs and Visualizations

The projects may generate:

### AI Outputs
- Student dataset CSV
- Model comparison metrics
- Confusion matrix
- Feature importance chart
- Pass/fail probability chart
- Interactive student prediction result CSV

### ML Outputs
- House price dataset CSV
- Regression model comparison metrics
- Actual-versus-predicted chart
- Feature importance or coefficient chart
- Correlation heatmap
- House price prediction result CSV

Output filenames and locations depend on the code version and execution paths. Check the messages printed by your notebook or script.

**For internship submission:** Add genuine screenshots showing the dataset preview, preprocessing, model evaluation, graphs, and interactive predictions. Do not report fabricated results.

---

## 📄 Week 6 Project Report

If you include the combined report in the repository, keep it inside the `docs/` folder.

- `docs/Week_6_AI_ML_Project_Report.docx`
- `docs/Week_6_AI_ML_Project_Report.pdf`

The report should document the actual implementation, dataset preparation, evaluation methods, generated results, and screenshots from your own execution.

---

## 🎓 Learning Outcomes

These projects provide practical experience with:

- Data preparation and missing-value handling.
- Classification and regression workflows.
- Neural-network classification concepts using an MLP.
- Scikit-learn pipelines and train/test splits.
- Cross-validation and hyperparameter tuning.
- Classification and regression evaluation metrics.
- Data visualization and result interpretation.
- Interactive prediction workflows.
- Python project organization and GitHub documentation.
- Reproducible experiments using synthetic datasets.

---

## 👨‍💻 Developer Profile

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=23&pause=1200&color=7C3AED&center=true&vCenter=true&width=600&lines=Saud+Masood;BSCS+Graduate;Flutter+Developer;AI%2FML+Engineer" alt="Animated developer profile"/>

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

These projects are developed for learning and internship demonstration purposes. Both datasets are synthetic and do not represent verified real-world observations.

- Student predictions are not definitive judgments of student ability or future success.
- House price estimates are not professional valuations and should not be used for financial decisions.
- Model performance on generated data does not establish real-world reliability.
- Always inspect the executed outputs before reporting results.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:1D4ED8,100:0F172A&height=120&section=footer" width="100%" alt="Decorative animated footer"/>

### 🚀 Built with Python, AI & Machine Learning

**Saud Masood · DevSphere Internship · Week 6**

*Learn • Build • Evaluate • Improve*

</div>
