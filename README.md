# Universal Data Cleaning & Preparation Jupyter Notebook Template

This is a comprehensive and reusable Jupyter Notebook template designed to accelerate the most time-consuming part of any data science project: **data cleaning and preprocessing**. 

Stop writing the same cleaning code for every project! This template provides a step-by-step, well-documented pipeline to take your raw tabular data (from a `.csv` file) and turn it into a clean, fully numeric format ready for machine learning modeling.

---

### Who is this for?

* **Aspiring Data Scientists & Students:** Learn how a professional data cleaning workflow is structured and use this as a starting point for your own portfolio projects.
* **Junior Data Analysts:** Speed up your work by using this template instead of starting from scratch. Impress your team with clean, reliable, and well-documented preprocessing.
* **Small Business Owners & Researchers:** You have data in Excel/CSV but don't have the budget for a full-time data scientist. Use this guided template to prepare your data for analysis yourself.

---

### Features & Included Steps

This notebook guides you through the most critical preprocessing tasks:

✅ **Data Loading:** Easily load your dataset with a simple configuration and error handling for missing files.

✅ **Handling Incorrect Data Types:** A common issue where numeric columns are read as text. This template includes a function to automatically find and fix them.

✅ **Managing Missing Values:** Impute (fill) missing numerical data using the column mean, a robust and standard technique.

✅ **Categorical Data Encoding:**
* **Binary Encoding:** Automatically converts columns with two categories (e.g., Yes/No, Male/Female) to `0`s and `1`s.
* **One-Hot Encoding:** Automatically converts columns with more than two categories into a model-ready format using `pd.get_dummies`.

✅ **Well-Documented:** Every step is explained with Markdown cells, detailing what the code does and what actions you need to take.

---

### How to Use

1.  Download the `.ipynb` file from this repository.
2.  Place your own data file (e.g., `my_data.csv`) in the same folder.
3.  Open the notebook and update the `file_path` variable in the first code cell to point to your data file.
4.  Update the configuration in the "Encode Categorical Data" section to list your binary and target columns.
5.  Run the cells from top to bottom!
