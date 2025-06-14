# EDA_Superstore_Sales_dataset
# 📦 SuperStore Dataset - Exploratory Data Analysis (EDA)

## 🧹 Data Preprocessing (Using pandas)
- Converted `order_date` and `ship_date` columns to datetime format.
- Converted `sales` and `quantity` columns to numeric data types.
- Checked and removed duplicate rows.
- Checked for and handled missing values.
- Ensured proper data types across all columns.

## 🔁 Data Transformation
- Created new feature `shipping_days` to capture the difference between ship and order dates.
- Created `profit_margin` as `profit / sales` to evaluate profitability.
- Extracted `month` from `order_date` for time-series analysis.

## 📊 Statistical Functions (Using NumPy)
- Mean, Median, and Standard Deviation of key metrics:
  - Profit, Sales, Discount, Quantity.
- Correlation matrix to find relationships between numeric variables.
- Skewness and Kurtosis of the Profit column for distribution analysis.

## 🔎 Analytical Questions Answered with Visualizations

### 1. 📈 Total Profit by Sub-Category
- **Objective:** Identify which sub-categories yield the most profit.
- **Visualization:** Bar plot using `seaborn`.

### 2. 📅 Monthly Sales Trend
- **Objective:** Understand sales trends over time.
- **Visualization:** Line plot of total monthly sales.

### 3. 🔁 Profit vs Discount Analysis
- **Objective:** Evaluate the effect of discount on profit.
- **Visualization:** Scatter plot of discount vs. profit.

### 4. 👥 Segment-wise Sales Distribution
- **Objective:** Understand how sales vary across different customer segments.
- **Visualization:** Box plot for each segment.

### 5. 🚚 Shipping Time Distribution
- **Objective:** Analyze how long it takes to ship products.
- **Visualization:** Histogram of shipping days.

## 🛠 Libraries Used
- `pandas` for data manipulation
- `numpy` for statistical operations
- `matplotlib` and `seaborn` for data visualization

---

**Note:** This analysis provides valuable insights into customer behavior, product profitability, and shipping efficiency, which can aid in better business decisions.

**Author**
Shubham Jagtap
BSc Data Science
