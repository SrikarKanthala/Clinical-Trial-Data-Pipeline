# Clinical Trial Data Transformation Pipeline

## 🧠 Overview
This project simulates a real-world data pipeline used to process clinical trial data. It includes data cleaning, feature engineering, validation, and visual exploration using Python in Google Colab.

## 📁 Dataset
A synthetic dataset of 500 clinical trial entries was generated using Python's Faker library. It includes:
- Trial & patient IDs
- Medical conditions
- Trial phase/status
- Dates, dosage, response

## ⚙️ Key Steps
1. **Data Cleaning:** Removed duplicates, handled nulls, standardized column names
2. **Feature Engineering:**
   - `trial_duration_days` from start and end date
   - `is_elderly` flag based on age
   - `phase_code` encoding for ML readiness
3. **Visualization:** Trial count per condition using Seaborn
4. **Exported cleaned data** as a CSV

## 🧰 Tools Used
- Python, Pandas, NumPy
- Matplotlib & Seaborn for visualization
- Google Colab

## 💡 Future Work
- Load data into SQL or use Streamlit for dashboard
- Add predictive modeling (e.g., outcome classification)

## 👤 Author
[Srikar Kanthala](https://www.linkedin.com/in/srikarkanthala)
