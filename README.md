# netflix-data-cleaning
Data Cleaning and Preprocessing Internship Task using Netflix Dataset.
# Netflix Data Cleaning and Preprocessing Project

## Internship Task 1 – Data Analyst Internship

### Project Objective
The objective of this task is to clean and preprocess a raw dataset by identifying and fixing common data quality issues such as missing values, duplicate records, inconsistent formatting, and incorrect data types.

---

## Dataset Used

Dataset Name: Netflix Movies and TV Shows Dataset

This dataset contains information about Netflix content including movies and TV shows, directors, cast members, country, release year, rating, duration, and date added.

---

## Tools Used

- Microsoft Excel
- Python (Pandas Library)
- GitHub

---

## Data Cleaning Steps Performed

### 1. Handling Missing Values
Checked for empty or null values in the dataset.

Missing values were found in:
- Director
- Cast
- Country
- Rating
- Duration
- Date Added

Actions taken:
- Filled missing Director values with **Unknown**
- Filled missing Cast values with **Not Available**
- Filled missing Country values with **Unknown**
- Filled missing Rating values with **Not Rated**
- Filled missing Duration values with **Unknown**

---

### 2. Removing Duplicate Records
- Checked for duplicate rows in the dataset
- Removed repeated records to avoid redundancy

---

### 3. Standardizing Text Formatting
Standardized text values to maintain consistency.

Examples:
- Removed unnecessary spaces
- Standardized values in Type column
- Cleaned Country and Rating column formatting

---

### 4. Date Format Correction
The **date_added** column had inconsistent date formats.

Action taken:
- Converted all dates into a standard format:

DD-MM-YYYY

Example:

September 9, 2019 → 09-09-2019

---

### 5. Cleaning Column Headers
Renamed column headers into a cleaner format.

Rules used:
- Converted all letters to lowercase
- Removed spaces
- Added underscore (_) between words

Example:

Date Added → date_added  
Release Year → release_year

---

### 6. Data Consistency Check
Verified dataset for:
- Incorrect values
- Formatting issues
- Blank cells
- Structural consistency

---

## Files Included in Repository

- netflix_titles.csv → Original dataset  
- netflix_cleaned.xlsx → Cleaned dataset  
- README.md → Project documentation  

---

## Outcome

The Netflix dataset was successfully cleaned and preprocessed.

The dataset is now:
- Structured properly
- Free from duplicate records
- Free from major missing values
- Standardized for analysis
- Ready for data visualization and future machine learning tasks

---

## Conclusion

Data cleaning is an important step in data analysis. By completing this task, raw and inconsistent data was transformed into a clean and organized dataset that can be used for accurate analysis and decision making.

This task improved understanding of handling real-world datasets and applying preprocessing techniques effectively.
