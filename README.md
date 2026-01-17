# Social Media and Mental Health DSS

## Project Description
This is a Decision Support System (DSS) that analyzes social media usage and mental health data.  
It helps identify users at Low, Medium, or High risk for mental health issues based on screen time and depression scores.

## Dataset
- Source: Kaggle - Social Media and Mental Health Dataset
- Size: 481 records, 21 columns
- Stored in: `data/social_media_mental_health.csv`

## Tools Used
- Python
- Jupyter Notebook
- Pandas (for data handling)
- Seaborn & Matplotlib (for visualization)

## How to Run
1. Clone the repository:  
```bash
git clone <your-repo-url>

##DSS Logic

Decision rule:

High Risk → Daily screen time > 5 hours AND Depression ≥ 4

Medium Risk → Daily screen time > 3 hours

Low Risk → Otherwise

Output: Each user classified as Low, Medium, or High risk.

Supports decisions for mental health interventions.

Results

Risk distribution (example):

Low Risk → 42.6%

Medium Risk → 42.4%

High Risk → 15.0%
