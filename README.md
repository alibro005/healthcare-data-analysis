<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a3d62,50:1e7ab8,100:00cec9&height=220&section=header&text=🏥%20Healthcare%20Data%20Analysis&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Exploratory%20Data%20Analysis%20of%20Patient%20and%20Hospital%20Records&descAlignY=60&descSize=15&animation=fadeIn" width="100%"/>

<br/>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-11557C?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br/>

> *Turning healthcare data into actionable insights through exploratory analysis.*

</div>

---

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a healthcare dataset containing patient demographics, medical conditions, admission details, hospital information, and billing records.

The goal is to **understand patterns**, **identify cost drivers**, and **explore relationships** between clinical and operational variables using **Python, Pandas, and Matplotlib**.

---

##  Repository Structure

```
healthcare-data-analysis/
│
├──  data/                    # Raw and/or processed dataset files
│
├──  notebook/                # Jupyter Notebook
│
├── .gitignore                  # Files excluded from version control
├── requirements.txt            # Python dependencies
└── README.md                   

```

---

## Dataset Description

The dataset includes approximately **55,000 patient records** with the following features:

### Demographic Information
- Name
- Age
- Gender
- Blood Type

### Clinical & Admission Details
- Medical Condition
- Admission Type
- Medication
- Test Results
- Doctor
- Hospital

### Time & Stay Information
- Date of Admission
- Discharge Date
- Length of Stay (engineered)

### Financial Data
- Billing Amount

---

##  Analysis Workflow

### 1. Data Inspection
- Dataset shape and structure
- Data types and column validation

### 2. Data Cleaning
- Removed duplicate records
- Converted date columns to `datetime`
- Verified missing values

### 3. Feature Engineering
- **Length of Stay** calculated from admission and discharge dates
- Age-based filtering and segmentation

### 4. Exploratory Data Analysis (EDA)
- Distribution analysis
- Grouped aggregations
- Relationship analysis between stay duration and billing

---

##  Visualizations Created

The notebook includes the following **Matplotlib-based visualizations**:

- **Gender Distribution (%)**
- **Top 10 Medical Conditions**
- **Age Distribution of Patients**
- **Billing Amount Distribution**
- **Length of Stay vs Billing Amount**
- **Admission Type Comparison**

All plots are built using **pure Matplotlib** (no Seaborn), with annotated values where appropriate.

---

##  Key Insights

| Insight | Interpretation |
|------|---------------|
| Gender distribution is nearly balanced | Dataset is demographically stable |
| A small number of medical conditions dominate admissions | Preventive focus areas can reduce hospital load |
| Longer hospital stays strongly increase billing amounts | Length of stay is a major cost driver |
| Emergency admissions tend to be more expensive | Emergency resource optimization is critical |
| Billing amounts show significant variability | Indicates differences in treatment intensity |

---

##  Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/alibro005/healthcare-data-analysis.git
cd healthcare-data-analysis
```
### 2. Install Dependencies
```
pip install -r requirements.txt
```
### 4. Run the Notebook
```
jupyter notebook notebook/
```
Run all cells to reproduce the analysis.


### Tools & Libraries

| Tool             | Purpose              |
| ---------------- | -------------------- |
| Python           | Core programming     |
| Pandas           | Data manipulation    |
| Matplotlib       | Visualization        |
| Jupyter Notebook | Interactive analysis |

###  License

This project is licensed under the MIT License.

<div align="center">

Created with data curiosity by [alibro005](www.github.com/alibro005)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00cec9,100:0a3d62&height=100&section=footer" width="100%"/> 

</div> 
