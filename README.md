# Generative AI Medical Data ETL

<img width="1166" height="590" alt="image" src="https://github.com/user-attachments/assets/a5195f34-4c06-4446-b5ff-70511f44f58f" />

This repository contains an **ETL pipeline** for processing liver patient data. The pipeline extracts information from a CSV file, transforms categorical attributes into numerical values, and loads the cleaned data into an SQLite database for further use by the data science team.

> **Note:** The original dataset is synthetic and not real patient data.

---

## Project Overview

- **Extract:** Load liver patient data from a CSV file into a pandas DataFrame.  
- **Transform:** Convert all categorical columns into numeric values using Label Encoding.  
- **Load:** Save the cleaned dataset into an SQLite database as a table called `Liver_patients`.

---

## Dataset

- **CSV Path:** `C:\Users\higas\Downloads\gen-ai-medical-data-etl\Liver_Patient_Dataset_ILPD.csv`  
- **Columns:** The dataset contains medical parameters related to liver disease along with prognosis (disease/no disease).  

---

## ETL Pipeline Usage

1. Clone this repository:

git clone https://github.com/sultanraheem/generative-ai-medical-data-etl.git
cd generative-ai-medical-data-etl
Install required Python packages:

pip install pandas scikit-learn sqlite3
Run the ETL notebook or script:

jupyter notebook
# Open the ETL notebook and run all cells
The pipeline will generate an SQLite database:

Database name: Patient_record.db

Table name: Liver_patients

You can query the table using any SQL client or pandas.

## Project Structure

<img width="283" height="110" alt="image" src="https://github.com/user-attachments/assets/2236ea1c-7582-4a56-8706-d526adb413c2" />

