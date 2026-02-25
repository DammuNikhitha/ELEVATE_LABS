 # AI & ML Internship – Task 1  
## Understanding Dataset & Data Types

### 📌 Objective
The objective of this task is to understand the structure of datasets, identify different data types, analyze data quality, and evaluate the suitability of the data for machine learning models.

### 📊 Datasets Used
1. **Titanic Dataset**
   - Predicts passenger survival based on features like age, gender, class, etc.

2. **Students Performance Dataset**
   - Contains students’ exam scores and demographic information.

Both datasets are publicly available and were downloaded from Kaggle.

### 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

### 🔍 Task Performed
- Loaded datasets using Pandas
- Displayed first and last few records
- Checked dataset shape and structure
- Identified numerical, categorical, ordinal, and binary features
- Analyzed data types and missing values using `df.info()`
- Generated statistical summaries using `df.describe()`
- Checked unique values in categorical columns
- Identified target variables and input features
- Observed data quality issues such as missing values and imbalance
- Evaluated dataset suitability for machine learning

### 🎯 Target Variables
- **Titanic Dataset:** `Survived`
- **Students Dataset:** `Math Score` / `Reading Score`


### 📈 Observations
- Titanic dataset contains missing values in the `Age` column.
- Some categorical variables require encoding before model building.
- The datasets are suitable for basic machine learning tasks.
- Titanic dataset shows class imbalance in the target variable.
