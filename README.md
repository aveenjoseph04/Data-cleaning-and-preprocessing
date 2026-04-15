# Data Cleaning and Preprocessing Project

## 📌 Overview

This project demonstrates basic **data cleaning and preprocessing techniques** using Python and pandas.
The dataset used contains customer information, and the script performs tasks such as:

* Handling duplicates
* Exploring unique values
* Cleaning text data
* Formatting dates
* Standardizing phone numbers

---

## 📂 Dataset

* File: `customers-100.csv`
* Make sure the dataset is placed in the correct path or update the file path in the script:

  ```python
  df = pd.read_csv("D:/internship/customers-100.csv")
  ```

---

## ⚙️ Requirements

Install the following before running the project:

* Python (3.x)
* pandas

Install pandas using:

```bash
pip install pandas
```

---

## 🚀 How to Run

1. Clone or download this project.
2. Open the Python script in your IDE (VS Code, Jupyter Notebook, etc.).
3. Update the dataset path if needed.
4. Run the script.

---

## 🧹 Steps Performed

### 1. Load Data

* Read CSV file using pandas

### 2. Data Exploration

* View first few rows (`head()`)
* Check structure (`info()`)
* Identify duplicates

### 3. Data Analysis

* Find unique values
* Count distinct entries
* Analyze frequency of names

### 4. Data Cleaning

* Create `Full Name` column
* Remove unnecessary columns:

  * First Name
  * Last Name
  * Customer Id
  * Phone 2

### 5. Handle Missing Values

* Count null values using `isna().sum()`

### 6. Data Formatting

* Convert `Subscription Date` to datetime format

### 7. Text Standardization

* Convert columns to lowercase:

  * Company
  * City
  * Country
  * Full Name

### 8. Phone Number Cleaning

* Remove non-digit characters from phone numbers

### 9. Duplicate Check

* Count total duplicate rows

---

## 📊 Output

The cleaned dataset includes:

* Standardized text
* Proper date format
* Clean phone numbers
* Removed unnecessary columns

---

## 📝 Notes

* Ensure the dataset path is correct before running.
* You can extend this project by:

  * Handling missing values
  * Visualizing data
  * Exporting cleaned data to a new file

---

## 📌 Author

Aveen Joseph
