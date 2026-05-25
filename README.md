# Formula 1 Race Outcome Prediction & Analysis

> An end-to-end Data Science and Data Mining project leveraging multi-source historical F1 data and weather patterns to predict race outcomes and analyze driving styles.

---

## Analysis & Visualizations

<p align="center">
  <img src="https://github.com/user-attachments/assets/a672b509-6318-46fb-a95f-1b6e5a13dcc3" alt="F1 Data Insights Preview" width="85%">
</p>

---

## Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** Data Cleansing & Transformation using **Pandas** and **NumPy**
- **Machine Learning & Analytics:** **Scikit-learn** (K-Means Clustering, Association Rules, Classification Modeling)

---

## Key Features & Workflow

### 1. Data Pipelines & ETL
- **Data Integration:** Integrated multi-source F1 datasets containing telemetry records, race outcomes, and historical weather data (focused on the **2019–2024** modern era).
- **Data Preprocessing:** Executed strict data cleaning and preprocessing pipelines to handle missing values and anomalies.

### 2. Feature Engineering & Modeling
- **Domain Features:** Engineered custom features such as circuit characteristics classified by **Downforce Levels** (Low, Balanced, High Downforce).
- **Predictive Modeling:** Developed Machine Learning Classification models to predict the probability of drivers finishing in the **Top 3 (Podium)**.
<p align="center">
  <img src="https://github.com/user-attachments/assets/81fdd7bf-1e01-463e-907a-d642ac007431" width="45%" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/8461319e-df4f-4693-a233-25413e195659" width="45%" />
</p>

### 3. Advanced Data Mining Techniques
- **Clustering (K-Means):** Profiled driver styles and track performance clusters using the **Elbow Method** to determine the optimal $K$ value.
- **Association Rules:** Extracted implicit tactical patterns and correlations between circuit types and constructor performance.

<p align="center">
  <img src="https://github.com/user-attachments/assets/9de36580-4aed-4d74-af3d-3ce752b1eaab" width="45%" />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/c9d8020d-2c85-463c-8637-c80ee2f13fcf" width="45%" />
</p>

---

## Core Solutions
- **No Data Fragmentation:** Centralized scattered historical and environmental logs into a single structured format for analytics.
- **Actionable Strategic Insights:** Successfully extracted hidden racing patterns that directly quantify risk and aid strategy optimization under real-time constraints.
