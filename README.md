PROJECT DOCUMENTATION

Food Delivery Analysis Using Python

Console-Based Order and Delivery Data Processing

1. Introduction

Food Delivery Analysis is a Python-based project that loads and processes food delivery order records from a CSV file using Pandas and foundational Python constructs. It cleans duplicate and missing entries, categorizes delivery metrics, computes group and overall averages, and exports cleaned output files without external visualization libraries.

2. Objectives of the Project

* To understand how Python works with tabular food delivery datasets.

* To load and process CSV files using Pandas, functions, lists, dictionaries, and sets.

* To handle duplicate rows and missing numeric or text values cleanly.

* To categorize delivery time, order value, or delay status using loops and conditionals.

* To calculate group averages, overall averages, and set overlaps in the console.

* To export cleaned records and summary results to output files.

3. Technologies Used

* Programming Language: Python

* Libraries: Pandas, NumPy

* Platform: Google Colab

* Dataset Format: CSV (`food_delivery_dataset.csv`)

4. Working of the Code

Step 1 — Load Dataset: Reads the food delivery CSV dataset into a Pandas DataFrame.

Step 2 — Clean Data: Removes duplicate order rows and fills missing numeric values (such as delivery time, distance, or order amount) using column medians and missing text values using a default label.

Step 3 — Add Labels: Uses loops and if/elif/else conditions to classify orders into clear tiers (for example, delivery time or order value bands) and risk/delay categories.

Step 4 — Summarize & Export: Counts order statuses using a dictionary, prints group averages by category alongside a total overall average line, checks cohort overlaps using sets, and saves cleaned data and a summary text report.

5. Software Development Life Cycle (SDLC)

Phase 1 — Planning: Plan a concise, beginner-friendly Python script to clean and summarize food delivery records in the console.

Phase 2 — Requirement Analysis: Hardware: laptop or computer with internet access. Software: Python, Google Colab, Pandas, NumPy, and a food delivery CSV dataset.

Phase 3 — System Design: Input: food delivery CSV file. Processing: duplicate removal, missing-value handling, rule-based labeling, dictionary counts, group/total averages, and set checks. Output: console summary and exported CSV/text files.

Phase 4 — Implementation: Implemented using modular functions, lists, dictionaries, sets, loops, conditionals, and Pandas operations.

Phase 5 — Testing: Verified file loading, missing-file error handling, duplicate removal, median imputation, group and overall averages, and output file creation.

Phase 6 — Deployment: Executed in Google Colab with the dataset placed in the working directory or stored separately in the project repository.

Phase 7 — Maintenance: Extendable by adding new order datasets, refining category thresholds, or adding more summary breakdowns.

6. Expected Output

* Cleaned record count after removing duplicate rows and handling missing values.

* Dictionary-based counts across order or delivery status categories.

* Group averages by category plus an overall total average line across all records.

* Set comparison counts for overlapping order or delivery cohorts.

* Saved cleaned CSV dataset and summary text output.

7. Advantages

* Easy to read, run, and explain using core Python and Pandas concepts.

* Handles dirty data (duplicates and missing entries) before computing averages.

* Combines category-level averages with an overall total average for clear comparison.

* Generates both console output and saved files.

8. Limitations

* Requires a valid food delivery CSV file in the active working directory.

* Uses fixed rule thresholds rather than predictive modeling.

* Does not generate visual charts or graphs.

9. Future Scope

* Zone-wise, restaurant-wise, or peak-hour delivery comparisons.

* Additional operational metrics such as preparation time, delivery distance, and ratings.

* Testing across larger multi-day or multi-city delivery datasets.

10. Conclusion

The Food Delivery Analysis project demonstrates practical data cleaning, rule-based labeling, dictionary and set usage, group and overall averaging, and file export in Python. It offers a clear, structured foundation for beginner data analysis projects.

11. Dataset File

Separate dataset file: `food_delivery_dataset.csv`.

Place the CSV file in the working directory or repository before running the script.# Food_Delivery_and_Order_Analysis_HCL
