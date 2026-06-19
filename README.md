Smart Supply Chain Analytics

Overview

This project develops an intelligent supply chain analytics framework using machine learning and data analytics techniques. The system performs product segmentation, anomaly detection, demand forecasting, and product recommendation to support inventory optimization and smart supply chain decision-making.

The project is built using the Online Retail dataset and demonstrates an end-to-end analytics pipeline from data preprocessing to business insights generation.

⸻

Objectives

* Segment products based on sales behavior.
* Detect unusual demand patterns and anomalies.
* Forecast future demand using time-series analysis.
* Identify frequently purchased product combinations.
* Generate actionable insights for inventory planning and supply chain optimization.

⸻

Dataset

Dataset: Online Retail Dataset

The dataset contains transactional retail data including:

* Invoice Information
* Product Description
* Quantity Purchased
* Unit Price
* Customer ID
* Transaction Date

⸻

Methodology

1. Data Preprocessing

* Missing value handling
* Invalid transaction removal
* Date feature extraction
* Product-level feature engineering
* Customer-level feature engineering

⸻

2. Product Segmentation

Techniques Used:

* StandardScaler
* K-Means Clustering
* Hierarchical Clustering (Ward Linkage)
* Principal Component Analysis (PCA)

Business Outcome:

* Fast Moving Products
* Medium Moving Products
* Slow Moving Products

⸻

3. Dynamic Anomaly Detection

Technique Used:

* Isolation Forest

Business Outcome:

* Detection of abnormal demand spikes and drops
* Identification of unusual purchasing patterns
* Early inventory risk detection

⸻

4. Demand Forecasting

Technique Used:

* Prophet

Business Outcome:

* 30-Day Demand Forecast
* Trend Analysis
* Seasonal Pattern Discovery

⸻

5. Recommendation System

Technique Used:

* Apriori Algorithm
* Association Rule Mining

Metrics:

* Support
* Confidence
* Lift

Business Outcome:

* Frequently Bought Together Analysis
* Product Bundling Opportunities
* Inventory Optimization Insights

⸻

Results

Product Segmentation

Three meaningful product segments were identified:

* Fast Moving Products
* Medium Moving Products
* Slow Moving Products

Anomaly Detection

Isolation Forest successfully detected unusual demand patterns and extreme demand spikes.

Demand Forecasting

Prophet generated future demand forecasts and identified trend and seasonal components.

Recommendation System

Association Rule Mining revealed strong product relationships with high lift scores, supporting inventory planning and cross-selling strategies.

⸻

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* SciPy
* Prophet
* Mlxtend

⸻

Key Business Impact

This project demonstrates how machine learning can support:

* Smart Inventory Management
* Demand Planning
* Supply Chain Optimization
* Product Bundling Strategies
* Anomaly Detection and Risk Monitoring
