# Hotel Booking Demand – Exploratory Data Analysis (EDA)

**Internship:** Valentius Kryptix  
**Week:** 01  
**Project Type:** Exploratory Data Analysis  
**Domain:** Hospitality and Hotel Booking Analytics

## 1. Project Overview

This project performs an Exploratory Data Analysis (EDA) of the Hotel Booking Demand dataset using Python.

The objective is to investigate hotel booking patterns, customer behaviour, cancellation trends, seasonal demand, and pricing characteristics through statistical analysis and data visualization.

The analysis focuses on identifying meaningful patterns, understanding data quality issues, and extracting business insights that could help hotel management make better decisions.

## 2. Dataset Information

**Dataset:** Hotel Booking Demand

**Source:** [Kaggle – Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

The dataset contains approximately 119,390 hotel booking records and 32 columns.

It includes information about:

- Hotel types (City Hotel and Resort Hotel)
- Booking cancellations
- Customer information
- Arrival dates
- Booking lead times
- Room pricing (ADR)
- Distribution channels
- Market segments
- Customer special requests

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## 4. Project Workflow

### 4.1 Dataset Loading and Structural Analysis

- Loaded the dataset using Pandas.
- Examined the dataset dimensions.
- Inspected column names and data types.
- Checked memory usage.
- Previewed the first and last records.

### 4.2 Missing Value Analysis

- Identified columns containing missing values.
- Calculated missing-value counts and percentages.
- Created a missing-value bar chart.
- Visualized missing-value distribution using a heatmap.

### 4.3 Data Quality Analysis

- Investigated duplicate records.
- Examined numerical and categorical data types.
- Checked unique categorical values.
- Investigated unusual numerical values.
- Identified potential outliers using the IQR method.
- Investigated negative ADR values, unusually high ADR values, and bookings with zero adults.

### 4.4 Statistical Analysis

- Calculated mean, median, and mode.
- Examined variance and standard deviation.
- Analysed quartiles and percentiles.
- Investigated categorical frequency distributions.
- Compared City Hotel and Resort Hotel booking characteristics.

### 4.5 Data Visualization

Created ten visualizations:

1. Distribution of Hotel Booking Lead Time
2. Booking Cancellation Distribution
3. Monthly Hotel Booking Trends
4. Booking Distribution by Market Segment
5. ADR Distribution by Hotel Type
6. Cancellation Rate by Hotel Type
7. Correlation Heatmap
8. Top 10 Customer Countries

Each visualization was accompanied by an interpretation of the observed patterns.

## 5. Key Findings

The following findings were identified during the analysis:

1. **Booking Cancellation:** Approximately 37.04% of bookings were canceled, indicating that cancellations are an important operational concern.

2. **Booking Lead Time:** The average lead time was approximately 104 days, while the median was 69 days, suggesting a right-skewed booking distribution.

3. **Customer Composition:** The median number of adults per booking was two, and at least 75% of bookings contained zero children.

4. **Data Quality:** The dataset contained missing observations, including substantial missing information in the agent and company columns.

5. **Unusual Records:** One negative ADR value (-6.38), one exceptionally high ADR value (5400), and 403 bookings with zero adults were identified for further investigation.

## 6. Business Relevance

The analysis provides insights that can support:

- Understanding booking cancellation patterns.
- Identifying seasonal demand variations.
- Evaluating pricing differences between hotel types.
- Understanding customer booking behaviour.
- Identifying important booking distribution channels.
- Improving data quality and reporting processes.

## 7. Project Structure

```text
valentius-kryptix-internship/
│
├── dataset/
│   └── hotel_bookings.csv
│
├── notebooks/
│   └── Hotel_Booking_Demand_EDA.ipynb
│
├── src/
│   └── hotel_booking_eda.py
│
├── visualizations/
│   ├── 01_lead_time_distribution.png
│   ├── 02_cancellation_distribution.png
│   ├── 03_monthly_booking_trends.png
│   ├── 04_market_segment_analysis.png
│   ├── 05_adr_distribution.png
│   ├── 06_cancellation_by_hotel.png
│   ├── 07_correlation_heatmap.png
│   └── 08_top_customer_countries.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

## 8. How to Run the Project

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/valentius-kryptix-internship.git
```

Navigate to the project directory and switch to the Week 1 branch:

```bash
cd valentius-kryptix-internship
git checkout week_1
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
colab_notebook
```

Open `notebooks/Hotel_Booking_Demand_EDA.ipynb` and execute the cells.

Alternatively, run the Python script:

```bash
python src/hotel_booking_eda.py
```

## 9. Conclusion

This project demonstrates a complete exploratory data analysis workflow, beginning with dataset inspection and data quality assessment and progressing through statistical analysis and visualization.

The analysis highlights important booking patterns, cancellation behaviour, customer characteristics, and potential data-quality issues.

It provides a foundation for further analysis and future predictive modelling in the hospitality domain.

---

**Internship Submission – Week 1**  
**Valentius Kryptix**
