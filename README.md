# README — CARISURG WEEK 0

## Overview
This repository contains work completed during **Week 0** of the **Carisurg MedTech Pathways Healthcare AI Program**.

It includes Assignments 1–7, covering healthcare data cleaning, data visualization, triage concepts, pseudocode development, and time management planning.

---

# Repository Contents

## Assignment 1 — Cleaning the Gender Column

### Objective
This assignment focused on cleaning the **Gender** column within an Emergency Department dataset from Mercer General Hospital.

The dataset originally contained inconsistent and non-standard gender entries (“dirty” data). These values were cleaned and transformed into a standardized numeric format suitable for future analysis and projects.

### Gender Encoding
- **1 = Male patients**  
- **0 = Female patients**  
- **-1 = Unknown**

### Dataset/Input
`EmergencyTriageDataset_Reduced_Dirty.csv`

### Output
`EmergencyTriageDataset_Reduced_Clean.csv`

---

## Assignment 2 — Cleaning the FiO₂ Column

### Objective
This assignment focused on cleaning the **FiO₂** column in the Emergency Department dataset.

Although the dataset did not contain clinically invalid FiO₂ values (below 21% or above 100%), it did contain missing values (`NaN`). These missing values were identified and imputed using the **mode** of the column.

This method was selected because it preserves the most frequently occurring clinical value without introducing unnecessary variation into the dataset.

### Data Cleaning Steps
- Checked for invalid or out-of-range values  
- Identified missing values (`NaN`)  
- Analyzed the distribution of FiO₂ values  
- Filled missing values using the mode  
- Verified consistency for later analysis  

### Dataset/Input
`EmergencyTriageDataset_Reduced_Dirty.csv`

---

## Assignment 3 — Data Visualization

### Objective
This assignment focused on creating visualizations from an Emergency Department dataset to explore clinical relationships and trends.

The analysis included:
- Respiratory rate (RR)  
- Pulse/heart rate  
- Age  
- Oxygen support (FiO₂)  

### Plot 1 — RR vs Pulse
This scatter plot explores the relationship between respiratory rate and heart rate.

Clinical thresholds included:
- **RR > 20** → Tachypnoea  
- **Pulse > 100** → Tachycardia  

#### Findings
The data shows no strong or consistent relationship between respiratory rate and pulse, although several patients exceed clinical thresholds.


### Plot 2A — FiO₂ Distribution
This histogram displays the distribution of oxygen support levels.

#### Findings
Most patients cluster at lower FiO₂ values, suggesting many are on room air or low oxygen support, while fewer require higher oxygen concentrations.


### Plot 2B — Age vs FiO₂
This scatter plot examines whether patient age is associated with oxygen support levels.

#### Findings
The data suggests a weak relationship, with slightly higher FiO₂ values appearing more frequently in older patients, though no strong trend is present.

### Dataset/Input
`EmergencyTriageDataset_Reduced_Dirty.csv`

---

## Assignments 4 & 5 — Vital Sign Descriptions Used in Triage

### Objective
These assignments focused on describing and interpreting key vital signs commonly used in emergency triage systems. The topics covered were blood pressure and oxygen saturation (SpO₂), with emphasis on their clinical thresholds and their role in supporting accurate patient assessment and clinical decision-making in emergency triage settings.

---

## Assignment 6 — Triage Risk-Level Pseudocode

### Objective
This assignment involved designing a pseudocode framework to simulate how a digital triaging system assigns risk levels based on patient vital signs and other clinical indicators. Building on foundational knowledge of emergency department triage and the key metrics used in clinical decision-making, the task required creating a representation of how an AI system could process patient inputs and categorise them into appropriate risk levels.

---

## Assignment 7 — Career Challenge: Time Management

### Topic
**Time Management for MedTech Students**

### Objective
This assignment focused on building effective time management strategies for students participating in the Carisurg MedTech Pathways Healthcare AI Program.

The project included:
- A 12-week time management plan  
- Weekly scheduling strategies  
- Personal productivity planning  
- Development of a structured weekly timetable  

### Career Challenge Image
<img width="1545" height="1999" alt="Time Management" src="https://github.com/user-attachments/assets/8eb6741c-2f8e-4af5-a173-d55ca075801b" />
