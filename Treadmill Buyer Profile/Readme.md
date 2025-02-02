## **1. Understanding the Dataset**

Before doing any analysis, it's crucial to **understand the dataset** by looking at:

- **Columns & Rows** – How many features (columns) and observations (rows) exist?
- **Data Types** – Identifying whether columns are numerical (int, float) or categorical (object, string).
- **Uniqueness** – Checking unique values in categorical columns (e.g., Gender, Age Group) and distributions of numerical columns.

**Goal:** Get a clear picture of what data you're working with.

---

## **2. Preprocessing (Data Cleaning & Preparation)**

### **A. Changing Data Types**

- Convert **categorical data into numerical** using:
    - One-hot encoding (for non-ordinal categories like Gender)
    - Label encoding (for ordinal categories like Age Groups)

### **B. Dropping Irrelevant Columns**

- Remove columns that do not contribute to analysis (e.g., Customer ID).

### **C. Handling Null Values**

- Drop rows or columns with excessive missing values.
- Fill missing values using:
    - **Mean/Median** (for numerical data)
    - **Mode** (for categorical data)
    - **Forward/Backward fill** (for time-series data)

**Goal:** Ensure the dataset is clean and ready for analysis.

---

## **3. Exploratory Data Analysis (EDA) & Visualization**

Here, you analyze and visualize data patterns.

### **A. Count Plots**

- Useful for categorical data like `Gender`, `Occupation`, `Marital Status`.
- Helps understand distributions.

### **B. Univariate Analysis (One Variable at a Time)**

#### **1. Numerical Variables**

- **Distribution Plot (Distplot)** → Shows data spread.
- **Count Plot** → For categorical data.
- **Box Plot** → Detects outliers and median values.

#### **2. Categorical Variables**

- **Bar Charts & Pie Charts** → Visualizing frequency distributions.

### **C. Bivariate Analysis (Two Variables at a Time)**

- **Count Plot** → Comparing categories (e.g., Gender vs. Purchase)
- **Box Plot** → Analyzing numeric distribution across categories.

### **D. Multivariate Analysis (More than Two Variables)**

- Pairwise relationships using **pair plots**.
- Grouping features for deeper insights.

---

## **4. Correlation Analysis**

Find relationships between numerical variables.

### **A. Correlation Matrix**

- Shows how strongly two features are related (values range from -1 to 1).

### **B. Heatmap**

- A visual representation of correlation to detect strong/weak relationships.

**Goal:** Identify the most relevant features that impact customer behavior.
