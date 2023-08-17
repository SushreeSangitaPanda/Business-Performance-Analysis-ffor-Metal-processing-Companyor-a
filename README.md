# Business Performance Analysis-for a Metal processing Company

This repository contains an in-depth analysis of business performance and customer segmentation based on a dataset containing information about items in orders. The analysis is conducted using Python libraries such as pandas, seaborn, as well as machine learning algorithms including Random Forest, SVM, and Logistic Regression. The dataset includes the following columns: item_uuid (PK), company_uuid (FK), order_uuid (FK), price, cost, quantity, material_group, material_type, thickness, diameter, deburring, bendings, vertical, dimension, length, customer_segments, and wz_code.

## Key Objectives and Conclusions

The primary objective of this analysis is to derive meaningful insights and conclusions from the provided dataset, specifically focusing on business performance and customer segmentation. The analysis addresses the following key points:

1. **Data Loading and Preprocessing:** The dataset is loaded using pandas, and preprocessing steps are performed to handle missing values, data types, and data consistency.

2. **Business Performance Metrics:** Various business performance metrics are calculated, including total revenue, total cost, and profit margin, providing a comprehensive view of the company's financial performance.

3. **Customer Segmentation:** Using machine learning algorithms such as Random Forest, SVM, and Logistic Regression, customer segments are identified based on their characteristics and purchase behaviors. The models are trained to predict customer segments, and their performance is evaluated using confusion matrices and classification reports.

4. **Exploratory Data Analysis:** Visualizations and statistical analysis are conducted using seaborn to explore relationships between variables and uncover patterns within the data.

5. **Interesting Conclusions:** Some of the conclusions and insights that can be obtained from the analysis might include:
   - Identification of the most profitable customer segments.
   - Determination of which product categories contribute the most to revenue.
   - Assessment of the effectiveness of deburring processes on product quality and profitability.
   - Correlation between metal type, thickness, and cost.

6. **Business Insights:** Insights from the analysis can guide strategic decision-making, such as targeting specific customer segments for marketing efforts, optimizing product pricing, and enhancing manufacturing processes.

## How to Use the Repository

1. **Data Files:** The dataset containing the information about items in orders is provided in a CSV file.

2. **Data Analysis Code:** The code used for data analysis, preprocessing, visualization, and machine learning modeling is present in the "analysis" directory. It's organized into Jupyter Notebook files and Python scripts.

3. **Machine Learning Models:** The machine learning algorithms (Random Forest, SVM, Logistic Regression) are implemented in separate Jupyter Notebook files. Model evaluation metrics such as confusion matrices and classification reports are included.

4. **Results and Visualizations:** The "results" directory contains visualizations, graphs, and summary statistics generated during the analysis.

Link to the code: https://github.com/SushreeSangitaPanda/SushreeSangitaPanda/blob/1bc5892d2289a63010ab5b7779816bcb00a6f448/Laserhub_task-Copy1.ipynb


## Conclusion

This Business Performance and Customer Segmentation Analysis provides valuable insights into the company's financial health and customer behavior. The analysis helps in understanding which customer segments are most profitable, which products are contributing significantly to revenue, and how different variables are interconnected within the business context. The machine learning models applied for customer segmentation offer predictive power that can be used for targeted marketing and personalized strategies. The provided code and results enable you to delve deeper into the dataset and draw your own conclusions about the company's performance and customer dynamics.
