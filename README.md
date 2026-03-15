# Fake Instagram Profile Detection using Machine Learning

This project implements a classification model to identify fraudulent Instagram accounts based on metadata. By analyzing features such as profile completeness, username patterns, and engagement metrics, the model distinguishes between real and fake profiles.

## Overview
Social media platforms are increasingly challenged by automated bots and fake accounts. This project provides a data-driven approach to detect these profiles, helping to maintain platform integrity and user trust.

## Dataset Characteristics
The model uses a dataset of 5,000 samples (2,500 real and 2,500 fake accounts). Key features analyzed include:
* **Profile Attributes:** Presence of a profile picture, name-to-username similarity, and bio length.
* **Username Patterns:** Ratio of numerical characters to total username length.
* **Engagement Stats:** Number of followers, following count, and post frequency.
* **Target Variable:** `fake` (0 for Real, 1 for Fake).

## Key Insights from EDA
* **Profile Picture:** There is a strong negative correlation (-0.78) between having a profile picture and being a fake account.
* **Username Digits:** Fake accounts frequently use a higher ratio of numbers in their usernames (correlation of 0.66).
* **Bio Content:** Real accounts typically have longer, more descriptive bios compared to fraudulent ones.

## Technical Stack
* **Language:** Python
* **Data Libraries:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (Preprocessing, Modeling, and Evaluation)

## Model Evaluation
The project includes a comprehensive evaluation phase, featuring:
* **Correlation Heatmaps:** To understand feature relationships.
* **ROC Curve & AUC Score:** To measure the model's diagnostic ability and classification accuracy.

## How to Run
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/fake-insta-detection.git](https://github.com/your-username/fake-insta-detection.git)
