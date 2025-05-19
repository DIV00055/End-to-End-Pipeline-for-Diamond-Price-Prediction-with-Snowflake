# End-to-End-Pipeline-for-Diamond-Price-Prediction-with-Snowflake
This repository contains our work for Trends Marketplace 2025 which is hosted every year by Carlson Analytics Lab at University Of Minnesota Twin Cities
Project Title: Real-Time Price Prediction at Scale with Snowflake and Superset

Goal: Enable real-time ML predictions via SQL queries
Link to Superset Dashboard: https://6cdef29e.us1a.app.preset.io/superset/dashboard/p/DQqGPzE95Rz/

# Executive Summary
### This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.

Despite being one of the most highly valued commodities, diamond pricing remains largely dependent on outdated appraisal methods and disconnected data systems. In today’s data-first economy, stakeholders across the diamond supply chain demand faster, smarter, and more consistent price intelligence.

This project introduces a real-time, production-ready solution for diamond price prediction—leveraging the combined power of Snowflake’s data warehousing, Databricks’ ML ecosystem, and scalable Python UDFs. Our pipeline transforms raw attributes into actionable insights, allowing business users to query machine learning models directly via SQL. By bridging advanced analytics with user-friendly interfaces, we unlock seamless integration between predictive models and everyday business operations—delivering speed, accuracy, and transparency to the heart of diamond pricing.

## What is in the pipeline? 

Pipeline: Ingestion → Engineering → Training → UDF Deployment → Visualization
Tech Stack: Snowflake, Snowpark, Databricks, Pandas, XGBoost, Python UDF, Optuna, Streamlit

## What are the values? 

Handles Large-Scale, High-Dimensional Data with Ease
Built to process millions of diamond records—our pipeline efficiently ingests and transforms complex features like cut, clarity, carat, and dimensions without being constrained by memory or token limits.

No Manual Tuning Required for Model Scalability
Our use of XGBoost and Optuna allows for automated hyperparameter optimization, eliminating the need for fixed model configurations and enabling smooth adaptation to new datasets or expanded attributes.

Goes Beyond Traditional Modeling by Embedding Intelligence in SQL
By deploying the model as a Python UDF in Snowflake, we allow real-time price prediction directly within SQL queries—bridging the gap between machine learning output and BI team workflows.

Modular and Transferable Framework
Though designed for diamonds, the pipeline structure can be easily repurposed for any product with structured attributes and price variability—such as watches, cars, or real estate.

Secure, Governed, and Production-Ready
Leveraging Snowflake’s built-in security, governance, and native role-based access, the system is enterprise-grade by default—suitable for deployment in regulated or sensitive business environments.

Insight Delivery Through Interactive Dashboards
Model outputs are visualized in Superset dashboards, offering stakeholders real-time access to predicted prices, key value drivers, and product segmentation insights—across SKUs, categories, or quality grades.

### Link to the toy dataset: https://www.kaggle.com/datasets/nancyalaswad90/diamonds-prices/data

Business Value: Scalable, enterprise-grade ML pipeline integrated with data warehouse for real-time use by BI teams.
