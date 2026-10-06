# Pandas Hands-On Data Analysis Projects

A practical portfolio documenting four hands-on data analysis projects completed using **Python, Pandas, NumPy, and Jupyter Notebook**.

The projects are designed around real-world-style datasets and focus on the complete analytical workflow: **data inspection → data cleaning → transformation → analysis → interpretation**.

---

## About This Repository

This repository documents my practical progression in **Python and Pandas for data analysis**.

Across the four hands-on exercises, I work with different datasets and business scenarios to develop practical skills in:

- Loading and inspecting datasets
- Understanding dataset structure
- Identifying missing values
- Detecting and handling incorrect values
- Identifying duplicate records
- Converting data types
- Creating new analytical variables
- Applying business rules
- Using frequency tables
- Grouping and aggregating data
- Comparing groups
- Identifying meaningful patterns
- Translating analytical findings into business recommendations

The goal is not only to produce numerical results, but also to understand **why the results matter and what they suggest for further investigation**.

---

# Tools and Technologies

| Tool | Purpose |
|---|---|
| **Python** | Programming and data analysis |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical operations and conditional transformations |
| **Jupyter Notebook** | Interactive analysis and documentation |
| **GitHub** | Version control and portfolio documentation |

---

# Projects

## Exercise 1 — Data Analysis

**Focus:** Data inspection, cleaning and basic analysis

This exercise introduces the fundamental Pandas workflow used throughout the portfolio.

### Key activities

- Loading a dataset
- Inspecting rows and columns
- Checking data types
- Identifying missing values
- Examining categorical variables
- Cleaning problematic data
- Performing basic analysis

### Skills demonstrated

`Pandas` · `Data Inspection` · `Data Cleaning` · `Missing Values` · `Basic Analysis`

### Screenshot

<img width="1896" height="758" alt="Screenshot 2026-10-06 215059" src="https://github.com/user-attachments/assets/faf3f236-ead0-4798-bb8f-c2bab6151efa" />
<img width="1896" height="603" alt="Screenshot 2026-10-06 215139" src="https://github.com/user-attachments/assets/cbe73a28-dc1f-4334-8c70-261af2b71754" />
<img width="1884" height="704" alt="Screenshot 2026-10-06 215301" src="https://github.com/user-attachments/assets/5a25deb2-77cf-4e4e-9b36-92cc21d80d30" />
<img width="1852" height="642" alt="Screenshot 2026-10-06 215330" src="https://github.com/user-attachments/assets/cd8db932-e008-4c4b-87a4-dc628aefc0c6" />

<img width="1884" height="704" alt="Screenshot 2026-10-06 215301" src="https://github.com/user-attachments/assets/ea6f1579-ac80-4946-9b36-25c12c41d69f" />



---

# Exercise 2 — Data Analysis

**Focus:** Data transformation and analytical exploration

This exercise builds on the foundational Pandas skills developed in Exercise 1 and introduces additional data transformation and analysis techniques.

### Key activities

- Dataset inspection
- Data cleaning
- Data transformation
- Creating analytical variables
- Frequency analysis
- Group-based analysis
- Interpretation of findings

### Skills demonstrated

`Pandas` · `Data Transformation` · `Grouping` · `Aggregation` · `Data Analysis`

### Screenshot

<img width="1834" height="710" alt="Screenshot 2026-10-06 215855_2" src="https://github.com/user-attachments/assets/864b73f6-f4e4-4777-9137-b4555284bf51" />
<img width="1905" height="743" alt="Screenshot 2026-10-06 215933" src="https://github.com/user-attachments/assets/6a378e5e-3a04-458b-b8d8-463a040269da" />
<img width="1859" height="601" alt="Screenshot 2026-10-06 215605" src="https://github.com/user-attachments/assets/835ea241-8d18-4d0c-a3bd-50ab58b88c44" />
<img width="1875" height="716" alt="Screenshot 2026-10-06 215641_2" src="https://github.com/user-attachments/assets/6eb5c8f6-d679-407d-a999-a3f16771eeac" />
<img width="1891" height="640" alt="Screenshot 2026-10-06 215813" src="https://github.com/user-attachments/assets/3218186a-3f92-4cba-a538-7c91131cff80" />

---

# Exercise 3 — Financial Transactions Analysis

**Industry:** Banking / Financial Services

### Scenario

A financial institution collected transaction information from its customers and wanted to understand transaction patterns while ensuring that the dataset was suitable for analysis.

The exercise focused on identifying and resolving data-quality issues before generating analytical insights.

### Dataset

The dataset contained information including:

- Customer ID
- Customer Name
- City
- Transaction Type
- Amount
- Account Status

### Data Cleaning

