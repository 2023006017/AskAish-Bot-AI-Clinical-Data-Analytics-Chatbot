# AskAish-Bot-AI-Clinical-Data-Analytics-Chatbot
AskAish Bot is an AI-powered clinical analytics chatbot built in R using Shiny. It generates synthetic clinical data, performs statistical summaries, builds machine learning models, creates TFLs, visualizations, dashboards, and automated reports in a single workflow.
📌 Abstract

AskAish Bot is an AI-driven clinical data analytics system developed in R using Shiny that automatically generates synthetic clinical datasets, performs statistical analysis, builds machine learning models, generates TFLs (Tables, Figures, Listings), produces interactive dashboards, and provides AI-style insights through a chatbot interface.

The system integrates clinical analytics, machine learning, and automated reporting into a single pipeline to assist researchers and clinical programmers in exploring study data quickly and efficiently.

This project demonstrates an end-to-end automated clinical data analysis workflow.

📖 Introduction

Clinical trials generate large volumes of structured data including demographics, laboratory results, and treatment information. Analysts and clinical programmers must perform multiple tasks including:

Data cleaning

Summary statistics

TFL generation

Visualization

Risk analysis

Reporting

Traditional workflows require multiple tools and manual steps.

AskAish Bot simplifies this process by integrating data generation, machine learning, analytics, and chatbot interaction into a single platform.

The system provides an interactive interface that enables users to explore clinical data and generate automated insights.

🎯 Objectives

The main objectives of this project are:

Build an automated clinical data analytics pipeline

Generate synthetic datasets for analysis

Perform statistical summaries

Generate TFLs used in clinical reporting

Implement machine learning models

Build interactive dashboards

Provide chatbot-based query system

Generate automated reports

🏗 System Architecture
                +----------------------+
                | Synthetic Data Gen   |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Data Processing      |
                | Cleaning / Transform |
                +----------+-----------+
                           |
                           v
          +----------------+----------------+
          |                                 |
          v                                 v
+--------------------+             +---------------------+
| Statistical Summary|             | Machine Learning     |
| Mean, SD, Tables   |             | Random Forest Model  |
+---------+----------+             +----------+-----------+
          |                                   |
          +------------------+----------------+
                             |
                             v
                    +-------------------+
                    | Visualization     |
                    | ggplot2 Charts    |
                    +---------+---------+
                              |
                              v
                    +-------------------+
                    | TFL Generation    |
                    | Tables Figures    |
                    +---------+---------+
                              |
                              v
                    +-------------------+
                    | AskAish Chatbot   |
                    | User Interaction  |
                    +---------+---------+
                              |
                              v
                    +-------------------+
                    | Automated Reports |
                    +-------------------+
🤖 Machine Learning Models

The project uses Random Forest Classification to predict patient risk levels.

Input Variables

Age

ALT

AST

Weight

Target Variable

Risk Level (High / Low)

Algorithm

Random Forest is an ensemble learning method that combines multiple decision trees to improve prediction accuracy.

Advantages

Handles nonlinear relationships

Robust to noise

Good performance on structured data

📊 Features
1️⃣ Synthetic Clinical Data Generation

The system automatically generates a clinical dataset including:

Subject ID

Age

Sex

Treatment group

Lab parameters

This enables testing without real clinical data.

2️⃣ Statistical Summary

The system automatically calculates:

Mean

Standard deviation

Summary statistics

3️⃣ TFL Generation

The system generates standard clinical reporting tables.

Demographics Table

Subjects by treatment

Mean age

Mean weight

Lab Summary

ALT statistics

AST statistics

4️⃣ Data Visualization

Visualizations include:

Age distribution histogram

ALT vs treatment boxplot

Sex distribution bar chart

These visualizations support quick data exploration.

5️⃣ Interactive Dashboard

The dashboard is built using Shiny and provides:

Interactive plots

Dynamic tables

Model output

AI insights

6️⃣ AskAish Chatbot

Users can interact with the system using simple queries such as:

summary
risk
treatment

The chatbot returns analytical results based on the dataset.

📄 Automated Reporting

The system can generate automated reports including:

Dataset summary

Demographics tables

Lab statistics

AI insights

Reports can be downloaded directly from the dashboard.

⚙️ Technologies Used

R

Shiny

dplyr

ggplot2

randomForest

DT

📁 Project Structure
AskAish-Bot
│
├── app.R
├── README.md
├── data
│   └── synthetic_clinical_data.csv
│
├── reports
│   └── automated_report.txt
│
└── plots
    └── visualizations
✅ Advantages

Fully automated analytics pipeline

Interactive dashboards

Integrated machine learning

Clinical-style TFL generation

Chatbot-based interaction

No real data required (synthetic data generation)

⚠️ Limitations

Uses simulated data rather than real clinical trial datasets

Chatbot uses rule-based responses instead of advanced NLP

Limited ML models in current version

🚀 Future Improvements

Possible enhancements include:

Natural Language Processing chatbot

Integration with real clinical datasets

Advanced ML models (XGBoost, Neural Networks)

Automated Clinical Study Report generation

Deployment on cloud platforms

📌 Conclusion

AskAish Bot demonstrates how clinical analytics, machine learning, and chatbot interfaces can be integrated into a unified system for automated data analysis and reporting.

This project provides a practical demonstration of an AI-assisted clinical programming workflow and serves as a foundation for more advanced intelligent analytics systems in healthcare research.


