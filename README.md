# ICS_435_Final_Project

**Authors:** Shaelyn Loo & Ahnasia Goulbourne  
**Course:** ICS 435

## Project Overview

This project investigates the feasibility of predicting patient adherence to mental 
health treatment plans using pre-treatment intake features. The original goal was to 
frame adherence prediction as a multi-class classification problem, categorizing 
patients into Low, Medium, or High adherence classes using demographic, clinical, and 
behavioral features available at the start of treatment.

After systematic modeling and evaluation, all classifiers performed near or below 
random chance, prompting a reframing of the project as a structured error analysis.
The primary contribution of this project is an investigation into why the models failed,
ruling out multiple potential causes and identifying the synthetic nature of the dataset as the 
dominant limiting factor.

## Dataset

**Source:** [Mental Health Diagnosis and Treatment Monitoring](https://www.kaggle.com/datasets/uom190346a/mental-health-diagnosis-and-treatment-monitoring)  
**Size:** 500 rows, 17 features  
**Type:** Synthetic  

Features cover patient demographics, diagnosis, symptom severity, sleep quality, 
physical activity, stress level, medication, therapy type, treatment dates, and 
adherence percentages.

## Requirements

Install all dependencies using pip:

```bash
pip install -r requirements.txt
```

### requirements.txt contents:
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
statsmodels
jupyter

## How To Run

1. Clone the repository:
```bash
git clone https://github.com/shaelyn-l/ICS_435_Final_Project.git
cd ICS_435_Final_Project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle and place the CSV file in the same directory 
   as the notebook

4. Open and run the notebook:
```bash
jupyter notebook ICS_435_Final_Project.ipynb
```

> **Note:** Run all cells sequentially from top to bottom. Each section 
> builds on variables and data defined in previous cells, running cells out 
> of order will result in errors.
