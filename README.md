# ✈️ Travel & Tourism Analysis | Python EDA

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of travel and tourism booking data to identify customer preferences, booking trends, cancellation patterns, travel costs, and business opportunities using Python.

The analysis helps understand customer behavior and provides actionable insights to support data-driven business decisions.

## 🎯 Project Objectives

- Analyze customer demographics and booking patterns.
- Identify popular transportation types, meal plans, and payment methods.
- Explore travel seasonality and cost variations.
- Investigate booking cancellations and their reasons.
- Understand the relationship between trip costs and travel characteristics.
- Perform statistical hypothesis testing to compare travel costs by gender.
- Provide actionable business recommendations.

## 📂 Dataset Overview

- **Total Records:** 1,000 bookings
- **Total Columns:** 29
- **Missing Values:** 0 reported in the original notebook
- **Duplicate Rows:** 0 reported in the original notebook

### Key Dataset Features

Customer details, booking dates, travel dates, destination information, hotel ratings, number of travellers, room requirements, meal plans, payment methods, booking status, cancellation reasons, customer ratings, and total trip costs.

## 🛠️ Technologies & Libraries

- **Python** – Data analysis
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SciPy** – Statistical hypothesis testing
- **Jupyter Notebook** – Interactive analysis

## 🔍 Analysis Performed

### 1. Data Exploration & Cleaning
- Inspected dataset structure and data types.
- Reviewed descriptive statistics and category frequencies.
- Checked missing values and duplicate records.
- Converted date columns into datetime format.

### 2. Customer Analysis
- Analyzed customer distribution by gender and country.
- Identified major customer markets.
- Examined customer age and travel group characteristics.

### 3. Booking & Travel Preferences
- Analyzed booking status and cancellation status.
- Identified popular transportation types.
- Compared meal plans and payment methods.
- Examined customer review comments.

### 4. Time-Based Analysis
- Analyzed monthly and yearly travel distributions.
- Explored seasonal travel patterns.
- Created a heatmap to examine trip-cost variations by booking day and month.

### 5. Correlation Analysis
- Studied relationships between trip cost, travellers, rooms, discounts, and customer age.
- Used a correlation heatmap to identify important relationships.

### 6. Cancellation Analysis
- Calculated the overall cancellation rate.
- Examined cancellation reasons.
- Identified potential opportunities to improve booking retention.

### 7. Statistical Hypothesis Testing
- Applied Welch's independent two-sample t-test.
- Compared average travel costs between male and female customers.
- Interpreted the p-value using a 5% significance level.

## 📊 Key Insights

- **India** accounts for 65.5% of customer bookings (655 bookings).
- **Flights** represent 68.2% of transportation choices (682 bookings).
- **77.2%** of bookings are marked Completed (772 bookings).
- The overall cancellation rate is **14.1%** (141 bookings).
- **Breakfast Included** is the most common meal plan, with 392 bookings.
- **UPI** is the most frequently used payment method, with 297 bookings.
- The mean total trip cost is approximately **227,838.9**, while the median is **157,200** in the dataset's unspecified currency units.
- Total trip cost has a moderate positive correlation with the number of rooms (0.54) and travellers (0.53).
- Welch's t-test returned a p-value of **0.36**. At a significance level of 0.05, the analysis did not find a statistically significant difference in average trip cost by gender.

## 💡 Business Recommendations

1. Focus marketing campaigns and package planning on the Indian customer market.
2. Use seasonal trends to improve pricing, staffing, and inventory planning.
3. Investigate cancellation journeys related to family emergencies, transportation disruptions, visa issues, and budget constraints.
4. Improve service quality and travel arrangements based on customer feedback.
5. Develop packages based on group size, room requirements, and transportation preferences.
6. Monitor booking completion, cancellation rate, customer ratings, and average trip cost over time.

## 📁 Project Structure

| File Name | Description |
|---|---|
| `Travel_Tourism.csv` | Dataset containing 1,000 travel and tourism booking records with 29 columns. |
| `Travel_Tourism_Analysis.ipynb` | Jupyter Notebook containing data cleaning, EDA, visualizations, correlation analysis, and hypothesis testing. |
| `Travel_Tourism_Analysis_Report.pdf` | Detailed project report summarizing the analysis, visualizations, findings, and insights. |
| `Travel_Tourism_Analysis_Presentation.pptx` | Presentation highlighting key findings, business insights, and recommendations. |
| `README.md` | Project overview, objectives, technologies, key insights, and instructions to run the analysis. |

## 🚀 How to Run This Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/btwitravi/Travel-Tourism-Analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Travel-Tourism-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Travel_Tourism_Analysis.ipynb` and run the cells sequentially. Keep `Travel_Tourism.csv` in the same folder as the notebook.

## 📌 Conclusion

This project demonstrates how Python-based exploratory data analysis and statistical testing can help uncover travel booking patterns, customer preferences, cancellation trends, and trip-cost relationships. The findings provide a foundation for improving customer experience and supporting data-driven decisions in the travel and tourism industry.

## 👨‍💻 Author

**Ravi Kumar Gupta**

- **GitHub:** [btwitravi](https://github.com/btwitravi)
- **LinkedIn:** [Ravi Kumar Gupta](https://www.linkedin.com/in/ravi-kumar-gupta-161745247/)
- **Portfolio:** [Data Analyst Portfolio](https://btwitravi.github.io/Portfolio/)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
