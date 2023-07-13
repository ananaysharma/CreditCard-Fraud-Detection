# CreditCard-Fraud-Detection
Building a supervised fraud model on the credit card transaction data

This project focuses on building a supervised fraud detection model for credit card transactions using a dataset of company card transactions. The dataset consists of 96,753 records of business transactions from a US government organization, presumably located in Tennessee. Although the dataset only contains 10 fields, it provides enough information to build a traditional credit card transaction fraud algorithm.

However, the dataset does not include labeled fraud records. To overcome this limitation, approximately 1,000 typical fraud records were invented based on knowledge of how credit card fraud behaves. These fabricated fraud records closely resemble real fraud cases, presenting a challenging problem that closely mimics real-world scenarios.

## Project Goals

The primary goal of this project is to develop a supervised fraud model using proper methodology and techniques. The project follows a structured approach, covering the following key steps:

1. **Preliminary exploration of the dataset:** Understand the structure and characteristics of the dataset.

2. **Data Cleaning and Feature Engineering:** Perform necessary data cleaning tasks, handle missing values, and create additional relevant features.

3. **Feature Selection:** Identify the most informative features to improve model performance and reduce noise.

4. **Explore preliminary models:** Build and evaluate initial fraud detection models using different algorithms.

5. **Select final model and create a report:** Choose the best-performing model and generate a comprehensive report that identifies fraudulent transactions effectively.

## Repository Structure

- `data/`: Directory to store the dataset and any additional data files used in the project.
- `notebooks/`: Jupyter notebooks documenting the analysis, data preprocessing, and model building steps.
- `reports/`: Folder containing the final report and any related documents summarizing the project's findings.
- `README.md`: This file, providing an overview of the project.

## Requirements

- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib, seaborn, etc. (See requirements.txt for a full list of dependencies.)

## Usage

To reproduce or extend the project's results, follow the notebooks provided in the `notebooks/` directory. The notebooks are organized in a sequential order that reflects the project's workflow.

