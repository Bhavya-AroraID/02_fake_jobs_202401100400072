# 02_fake_jobs_202401100400072

# Fake Job Detection

## Overview
This project aims to build a machine learning model to classify job postings as **real** or **fake** using structured data such as title length, description length, and the presence of a company profile. It helps job portals and users avoid fraudulent postings and improves trust in online platforms.

## Dataset
The dataset contains the following key features:
- `title_length`: Length of the job title
- `description_length`: Length of the job description
- `has_company_profile`: Whether a company profile exists (1 = Yes, 0 = No)
- `is_fake`: Label (1 = Fake, 0 = Real)

## Project Structure

## Setup Instructions
1. Clone the repository or upload the files to Google Colab.
2. Install required libraries (most are pre-installed in Colab):
```bash
pip install pandas scikit-learn matplotlib seaborn

