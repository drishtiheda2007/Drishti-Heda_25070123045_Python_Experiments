# 🧹 Data Preprocessing and Handling Missing Values in Python

## 👤 Student Details
- **Name:** Drishti Heda 
- **Branch:** EnTC A3  
- **PRN:** 25070123045  

---

## 📄 Experiment Details
- **Experiment Name:** Data Preprocessing and Handling Missing Values in Python  
- **Purpose:** Study of data preprocessing techniques and handling missing data using Python  
- **Programming Language:** Python  

---

## 🎯 Aim
To understand data preprocessing techniques and learn how to identify, handle, and clean missing values in a dataset using Python and the Pandas library.

---

## 📌 Introduction
Data preprocessing is a crucial step in data analysis and machine learning.  
Real-world datasets often contain missing, inconsistent, or noisy data, which can negatively affect analysis and model performance.

Handling missing values properly ensures:
- Better data quality  
- Accurate results  
- Reliable models  

Python provides powerful libraries like **Pandas** and **NumPy** to efficiently preprocess and clean data.

---

## 📖 Procedure (Steps)
1. Import necessary libraries (Pandas, NumPy)  
2. Load dataset into a DataFrame  
3. Identify missing values  
4. Analyze missing data patterns  
5. Apply techniques to handle missing values  
6. Perform data cleaning and transformation  
7. Verify the final dataset  

---

## 🔑 Key Concepts
- Data Preprocessing  
- Missing Values  
- Data Cleaning  
- Data Transformation  
- Imputation Techniques  
- Data Consistency  

---

## 📘 Theory

### 1. Identifying Missing Values
```python
df.isnull()
df.isnull().sum()

---

### 2. Removing Missing Values
Rows or columns containing missing values can be removed using:

```python
df.dropna()

---

### ✅ **3. Filling Missing Values**
```markdown id="sec3fill"
### 3. Filling Missing Values
Missing values can be replaced using appropriate statistical methods:

- **Fill with Mean**
```python
df.fillna(df.mean())

- **Fill with Median**
```python
df.fillna(df.median())


### ✅ **Fill with Mode**
```markdown
- **Fill with Mode**
```python
df.fillna(df.mode().iloc[0])


### ✅ **Fill with Constant Value**
```markdown
- **Fill with Constant Value**
```python
df.fillna(0)


---

### ✅ **4. Forward Fill and Backward Fill**
```markdown
### 4. Forward Fill and Backward Fill

- **Forward Fill (propagates previous value forward)**
```python
df.fillna(method='ffill')


### ✅ **Backward Fill (same style)**
```markdown
- **Backward Fill**
```python
df.fillna(method='bfill')

---

### ✅ **5. Data Transformation**
```markdown
### 5. Data Transformation
After handling missing values, data can be transformed for better analysis:

```python
df['Column'] = df['Column'].astype(int)

---

### ✅ **6. Checking Cleaned Data**
```markdown
### 6. Checking Cleaned Data
After preprocessing, verify that no missing values remain:

```python
df.isnull().sum()
---

## 📊 Dataset Used
The dataset used in this experiment contains:
- Numerical columns  
- Categorical columns  
- Missing values in different fields  
- Real-world structured data for preprocessing practice  

This dataset is used to demonstrate various data cleaning and preprocessing techniques.

---

## 🛠 Tools Used
- Python  
- Jupyter Notebook  
- Pandas Library  
- NumPy Library  
- VS Code / Google Colab  

---

## 📂 Applications of Data Preprocessing
- Machine Learning model preparation  
- Data cleaning in real-world datasets  
- Business analytics  
- Data science projects  
- Improving data quality  

---

## 🎯 Conclusion
Data preprocessing is a fundamental step in any data analysis workflow.

Handling missing values properly ensures that the dataset is:
- Clean  
- Reliable  
- Ready for analysis or machine learning  

This experiment demonstrated:
- Removing missing values  
- Filling missing values  
- Data transformation  

These techniques are essential for working with real-world datasets.

---

## 📎 Extra Notes
- Always analyze missing data before handling it  
- Choose appropriate imputation technique  
- Avoid unnecessary data loss  
- Clean data improves model accuracy  
- Practice preprocessing techniques regularly  

---

## ✨ THANK YOU
