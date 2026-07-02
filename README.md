# Vortex Tech AI/ML Internship - Week 1: Data Cleaning and EDA

## Project Overview
This project focuses on the fundamental first step of the AI/ML pipeline: taking a raw dataset, identifying structural flaws or missing information, performing necessary data cleaning, and conducting an Exploratory Data Analysis (EDA). 

For this task, a road network dataset consisting of 200 distinct entries was analyzed to evaluate structural integrity, surface conditions, speed limits, and traffic metrics.

## What Was Built
* **Data Inspection & Quality Check:** Verified the dataset structure, missing data profiles, and checked for duplicated row entries using Pandas.
* **Data Type Pipeline:** Fixed structural discrepancies by explicitly converting date features (`last_maintenance_date`) from text format to standard datetime objects.
* **Statistical Analysis:** Generated descriptive numerical summaries and category distribution counts.
* **Visualizations:** Engineered data distribution graphs using Matplotlib and Seaborn, including:
  * A distribution histogram analyzing road speed limits.
  * A categorical bar chart tracking the frequencies of various road surface conditions.

## Project Structure
* `Week 1.ipynb`: The primary Jupyter Notebook containing all annotated Python code, data cleaning steps, and visualization cells.
* `road_network.csv`: The underlying raw dataset utilized for the analysis.
* `README.md`: Documentation detailing project architecture and setup instructions.

## How to Run It

### 1. Prerequisites
Ensure you have Python installed on your local system[cite: 1]. You will need to install the following core data science libraries[cite: 1]:
```bash
pip install pandas matplotlib seaborn jupyter

### 2.Execution : 
1.clone or download this repository to your local machine.
2.Open your terminal or command prompt, navigate to the project directory, and launch the Jupyter environment:jupyter notebook
3.Open your notebook file from the Jupyter dashboard and run the cells sequentially to observe the data pipeline and visualizations.
