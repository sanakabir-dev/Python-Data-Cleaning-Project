# 📊 DecodeLabs Project 1 – Data Cleaning & Preparation

## 📌 Overview

This project was completed as part of the **DecodeLabs Industrial Training Program**.

The objective of this project was to clean and prepare a raw dataset by identifying missing values, verifying data integrity, standardizing data formats, and validating business rules using **Python** and **Pandas**.

---

## 🎯 Project Objectives

- Identify missing values
- Handle missing data appropriately
- Detect duplicate records
- Verify unique Order IDs
- Standardize date formats
- Clean text fields
- Validate business logic
- Export a clean dataset

---

## 📂 Dataset Information

- **Total Records:** 1200
- **Total Columns:** 14

### Features

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- OrderStatus
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- Microsoft Excel

---

## 🔄 Data Cleaning Workflow

### 1️⃣ Data Inspection

- Loaded dataset
- Examined structure
- Checked data types
- Generated descriptive statistics

### 2️⃣ Missing Value Handling

The **CouponCode** column contained missing values.

Instead of deleting these records, missing values were replaced with:

```
No Coupon
```

This preserves business meaning because a missing coupon code indicates that no coupon was used.

### 3️⃣ Duplicate Verification

- Checked duplicate rows
- Checked duplicate Order IDs

No duplicate records were found.

### 4️⃣ Data Standardization

Performed:

- Date standardization
- Text trimming
- Title Case conversion
- Data type verification

### 5️⃣ Business Logic Validation

Validated the following relationship:

```
TotalPrice = Quantity × UnitPrice
```

Rounded comparison was used to avoid floating-point precision issues.

---

## ✅ Final Validation Results

| Validation | Status |
|------------|--------|
| Missing Values | ✅ Completed |
| Duplicate Rows | ✅ No Duplicates Found |
| Duplicate Order IDs | ✅ Unique |
| Date Format | ✅ Standardized |
| Text Formatting | ✅ Standardized |
| Business Logic Validation | ✅ Passed |

---

## 📈 Key Insights

- The dataset contains **1,200 customer orders**.
- All missing values were successfully handled.
- No duplicate records or duplicate Order IDs were found.
- The dataset is clean and ready for analysis.
- Coupon usage information has been preserved.
- Business logic validation confirmed data consistency.


---

## 💼 Skills Demonstrated

- Data Cleaning
- Data Validation
- Data Wrangling
- Exploratory Data Analysis
- Python Programming
- Pandas
- Excel
- Google Colab

---

## 🎯 Conclusion

This project demonstrates a complete data cleaning workflow using Python and Pandas. The dataset was successfully prepared for future exploratory data analysis, visualization, and machine learning applications by ensuring consistency, accuracy, and data integrity.
