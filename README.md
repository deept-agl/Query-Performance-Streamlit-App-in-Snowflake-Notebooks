# 📊 Interactive Query Performance Streamlit App in Snowflake Notebooks

This is a simple interactive Streamlit app that runs inside **Snowflake Notebooks** to help you analyze **query performance**.

It pulls data from the `ACCOUNT_USAGE.QUERY_HISTORY` table and shows visual insights about the longest-running queries using filters and charts.

---

## 🚀 What It Does

- Select a **timeframe**: day, week, or month  
- Choose how many top queries to display  
- Filter queries by **SQL command** (e.g., SELECT, SHOW, DESCRIBE)  
- See:
  - A **histogram** of query execution times  
  - A **boxplot** showing execution time spread  
  - Raw data and summary stats

---
## Here’s a quick look at the app in action:


![Interactive Query Controls](https://github.com/deept-agl/Query-Performance-Streamlit-App-in-Snowflake-Notebooks/blob/main/interactive%20output%20controls.png)

## How the final plots look like:


![Plots](https://github.com/deept-agl/Query-Performance-Streamlit-App-in-Snowflake-Notebooks/blob/main/Performance%20plots.png)

## ▶️ How to Run

---

Just run the code inside a **Snowflake Notebook** with Streamlit imported.

Make sure you're connected to your Snowflake environment and your role have access to `ACCOUNT_USAGE.QUERY_HISTORY`.

---

## 🔧 Built With

- Streamlit  
- Snowflake Snowpark  
- Pandas  
- Altair  
- NumPy

---

## 🙌 Credits

This app was built by following a **Snowflake Quickstart tutorial**.  
Thanks to the Snowflake team for the amazing learning resources!  
👉 [https://quickstarts.snowflake.com](https://quickstarts.snowflake.com/guide/automated-query-performance-insights-with-streamlit/index.html?index=..%2F..index#4)
