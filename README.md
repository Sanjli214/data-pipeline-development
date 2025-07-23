# 📊 Task 1: Data Pipeline Development – CODTECH Internship

This project is part of my internship at **CODTECH**, where the goal was to design and implement a **Data Pipeline** that automates **data extraction**, **preprocessing**, **transformation**, and **loading** using Python libraries like **Pandas** and **Scikit-learn**.

We use the **Netflix Titles Dataset** and perform comprehensive ETL steps to prepare the data for further analysis or modeling.

---

## 🎯 Objective

To create a robust, reusable, and automated **ETL (Extract, Transform, Load)** pipeline using Python that:

- Extracts data from a trusted source
- Cleans and preprocesses the data
- Transforms features for machine learning readiness
- Saves the cleaned dataset for further use

---

## 📂 Dataset Used

- **Source:** [Netflix Titles Dataset](https://raw.githubusercontent.com/prasertcbs/basic-dataset/master/netflix_titles.csv)
- **Type:** CSV file hosted on GitHub
- **Description:** Contains data about Netflix TV shows and movies available for streaming.

---

## 🛠️ Tools and Libraries

- **Python 3**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Scikit-learn** – for encoding and scaling
- **Jupyter Notebook** – for step-by-step execution

---

## 🔁 Workflow Steps

### 1. Data Extraction

- Loaded the dataset directly from a raw GitHub CSV URL using `pandas.read_csv()`.

### 2. Data Preprocessing

- Checked for missing/null values and handled them:
  - Filled or dropped based on relevance
- Removed duplicate records
- Converted `date_added` to datetime format
- Extracted useful features like `year_added` and `month_added` from `date_added`

### 3. Data Transformation

- **One-Hot Encoding** of categorical features (like `type`, `rating`)
- **Label Encoding** where appropriate (e.g., country)
- **Feature Scaling** on numerical columns (if any)
- Cleaned and normalized the dataset for further use

### 4. Data Loading

- Saved the cleaned and transformed data into a new CSV file:

## 📌 Installation & Usage

To run the project locally:

```bash
git clone https://github.com/your-username/netflix-data-pipeline-codtech.git
cd netflix-data-pipeline-codtech
pip install -r requirements.txt
jupyter notebook netflix_etl_pipeline.ipynb