The dataset initially contained **3,000 records and 6 columns**.

Several data-quality issues were identified during the cleaning process, including:

- Missing values
- Invalid transaction amounts
- Text values appearing in the numerical amount field
- Typographical errors
- Zero transaction amounts
- Negative transaction amounts
- Duplicate records

The transaction amount field required particular attention because it contained values such as:

- `Not Available`
- `Error`
- `Pending`
- `Unknown`
- `1O000`
- `##VALUE!`
- `0`
- `-2500`
- `₦12,500`

These values were investigated and cleaned before analysis.

### Analytical Transformation

A new variable called `Transaction_Category` was created using a business rule:

- Transactions **≥ 100,000** → `Large Transaction`
- Transactions **< 100,000** → `Regular Transaction`

### Key Findings

After cleaning and transformation:

| Transaction Category | Number of Transactions | Average Transaction Amount |
|---|---:|---:|
| Regular Transaction | 2,538 | 30,492.60 |
| Large Transaction | 276 | 179,186.56 |

The analysis showed that large transactions had a substantially higher average transaction amount than regular transactions.

### Additional Analysis

Transaction amounts were also examined by:

- Transaction Type
- City
- Transaction Category

The analysis helped identify differences in transaction behaviour across customer locations and transaction types.

### Skills demonstrated

`Pandas` · `Data Cleaning` · `Data Type Conversion` · `Missing Values` · `Duplicate Detection` · `Conditional Classification` · `GroupBy` · `Aggregation`

### Screenshots

<img width="1847" height="720" alt="Screenshot 2026-10-06 221148" src="https://github.com/user-attachments/assets/76667c26-631c-4ece-902b-a53cbd312e3d" />


<img width="1887" height="708" alt="Screenshot 2026-10-06 221232" src="https://github.com/user-attachments/assets/5290cf0c-1730-4542-ab74-df5ebf0543ee" />


<img width="1899" height="707" alt="Screenshot 2026-10-06 221049" src="https://github.com/user-attachments/assets/a8981f0b-a2de-48e8-b3d4-66e19a20d26d" />


<img width="1901" height="728" alt="Screenshot 2026-10-06 221302" src="https://github.com/user-attachments/assets/2ed9191e-aa60-405f-b8ad-a4d76f29548b" />


<img width="1896" height="714" alt="Screenshot 2026-10-06 221422" src="https://github.com/user-attachments/assets/f1204ad9-d5e8-462b-aa96-84d4c2f10f00" />

---

# Exercise 4 — Energy Consumption Analysis

**Industry:** Energy / Utilities

## Scenario

An energy company collected electricity consumption information from customers and wanted to understand consumption patterns across different customer groups.

The dataset contained:

- Customer ID
- City
- Customer Type
- Monthly Consumption
- Account Status
- Energy Source

The objective was to clean the dataset and transform the raw information into useful analytical insights.

---

## Part A — Understanding the Data

The dataset initially contained:

**3,012 records × 6 columns**

All six variables were initially stored as `object` data types because the dataset contained mixed and problematic values.

Initial inspection identified:

- Missing city values
- Missing customer types
- Missing consumption values
- Missing account statuses
- Missing energy sources
- Invalid text values in the consumption field
- Duplicate customer records

---

## Part B — Data Cleaning

Several data-quality issues were investigated and addressed.

### Missing Values

Missing values were identified across the dataset.

Categorical missing values in:

- City
- Customer Type
- Account Status
- Energy Source

were handled appropriately.

Where the categorical information could not be reliably determined, the value was labelled:

`Unknown`

<img width="1864" height="717" alt="Screenshot 2026-10-06 222106" src="https://github.com/user-attachments/assets/48a7640f-3456-4c1d-af76-7fd969b2341f" />
<img width="1872" height="711" alt="Screenshot 2026-10-06 222213" src="https://github.com/user-attachments/assets/1618d6b2-1c75-42da-9975-ce3440474a21" />

<img width="1815" height="701" alt="Screenshot 2026-10-06 222312" src="https://github.com/user-attachments/assets/cf3a23cd-a924-4eba-917c-6b53393205f7" />

<img width="1880" height="736" alt="Screenshot 2026-10-06 222611" src="https://github.com/user-attachments/assets/4ff7e0ee-eef8-4743-9fb0-a1c67a90eefd" />


<img width="1884" height="716" alt="Screenshot 2026-10-06 222423" src="https://github.com/user-attachments/assets/cecdc53d-c181-4c20-b8fb-1de288444ab9" />



### Monthly Consumption

The `Monthly Consumption` field contained several invalid values, including:

```text
Pending
Unknown
Error
No Reading
12O
5,2O0
##VALUE!
