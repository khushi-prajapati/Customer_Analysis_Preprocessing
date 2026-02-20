Task 1: Data Cleaning and Preprocessing  

Dataset Used  
Customer Personality Analysis (Kaggle Dataset)
This dataset contains customer demographic details, income information, spending behavior, and campaign responses.

Objective  
The objective of this task was to clean and preprocess a raw dataset by handling missing values, removing duplicates, correcting data types, standardizing text formats, and preparing the dataset for further analysis or modeling.

Tools & Technologies Used  
- Python  
- Pandas  
- Google Colab  

Data Cleaning Steps Performed  

1. Checked dataset shape and structure  
2. Identified and handled missing values  
   - Filled missing **Income** values using median imputation  
3. Removed duplicate records  
4. Standardized column names (converted to lowercase and replaced spaces with underscores)  
5. Converted `Dt_Customer` column to proper datetime format  
6. Created a new feature `Age` using `Year_Birth`  
7. Removed unrealistic age values (outlier treatment)  
8. Standardized categorical columns (`Education`, `Marital_Status`)  
9. Verified and corrected data types  
10. Saved cleaned dataset for further analysis  

Key Improvements Made  
- Ensured consistent formatting across dataset  
- Reduced inconsistencies and improved data quality  
- Created a new meaningful feature (`Age`)  
- Prepared dataset for data analysis and machine learning
- 
Final Result  

A clean, structured, and analysis-ready dataset prepared using proper data preprocessing techniques.

