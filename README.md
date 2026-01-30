## 📌 What Was Built in This Project
-An end-to-end COVID-19 AI Risk Monitoring System using Databricks
-A complete pipeline covering data ingestion, cleaning, feature engineering, machine learning, automation, and analytics
-A system designed to convert raw health data into AI-driven risk insights for decision-making

## 📂 Datasets Used

1.COVID-19 India Case Data:
-Contains daily COVID case counts, recoveries, deaths, and active cases
-Used to analyze infection trends and severity indicators

2.COVID-19 Vaccination Data:
-Contains vaccination progress metrics such as total vaccinations and coverage ratios
-Used to enrich risk assessment and contextual analysis
-Both datasets are ingested as raw inputs and processed through the Bronze–Silver–Gold pipeline

## 🏗️ What Was Done
-Ingested raw COVID case and vaccination datasets into the Bronze layer
-Cleaned, standardized, and validated data in the Silver layer
-Engineered AI-ready features such as growth rates, ratios, and mortality indicators in the Gold layer
-Trained a machine learning model to predict COVID risk levels
-Stored model predictions as Delta tables for analytics consumption

## ⚙️ Pipeline Automation & Job Execution
-Databricks Jobs were created to orchestrate the complete pipeline
-Each stage (Bronze, Silver, Gold, ML) is configured as a dependent task
-The pipeline was successfully executed end to end using a single job trigger
-Successful job execution confirms reproducibility, automation, and production-style orchestration

## 📊 Analytics & Dashboard

-AI-generated outputs are visualized through a Databricks SQL dashboard
-The dashboard presents:
1.Current COVID risk level
2.Active case ratio and mortality rate
3.Risk distribution across Low, Medium, and High categories
4.Trend analysis over time
-A single-page dashboard was intentionally designed for executive-level clarity

## 📁 Repository Artifacts

- Databricks notebooks implementing Bronze, Silver, Gold, and ML stages  
- Job execution screenshots confirming successful pipeline runs (available in the `screenshots/` folder)
- Dashboard screenshots and access link (login required) (screenshots available in the `screenshots/` folder)
  🔗:https://dbc-f68b99b8-0b53.cloud.databricks.com/dashboardsv3/01f0fd4f709a17fc8cc459d12f108354/published?o=7474655970071885
- Whiteboard planning image documenting workflow design (available in the `screenshots/` folder) 
- PPT and demo video explaining the project end to end

## 🧠 Key Takeaways

-Demonstrates how Databricks enables end-to-end Data & AI workflows
-Shows the importance of planning-first system design
-Highlights automation, reproducibility, and AI-driven insights
-Bridges data engineering, machine learning, and analytics into one system
