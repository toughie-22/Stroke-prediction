
🔍 Project Overview

The dataset includes information on:

1. Demographics: Age, gender, residence type

2. Medical history: Hypertension, heart disease, average glucose level, BMI

3. Lifestyle: Smoking status, work type, marital status

The project follows these steps:

1. Data Cleaning

i. Missing BMI values filled with the mean (since BMI doesn’t fluctuate wildly).

ii. Removed the irrelevant ID column.

2. Exploratory Data Analysis (EDA)

i. Checked distributions of health indicators.

ii. Visualized patterns across stroke vs. non-stroke groups.

3. Modeling

i. Built classification models to predict stroke occurrence.

ii. Compared performance to identify the most reliable approach.

4. Evaluation

i. Balanced sensitivity (catching true stroke cases) with precision (avoiding false alarms).

📊 Why This Matters

1. Healthcare Relevance: Identifying stroke risk early allows for lifestyle changes, targeted medical care, and potentially life-saving interventions.

2. Data Science Challenge: The dataset is imbalanced (few stroke cases compared to non-stroke), making this a great opportunity to apply resampling techniques and metrics beyond accuracy.

3. Scalability: With more clinical data, this model could be integrated into hospital decision-support systems.

🚀 Tech Stack

i. Python

ii. Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

⚡ How to Run

Clone this repository.

Place stroke.csv in the project folder.

Launch the notebook:

jupyter notebook Stroke_prediction.ipynb


Run the cells to see data cleaning, analysis, and predictions in action.

💡 Key Takeaway

This project demonstrates how machine learning can transform raw health data into actionable insights. By bridging healthcare and data science, we take one more step toward building smarter systems that protect lives.
