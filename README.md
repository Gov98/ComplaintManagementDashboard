# Complaint Management System (CMS) Dashboard

This repository contains the Power BI dashboards developed for the Complaint Management System (CMS). The dashboards offer interactive visualizations and analytics to monitor and manage customer complaints effectively.

<b>video demonstration</b><br>
![video](/screenshot/demo.gif) 
<br>

## Dashboard Overview

The CMS Power BI dashboards are divided into two main sections:

### 1. **Dashboard Page**
![image](https://github.com/user-attachments/assets/2a24d05a-3f22-41df-92fa-5e2c09367435)

This page provides an at-a-glance summary of key metrics and visualizations.

#### Metrics and Visualizations:
- **Total Complaints:** Total number of complaints received.
- **Total Overdue Complaints:** Number of complaints not resolved within the SLA.
- **Resolution Time:** Average number of days to resolve a complaint.
- **Resolution Progress:** Percentage of complaints marked as "Closed."
- **Yearly Trend:** A line chart showing complaint trends over the years. Metrics include:
  - **Actual Count:** Total complaints per year.
  - **YoY% (Year-over-Year Percentage):** Change in complaints compared to the previous year.
  - **QoQ% (Quarter-over-Quarter Percentage):** Change in complaints compared to the previous quarter.
  - **MoM% (Month-over-Month Percentage):** Change in complaints compared to the previous month.
- **Complaints by Department:** Bar chart showing the distribution of complaints across departments. Includes a "Top N" filter for analysis.
- **Complaints by Timely Response:** Visualizes the percentage of complaints resolved within SLA.
- **SLA Compliance Rate:** A KPI gauge indicating the compliance percentage.
- **Customer Rating:** Displays average customer feedback (star rating) collected via Microsoft Forms.

---

### 2. **Analytics Page**
![image](https://github.com/user-attachments/assets/c3eab82e-72da-481a-b54b-69174e4e0f2b)

This page allows users to perform detailed analyses of complaints using custom parameters and slicers.

#### Features:
- **Previous N Months of Complaints (Monthly Analysis):**
  - Analyze complaint trends for a user-defined period (e.g., last 6 months).
  - Metrics include:
    - **Max Complaints Date:** Month with the highest number of complaints.
    - **Average Complaints:** Average complaints over the selected period.
    - **Percentile:** Custom percentile-based analysis using a slider.
    - **Line Selection:** Choose between metrics (e.g., Average, Percentile) for dynamic trend visualization.

- **Interactive Slicers and Filters:**
  - **Anchor Date:** Select an endpoint for analysis.
  - **N Value:** Specify the number of months to analyze.
  - **Dynamic Metrics Selection:** Choose metrics such as Average, Percentile, or Total Percentage.

---

## Key Features

1. **Power Automate Integration:** The dashboards are integrated with Power Automate workflows for automated data updates. Complaints are processed in real-time, and the dataset refreshes dynamically.
2. **Interactive Visuals:** Advanced filtering options, slicers, and parameter inputs allow users to customize their analysis.
3. **Dynamic Metrics and Trends:** The dashboards support switching between metrics such as YoY%, QoQ%, MoM%, and Actual values for trends.

---

## Repository Contents

- **`Dashboard.pbix`**: The Power BI file containing the dashboards.
- **`ComplaintManagement.xlsx`**: The data source for the dashboards, including:
  - **Main Table:** Tracks complaints.
  - **Lookup Table:** Maps departments and related information.
- **Power Automate Flows Documentation**: Details of automated workflows integrated with the CMS.
- **README.md**: This file explaining the repository and dashboards.

---

## Access the Dashboard

You can view the live Power BI dashboard using the link below:

[View CMS Dashboard](<https://app.powerbi.com/reportEmbed?reportId=466a53f2-e8a1-462a-ac66-77edb6cae89e&autoAuth=true&ctid=28bcace8-4ce7-4949-868f-170f67122379>)

---

## How to Publish and Access

1. **Publishing:** The dashboards can be published to the Power BI Service for online access.
2. **Embedding:** You can embed the dashboards in a SharePoint site or generate public links for sharing.
3. **Integration with GitHub:** Publish the Power BI `.pbix` file and ensure the README contains links to showcase your dashboard.

---

## Future Enhancements

- **Task Assignment Automation:** Equally distribute tasks among department employees based on workload.
- **Feedback Dashboard:** Incorporate detailed customer feedback visualizations.
- **Departmental Power Apps Integration:** Enable department-level complaint management through Power Apps.

---

Feel free to use, modify, and enhance this repository for your projects. Contributions are welcome!
