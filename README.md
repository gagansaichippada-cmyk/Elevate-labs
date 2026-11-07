Task 1: Data Cleaning & Preprocessing

Internship Project – Elevate Labs

1. Project Overview

The objective of this project is to understand and perform data cleaning and preprocessing using Python. Data preprocessing is an important step in Machine Learning because raw datasets may contain missing values, categorical data, and outliers.

In this project, I used the Titanic dataset and performed different preprocessing techniques to prepare the data for Machine Learning.

2. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

3. Dataset Information

Dataset Name: Titanic Dataset

Dataset Source: "Titanic Dataset – https://www.kaggle.com/datasets/yasserh/titanic-dataset
- Total Records: 891
- Original Columns: 12
- Final Columns: 13
- Dataset Format: CSV

The dataset contains passenger information such as age, gender, passenger class, ticket fare, cabin, and survival status.

4. Project Structure

Task_1_Data_Cleaning/
│
├── dataset/
│   └── Titanic-Dataset.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── outputs/
│   └── cleaned_titanic.csv
│
├── screenshots/
│
└── README.md

5. Data Cleaning & Preprocessing Steps

The following operations were performed:

1. Importing Libraries

- Imported Pandas and NumPy for data manipulation.
- Imported Matplotlib and Seaborn for visualization.
- Imported Scikit-learn for feature scaling.

2. Dataset Exploration

- Displayed the first and last records.
- Checked dataset dimensions.
- Examined column names and data types.
- Generated statistical summaries.
- Identified missing values and duplicate records.

3. Handling Missing Values

- Age: Filled missing values using Median.
- Cabin: Filled missing values with "Unknown".
- Embarked: Filled missing values using Mode.

4. Categorical Encoding

Used One-Hot Encoding to convert categorical columns into numerical values.

- Sex
- Embarked

5. Feature Scaling

Applied Min-Max Normalization to:

- Age
- Fare

This transforms the numerical values into a range between 0 and 1.

6. Outlier Detection

Used boxplots to visualize potential outliers in Age and Fare columns.

7. Outlier Handling

Applied the Interquartile Range (IQR) method and used outlier capping to limit extreme values.

8. Final Dataset Verification

- Checked missing values.
- Checked duplicate records.
- Verified dataset dimensions.
- Reviewed the cleaned dataset.

9. Exporting Cleaned Dataset

Saved the final cleaned dataset as:

"outputs/cleaned_titanic.csv"

6. Final Results

Description| Result
Original Records| 891
Original Columns| 12
Final Records| 891
Final Columns| 13
Remaining Missing Values| 0
Duplicate Records| 0

7. How to Run the Project

Step 1: Clone or download this repository.

Step 2: Install the required libraries.

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Step 3: Open the project in VS Code.

Step 4: Open the Jupyter Notebook:

"notebooks/data_cleaning.ipynb"

Step 5: Run all notebook cells.

Step 6: Find the cleaned dataset in the outputs folder.

8. Learning Outcomes

Through this project, I learned:

- How to import and explore datasets using Pandas.
- How to identify and handle missing values.
- How to perform categorical encoding.
- How to apply feature scaling.
- How to visualize and detect outliers.
- How to handle outliers using the IQR method.
- How to export cleaned datasets into CSV format.

9. Conclusion

This project helped me understand the importance of data cleaning and preprocessing in Machine Learning.

I successfully performed missing value handling, categorical encoding, feature scaling, outlier detection, and outlier treatment using Python.

The final cleaned dataset was saved in CSV format and is ready for further data analysis and machine learning experiments.

---

Project: Task 1 – Data Cleaning & Preprocessing
Internship: Elevate Labs
Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
