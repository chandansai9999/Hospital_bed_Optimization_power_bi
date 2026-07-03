#  Hospital Bed Optimization Dashboard

##  Project Overview

This Power BI dashboard was developed to analyze hospital operations and optimize bed utilization. The dashboard provides insights into patient admissions, waiting times, bed occupancy, treatment costs, and departmental efficiency, enabling hospital administrators to make data-driven decisions for improving operational performance and patient care.

##  Business Problem

Hospitals often face challenges such as:

* High patient waiting times
* Uneven bed utilization across departments

These challenges can impact patient experience, operational efficiency, and overall healthcare delivery.

##  Project Objective

The objective of this dashboard is to:

* Monitor hospital bed occupancy rates
* Track patient waiting times
* Analyze admission patterns
* Compare departmental performance

##  Tools & Technologies Used

* Power BI
* DAX
* Data Modeling
* Excel Dataset

##  Dataset

This project uses a  **hospital dataset** containing **3,000 patient records** designed to simulate real-world hospital operations across multiple departments.

### Dataset Features

* Patient ID
* Age
* Gender
* Department
* Doctor
* Admission Date
* Discharge Date
* Wait Time (Minutes)
* Treatment Cost
* Bed ID

**Dataset:** [hospital_dataset.xltm](Hospital_Dataset/hospital_dataset.xltm)


#  Key Performance Indicators (KPIs)

| KPI                    | Value     | Description                                   |
| ---------------------- | --------- | --------------------------------------------- |
| Average Wait Time      | 56.70 Min | Average patient waiting time before treatment |
| Bed Occupancy Rate     | 66.35%    | Percentage of occupied beds                   |
| Total Patients         | 1,000     | Total patients handled                        |
| Average Treatment Cost | ₹48.52K   | Average treatment cost per patient            |

### KPI Overview
<img width="630" height="119" alt="image" src="https://github.com/user-attachments/assets/3d94a906-491f-4313-ac42-eecbfa427b3b" />


# Dashboard Visual Analysis

## 1. Patient Volume vs Average Wait Time by Department

### Purpose

Compares patient volume and average waiting time across departments to identify potential operational bottlenecks.

<img width="260" height="179" alt="image" src="https://github.com/user-attachments/assets/7df6a031-69e6-41e5-a3dc-775795458632" />
 

## 2. Monthly Patient Admissions Trend

### Purpose

Shows monthly admission patterns and helps identify periods of increased patient demand throughout the year.

<img width="260" height="175" alt="image" src="https://github.com/user-attachments/assets/529fe8f4-ea65-4188-b9ed-03512596f36d" />

## 3. Bed Occupancy Rate by Department

### Purpose

Compares bed utilization across departments to understand capacity usage and identify departments operating near occupancy limits.

<img width="262" height="178" alt="image" src="https://github.com/user-attachments/assets/fd7347b9-7542-4e41-8f61-bcb6e0c88a2e" />

## 4. Monthly Patient Load vs Average Wait Time

### Purpose

Analyzes the relationship between patient volume and waiting times across different months.

<img width="268" height="179" alt="image" src="https://github.com/user-attachments/assets/8e399a61-b019-4157-826c-ef8d47cdcbdf" />

## 5. Department Efficiency Matrix

### Purpose

Evaluates departmental performance using bed occupancy rate and average waiting time.

Departments with higher occupancy and lower wait times are generally considered more efficient.

<img width="261" height="183" alt="image" src="https://github.com/user-attachments/assets/f67353e4-52a9-47ff-8a8b-45b75e7cdad4" />

## 6. Department-wise Average Treatment Cost

### Purpose

Compares treatment costs across departments to identify high-cost service areas.

<img width="265" height="181" alt="image" src="https://github.com/user-attachments/assets/efac5df3-c4ca-4c31-ae70-57b3c86d7f32" />

# Key Findings

* Emergency department handles the highest patient volume while maintaining relatively controlled waiting times.

* Neurology experiences longer patient wait times despite lower occupancy levels, indicating potential workflow inefficiencies.

* Patient admissions fluctuate throughout the year, with certain months experiencing noticeably higher demand.

* Emergency department operates at the highest bed occupancy levels, indicating strong resource utilization.

* Departmental efficiency varies significantly across hospital units, highlighting opportunities for operational improvements.

* Treatment costs differ across departments, with specialized departments incurring higher average costs.

# Business Recommendations

* Review operational workflows in Neurology to reduce patient waiting times.
* Monitor departments operating near capacity to prevent overcrowding.
* Use admission trends for proactive staffing and resource planning.
* Optimize bed allocation across departments to improve utilization.

# Business Impact

This dashboard helps hospital administrators:

* Monitor operational performance in real time

* Improve bed utilization management

* Identify bottlenecks affecting patient flow

* Support efficient resource allocation

* Enable data-driven healthcare planning

