# Heart Disease Data Analysis

A Python-based exploratory data analysis project on a heart disease dataset using **Pandas, NumPy, Seaborn, and Matplotlib**.

The project focuses on understanding the dataset, exploring patient-related features, identifying patterns, and visualizing relationships between different health-related attributes and the `HeartDisease` target variable.

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset containing information related to heart disease.

The analysis includes:

- Loading and inspecting the dataset
- Understanding dataset structure and dimensions
- Checking data types and missing values
- Exploring numerical and categorical features
- Analyzing the distribution of different variables
- Studying relationships between features
- Creating visualizations to identify patterns
- Exploring the `HeartDisease` target variable

## 🗃️ Dataset

The dataset contains **918 records and 12 columns**.

### Features

| Feature | Description |
|---|---|
| `Age` | Age of the patient |
| `Sex` | Sex of the patient |
| `ChestPainType` | Type of chest pain |
| `RestingBP` | Resting blood pressure |
| `Cholesterol` | Serum cholesterol level |
| `FastingBS` | Fasting blood sugar indicator |
| `RestingECG` | Resting electrocardiogram results |
| `MaxHR` | Maximum heart rate achieved |
| `ExerciseAngina` | Exercise-induced angina |
| `Oldpeak` | ST depression value |
| `ST_Slope` | Slope of the peak exercise ST segment |
| `HeartDisease` | Target variable indicating heart disease |

## 🛠️ Technologies Used

- **Python**
- **NumPy** – numerical operations
- **Pandas** – data loading and analysis
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook / Google Colab**

## 📊 Analysis Performed

The notebook explores the dataset through different stages:

### 1. Data Loading
The dataset is loaded using Pandas and stored in a DataFrame.

### 2. Data Inspection
The dataset is examined using operations such as:

- `head()`
- `columns`
- `shape`
- `info()`
- `describe()`
- Missing-value checks

### 3. Feature Analysis

Both numerical and categorical variables are explored to understand their distributions and characteristics.

### 4. Data Visualization

Different plots are used to visualize relationships and distributions within the dataset.

### 5. Target Analysis

The `HeartDisease` column is analyzed to understand how the target variable relates to different features in the dataset.

## 📁 Project Structure

```text
heart-disease-analysis/
│
├── Heart_Disease_Analysis.ipynb
├── heart.csv
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/heart-disease-analysis.git
```

### 2. Navigate to the project

```bash
cd heart-disease-analysis
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### 4. Open the notebook

```bash
jupyter notebook
```

Then open:

```text
Heart_Disease_Analysis.ipynb
```

## ⚠️ Disclaimer

This project is intended for **educational and data-analysis purposes only**.

The analysis should not be used as a medical diagnostic tool or as a substitute for professional medical advice.

## 📚 Learning Outcomes

Through this project, I practiced:

- Python-based data analysis
- Pandas DataFrame operations
- Data cleaning and inspection
- Exploratory Data Analysis
- Statistical visualization
- Working with numerical and categorical data
- Extracting insights from datasets

## 👨‍💻 Author

**Rushil Patel**

B.Tech CSE (Artificial Intelligence)

---

⭐ If you found this project useful, feel free to explore the notebook and the analysis.
