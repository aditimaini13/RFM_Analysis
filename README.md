# RFM Analysis Project

In this project, I conducted RFM (Recency, Frequency, Monetary) analysis using Python to gain actionable insights into customer behavior and effectively segment customers based on their purchasing patterns. RFM analysis is a valuable technique that provides a comprehensive view of customer engagement, loyalty, and value to businesses.

## Dataset

I utilized a dataset sourced from [StatsO](https://statso.io/rfm-analysis-case-study/) for this project. The dataset contained essential transaction information, including purchase dates, amounts, and customer IDs. While the dataset was relatively clean, I performed essential data wrangling to derive additional columns and features necessary for the analysis.

## Steps Taken

### 1. Data Preprocessing

To ensure data accuracy, I performed essential data preprocessing tasks. This involved converting date columns into appropriate datetime formats and addressing any missing or inconsistent data points.

### 2. Calculating RFM Values

I calculated three key metrics for each customer to facilitate RFM analysis:

- *Recency*: Determined how recently a customer made a purchase.
- *Frequency*: Quantified how often a customer conducted transactions.
- *Monetary Value*: Measured the amount of money a customer spent.

### 3. Assigning RFM Scores

RFM scores were assigned to each customer based on quartiles. Higher scores were given to customers who exhibited recent purchases, frequent transactions, and higher monetary spending.

### 4. Segmenting by RFM Values

I segmented customers into different value segments based on their RFM scores. This categorization allowed for the identification of diverse customer groups, such as high-value, loyal customers and customers with lower engagement levels.

### 5. Customer Segmentation Analysis

Further segmentation of customers based on RFM scores yielded granular customer profiles. This step unveiled segments like "Champions" (high RFM scores) and "Hibernating" customers (low RFM scores).

### 6. Utilizing Plotly for Visualization

In addition to Matplotlib and Seaborn, I employed Plotly, a powerful data visualization library, to create interactive and engaging visualizations. This enriched the presentation of the analysis results, making it easier to communicate findings.

## Tools and Libraries

This project was accomplished using Python, along with the following key tools and libraries:

- *Pandas*: Utilized for data manipulation and preprocessing.
- *Plotly*: Leveraged for creating dynamic and interactive visualizations, enhancing the presentation of results.

## Conclusion

The RFM analysis provided profound insights into customer behavior, enabling effective customer segmentation and tailored marketing strategies. By utilizing Python and its associated libraries, including Plotly for interactive visualizations, I was able to perform a comprehensive analysis efficiently. The project's outcomes contribute to enhancing customer retention, optimizing engagement strategies, and driving revenue growth for businesses.

