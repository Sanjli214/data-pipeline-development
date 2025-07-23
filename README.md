# 📊 Data Pipeline Development – CodTech Internship Task 1

This repository contains my submission for **Task 1: Data Pipeline Development** as part of the **CodTech Internship**.  
I developed a complete **ETL (Extract, Transform, Load) pipeline** using **Python**, **Pandas**, and **Scikit-learn** on a real-world Netflix dataset.

---

## 📌 Project Overview

🔹 **Objective**: Automate the end-to-end process of extracting raw data, cleaning and transforming it, and saving the final processed output.  
🔹 **Task Name**: Data Pipeline Development (Task 1)  
🔹 **Internship**: CodTech  
🔹 **Tech Stack**: Python, Pandas, Scikit-learn  
🔹 **Dataset**: Netflix Titles Dataset (from PrasertCbs GitHub)

---

## 🗃️ Files Included

| File                             | Description                                      |
|----------------------------------|--------------------------------------------------|
| `netflix_etl_pipeline.ipynb`     | Jupyter Notebook with the full ETL pipeline      |
| `processed_netflix_titles.csv`   | Cleaned and transformed output dataset           |
| `README.md`                      | Project documentation and explanation            |

---

## 🔄 ETL Pipeline Summary

### ✅ 1. **Extract**
- Loaded Netflix dataset from a trusted GitHub source
- Inspected structure and null values

### ✅ 2. **Transform**
- Cleaned missing values in `country`, `rating`, `director`
- Parsed `date_added` into datetime format
- Feature engineered new columns: `year_added`, `month_added`, `duration_int`, `duration_type`
- Label encoded `type`, `rating`
- Scaled numerical features using `StandardScaler`
- Removed duplicates

### ✅ 3. **Load**
- Saved the cleaned and transformed dataset to a CSV file: `processed_netflix_titles.csv`

---

## 📊 Dataset Source

- 📂 [Netflix Titles Dataset (GitHub)](https://raw.githubusercontent.com/prasertcbs/basic-dataset/master/netflix_titles.csv)

---

## ⚙️ Tools & Technologies

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook

---

## 🙋‍♀️ About Me

👩‍💻 **Sanjli Agarwal**  
🎓 B.Tech CSE (Data Science Minor) – NIET, Greater Noida  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile/) *(Add your actual link)*

---

## 📌 Status

✅ **Task 1 – Data Pipeline Development**: Completed  
🔜 Task 2: Coming soon...

---

## 📎 Tags

`#DataPipeline` `#ETL` `#Python` `#Pandas` `#Sklearn` `#NetflixDataset` `#DataAnalytics` `#CodTechInternship`
