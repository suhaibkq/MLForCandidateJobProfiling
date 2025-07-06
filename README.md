# 🔍 Job Change Prediction using Ensemble Learning

## 📌 Problem Statement

In today's competitive job market, identifying whether an employee is likely to switch jobs is valuable for employers and recruiters. This project aims to build a predictive model using machine learning techniques to determine if a candidate is likely to change jobs.

## 🎯 Objective

To predict whether a candidate is looking for a job change using features such as education, experience, training hours, and company size. This helps organizations optimize their hiring strategies and retention plans.

## 📊 Dataset

- **File**: `jobs_data.csv`
- **Target Variable**: `target` (1 = looking for a job change, 0 = not looking)
- **Features Include**:
  - `city`, `gender`, `relevent_experience`, `enrolled_university`, `education_level`
  - `major_discipline`, `experience`, `company_size`, `last_new_job`, `training_hours`
  - `company_type`, `education_level`, etc.

## 🧪 Project Workflow

1. **Data Preprocessing**
   - Handled missing values and inconsistent categories
   - Label encoding for categorical variables
   - Standardized numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of experience, company size, and training hours
   - Analyzed correlation between features and job change intent

3. **Model Building**
   - Implemented Bagging and Random Forest classifiers
   - Performed hyperparameter tuning using GridSearchCV
   - Used train-test split for performance evaluation

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score
   - Used Confusion Matrix and ROC Curve for comparison

## 🏆 Results

- **Best Performing Model**: Random Forest
- **Key Insights**:
  - Candidates with relevant experience and more training hours are less likely to change jobs
  - Candidates from smaller companies or with fewer years of experience are more likely to look for new opportunities

## 📁 Repository Structure

├── MLS3_ETMT_session_notebook_updated_.ipynb
├── jobs_data.csv
├── README.md


## 🔍 Key Takeaways

- Ensemble techniques like Bagging and Random Forest improve prediction accuracy and reduce overfitting.
- Targeted recruitment and retention strategies can be built using these models.
- Proper feature engineering and handling of categorical variables significantly impact model performance.

## 🚀 Future Enhancements

- Deploy the model via Streamlit or Flask for interactive prediction
- Use SHAP or LIME for model explainability
- Integrate more behavioral data such as application history or job portal activity

## 👨‍💻 Author

**[Suhaib Khalid]**  
ML Enthusiast

