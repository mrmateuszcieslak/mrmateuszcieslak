<h1 align="center">Mateusz Cieślak</h1>

<p align="center">
  <strong>Data & BI · SQL & Databases · Machine Learning · AWS & IoT</strong><br>
  Turning data into clear reports, predictive experiments, and connected systems.
</p>

<p align="center">
  <a href="#portfolio-by-role"><img src="https://img.shields.io/badge/Explore-Portfolio-2563EB?style=for-the-badge" alt="Explore portfolio"></a>
  <a href="https://www.linkedin.com/in/mateuszcieslak1/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="Connect on LinkedIn"></a>
  <a href="mailto:maticieslak7@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-0F766E?style=for-the-badge" alt="Contact by email"></a>
</p>

I work with **SQL, Python, and Power BI** to prepare data and communicate findings. My public portfolio brings together production and sales dashboards, SQL Server application integration, machine learning notebooks, and an AWS IoT architecture project.

**Career interests:** BI Developer / Power BI Developer · Data Analyst · SQL Developer / Database Specialist · AI / Cloud Developer.

## Portfolio by role

Choose the work most relevant to your team:

| Role | Start here | What to review |
| --- | --- | --- |
| **BI Developer** | [Production Analytics](#production-analytics) · [Apple Sales](#apple-sales) | Power BI dashboards, DAX, time filters, data modeling, Power Query |
| **Data Analyst** | [Apple Sales](#apple-sales) · [Winter Olympics](#winter-olympics) · [Loan Data](#loan-data-preparation) | Revenue and volume trends, exploratory analysis, visualization, data preparation |
| **SQL / Database Specialist** | [SimulatorCar](#sql-server-application-integration) · [Production Analytics](#production-analytics) | SQL Server integration, ADO.NET, persistent application data, a BI data model |
| **AI / Cloud Developer** | [Bank Churn](#bank-customer-churn) · [AWS IoT](#aws-iot-architecture) · [Loan Data](#loan-data-preparation) | Classification experiments, model comparison, preprocessing, Terraform and AWS resources |

## Featured work

### Production Analytics

**How does actual production compare with the plan, and where do costs, downtime, and quality need attention?**

An interactive dashboard covering production KPIs, planned versus actual output and costs, downtime, and quality. Year/month filters and dynamic titles support time-based exploration.

**Stack:** Power BI · SQL Server 2019 · DAX · Data modeling  
**Evidence:** Power BI Desktop report (`.pbix`) and documented `FactProdukcja` / `DimData` model.  
**Scope:** Portfolio demonstration using synthetic 2025 data; report interface in Polish. Refreshing may require changing the local SQL Server connection.

[**Explore the report and model →**](https://github.com/mrmateuszcieslak/ProductionAnalytics)

[![Production Analytics last commit](https://img.shields.io/github/last-commit/mrmateuszcieslak/ProductionAnalytics?style=flat-square&label=updated&color=2563EB)](https://github.com/mrmateuszcieslak/ProductionAnalytics/commits/main/)

<a href="https://github.com/mrmateuszcieslak/ProductionAnalytics">
  <img src="https://github.com/user-attachments/assets/83c6d838-9e7e-41c3-8334-7c638c3b4645" alt="Production Analytics Power BI dashboard preview" width="900">
</a>

### Apple Sales

**Which apple varieties drive revenue, and how do sales change through the year?**

A Power BI dashboard comparing sales volume and revenue by variety and month. The Apple Variety slicer updates the visuals, including Total Revenue and monthly comparisons.

**Stack:** Power BI · DAX · Power Query  
**Focus:** Sales seasonality, variety comparisons, KPI presentation, and interactive filtering.

[**Explore the sales dashboard →**](https://github.com/mrmateuszcieslak/apple-sales-dashboard)

[![Apple Sales last commit](https://img.shields.io/github/last-commit/mrmateuszcieslak/apple-sales-dashboard?style=flat-square&label=updated&color=2563EB)](https://github.com/mrmateuszcieslak/apple-sales-dashboard/commits/main/)

<a href="https://github.com/mrmateuszcieslak/apple-sales-dashboard">
  <img src="https://github.com/user-attachments/assets/51bcb083-13aa-4971-a02c-1f3808b1dfc5" alt="Apple Sales Power BI dashboard preview" width="900">
</a>

### SQL Server Application Integration

**Connecting a desktop application to persistent relational data.**

SimulatorCar combines car navigation with street management. Users can modify street details and save changes through a SQL Server database integration.

**Stack:** C# · Windows Forms · Microsoft SQL Server · ADO.NET · DataSet  
**Focus:** Database-backed application development, editing records, and data persistence.

[**Inspect the application →**](https://github.com/mrmateuszcieslak/SimulatorCar)

### Bank Customer Churn

**Exploring and comparing classification approaches for bank customer churn.**

The notebook includes data exploration, IQR-based outlier handling, scaling, categorical encoding, and a stratified train/test split. It implements Decision Tree, SVM, Random Forest, and XGBoost experiments, with GridSearchCV and stratified cross-validation. Evaluation code compares accuracy, precision, recall, F1, and ROC AUC.

**Stack:** Python · Pandas · scikit-learn · XGBoost · Matplotlib · Seaborn  
**Scope:** Educational notebook experiments; no production deployment or independently validated performance claim.  
**Collaboration:** Developed in cooperation with [SSJ0406](https://github.com/SSJ0406), as credited in the project README.

[**Inspect the ML notebook →**](https://github.com/mrmateuszcieslak/Bank-Customer-Churn-Prediction-AI)

[![Bank Churn last commit](https://img.shields.io/github/last-commit/mrmateuszcieslak/Bank-Customer-Churn-Prediction-AI?style=flat-square&label=updated&color=7C3AED)](https://github.com/mrmateuszcieslak/Bank-Customer-Churn-Prediction-AI/commits/main/)

### AWS IoT Architecture

**From environmental measurements to a cloud architecture defined as code.**

LaboratoryIoT contains device code, architecture diagrams, a Power BI report, and Terraform definitions. The infrastructure code defines AWS IoT resources and certificates, a topic rule invoking Lambda, an S3 bucket, and a DynamoDB table.

**Stack:** AWS IoT Core · AWS Lambda · Amazon S3 · Amazon DynamoDB · Terraform · ESP32 / Arduino · Power BI  
**Focus:** Device/cloud integration, Infrastructure as Code, and architecture documentation.  
**Scope:** Educational and research project described as a conceptual, partially implemented model. Repository materials do not establish a complete production deployment.

[**Explore the architecture and Terraform →**](https://github.com/mrmateuszcieslak/LaboratoryIoT)

[![AWS IoT last commit](https://img.shields.io/github/last-commit/mrmateuszcieslak/LaboratoryIoT?style=flat-square&label=updated&color=0F766E)](https://github.com/mrmateuszcieslak/LaboratoryIoT/commits/main/)

## More data projects

### Winter Olympics

Analysis of Winter Olympic medal records for **1924–2014**, covering countries, years, sports, gender, Poland, and Adam Małysz. Visualizations include bar, line, pie, and stacked bar charts.

**Stack:** Python · Pandas · Matplotlib  
[**Explore the analysis →**](https://github.com/mrmateuszcieslak/WinterOlympicGames)

### Loan Data Preparation

Credit-data cleaning and filtering for further analysis and machine learning. The notebook includes stratified sampling to create a **15,000-row subset** while preserving target-class proportions.

**Stack:** Python · Pandas · scikit-learn  
**Collaboration:** Developed in cooperation with [SSJ0406](https://github.com/SSJ0406), as credited in the project README.  
[**Explore the notebook →**](https://github.com/mrmateuszcieslak/Loan-Project-AI)

### IoT Weather Station

An Arduino / ESP32 weather-station project for environmental measurements and wireless communication, including temperature, humidity, pressure, and air-quality parameters.

**Stack:** Arduino · ESP32 · Environmental sensors  
[**Explore the device project →**](https://github.com/mrmateuszcieslak/ArduinoStacjaPogodowa)

<details>
<summary><strong>Additional software projects — expense, contact, and task management</strong></summary>

| Project | Confirmed functionality | Technologies |
| --- | --- | --- |
| [ExpenseManagerApp](https://github.com/mrmateuszcieslak/ExpenseManagerApp) | Expense CRUD, totals, monthly reports, JSON persistence | C# 12, .NET 8, System.Text.Json, Repository pattern |
| [Contact Management System](https://github.com/mrmateuszcieslak/Contact-Management-System) | Contact CRUD, login, calendar reminders | PHP, JavaScript, HTML, CSS, FullCalendar |
| [TaskManagerApp](https://github.com/mrmateuszcieslak/TaskManagerApp) | Task CRUD, sorting/filtering, PDF and JSON export | JavaScript, HTML, CSS |

</details>

## Technologies demonstrated in this portfolio

| Area | Confirmed technologies |
| --- | --- |
| **Business Intelligence** | Power BI, DAX, Power Query, data modeling |
| **Databases & integration** | Microsoft SQL Server, ADO.NET, DataSet |
| **Data analysis** | Python, Pandas, Matplotlib, Seaborn |
| **Machine learning** | scikit-learn, XGBoost, GridSearchCV, stratified cross-validation |
| **Cloud & IoT** | AWS IoT Core, Lambda, S3, DynamoDB, Terraform, Arduino, ESP32 |
| **Application development** | C#, .NET, Windows Forms, PHP, JavaScript, HTML, CSS |

## Contact

Interested in discussing BI, data analysis, database development, or AI/cloud opportunities?

**[Connect on LinkedIn](https://www.linkedin.com/in/mateuszcieslak1/)** · **[Email me](mailto:maticieslak7@gmail.com)** · **[Browse all repositories](https://github.com/mrmateuszcieslak?tab=repositories)**

<!-- Dynamic badges are externally generated by Shields.io and may be cached.
     Project descriptions and previews are static; Power BI interactions happen in the report.
     This README requires no workflow, JavaScript, or GitHub Actions configuration. -->
