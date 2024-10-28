# HealthInsight-Patient-Outcomes-Performance-Tracker

This R Shiny application, HealthInsight: Patient Outcomes & Performance Tracker, is designed to visualize healthcare data, allowing users to explore patient outcomes and treatment performance across different hospitals. The dashboard provides a sidebar with filters, including date range, hospital, treatment, age range, and gender, enabling users to customize the data displayed.

The filtered_data function dynamically applies these filters to the sample hospital_data dataset. Two main plots are generated in the dashboard body:

Outcome Plot – A line chart showing the average patient outcomes over time.
Success Rate Plot – A bar chart displaying success rates for each treatment.
The dashboard relies on ggplot2 for static visualizations and dplyr for data manipulation, making it interactive and informative for healthcare data analysis.
