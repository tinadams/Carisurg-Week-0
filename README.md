# README — Mercer General Project 

## Objective
This project focuses on practicing data cleaning techniques in Python. 

## DAY 1
The main task for Day 1 is to clean the **Gender** column within an Emergency Department dataset at Mercer General Hospital.

The dataset originally contained inconsistent and non-standard gender entries (referred to as “dirty” data). These values were cleaned and transformed into a consistent numeric format that can be used for future analysis and modeling.

After cleaning, the **Gender** column is encoded as follows:

- **1 = Male patients**  
- **0 = Female patients**
- **-1 = unkown**

---

# Dataset/Input

**File used:** `EmergencyTriageDataset_Reduced_Dirty.csv`

# Output

**Cleaned dataset generated:** `EmergencyTriageDataset_Reduced_Clean.csv`


## DAY 2
The main task for Day 2 is to clean the **Fio2** column within an Emergency Department dataset at Mercer General Hospital.

Although the original dataset did not contain values outside the valid range (below 21% or above 100%), it included missing values (NaN). These missing entries were identified and imputed uding the mode to ensure the column was in a consistent and usable format.

This approach was selected because it preserves the most frequently occurring clinical value in the dataset without adding unnecessary variation into the distribution.

# Data Cleaning Steps (Fio2 Column)

- Checked for invalid or out-of-range values
- Identified missing values (NaN) in the **Fio2** column  
- Analyzed distribution to determine appropriate imputation method  
- Filled missing values using the mode value  
- Ensured consistency and readiness for later analysis


## Dataset/Input

**File used:** `EmergencyTriageDataset_Reduced_Dirty.csv`

## DAY 3
The main task for Day 3 is to create **data visualizations** using an Emergency Department dataset at Mercer General Hospital.

My work looks at relationships and patterns in key clinical variables, including respiratory rate, heart rate, age, and oxygen support (FiO₂).

# Plot 1: RR vs Pulse
This scatter plot explores the relationship between respiratory rate and heart rate.

Clinical thresholds were added for:
- RR > 20 (tachypnoea)  
- Pulse > 100 (tachycardia)

The data shows no strong or consistent relationship between RR and pulse, although some patients exceed clinical thresholds.

# Plot 2A: FiO₂ Distribution
This histogram shows the distribution of oxygen support levels.

Most patients are clustered at lower FiO₂ values, suggesting many are on room air or low oxygen support, with fewer patients requiring higher levels.

# Plot 2B: Age vs FiO₂
This scatter plot looks at whether age is related to oxygen support levels.

The data suggests a possible weak relationship, with slightly higher FiO₂ in older patients, but there is no clear pattern.

## Dataset/Input

**File used:** `EmergencyTriageDataset_Reduced_Dirty.csv`
