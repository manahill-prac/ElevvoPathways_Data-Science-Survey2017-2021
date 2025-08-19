# Data-Science-Survey2017-2021

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/manahill-prac/ElevvoPathways_Data-Science-Survey2017-2021/blob/main/YourNotebookName.ipynb)

---

## 📌 Project Description

This project performs **data cleaning, exploratory analysis, and visualization** on the **Kaggle Data Science Survey 2017–2021** dataset.  
The main objectives are:

- Handle missing values, duplicates, and inconsistent formatting.  
- Encode categorical variables for analysis.  
- Extract meaningful insights about survey respondents (demographics, experience, education, tools used, etc.).  
- Create professional visualizations for portfolio and reporting.  
- Export a cleaned dataset and summary dashboard for further analysis.

This notebook is **fully reproducible in Google Colab**, with dataset loaded directly from Google Drive, ensuring **zero runtime issues**.

---

## 📂 Dataset Information

- **Dataset:** [Kaggle Data Science Survey 2017-2021](https://www.kaggle.com/datasets/ruchi798/data-science-survey-2017-2021)  
- **File Used:** `kaggle_survey_2017_2021.csv`  
- **Notes:**  
  - Contains numeric codes for categorical responses.  
  - Multi-part columns exist for some survey questions (e.g., Q7 Tools Used).  
  - Cleaned dataset and summary CSVs are exported for easy analysis.

---

## 📝 Step-by-Step Instructions

1. **Setup Environment**
   - Install and import required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.  
   - Load the dataset from Google Drive for smooth Colab execution.

2. **Data Cleaning**
   - Remove duplicates and unnecessary columns.  
   - Standardize column names and text entries.  
   - Handle missing values appropriately.

3. **Encoding Categorical Variables**
   - Apply `LabelEncoder` or mapping for categorical survey columns.  
   - Standardize multi-part columns like Q7 (Tools Used).

4. **Extract Insights**
   - Compute top 5 countries, gender distribution, experience levels, education levels, and top tools used.  
   - Map numeric codes back to readable labels for portfolio presentation.

5. **Professional Visualizations**
   - Bar charts for all top insights.  
   - Clean, consistent styling using `seaborn` and `matplotlib`.  
   - 2x3 layout dashboard with titles and axes labels.

6. **Export Cleaned Data & Summary**
   - Save cleaned dataset as `survey_2017_2021_cleaned.csv`.  
   - Export top insights as `survey_summary_dashboard.csv`.  
   - Optional: create a readable version with text labels (`survey_2017_2021_readable.csv`).

7. **Display Summary in Notebook**
   - Step 11 displays both the summary dashboard and readable cleaned dataset directly in the notebook for easy preview.

---

## 📌 Output Files

| File | Description |
|------|-------------|
| `survey_2017_2021_cleaned.csv` | Numeric-coded cleaned dataset for analysis |
| `survey_2017_2021_readable.csv` | Human-readable version with text labels |
| `survey_summary_dashboard.csv` | Top insights (countries, gender, experience, education, tools) |

---

