# 🚒 London Fire Brigade — Data Analysis

🇬🇧 **English** | [🇫🇷 Français](README_FR.md)



### 📌 Project Overview

This project analyzes **London Fire Brigade operational data from 2021 to 2025** to understand the relationship between emergency incidents, resource mobilization, response times and operational costs.

The objective was to identify the main drivers of operational activity and expenditure while assessing whether the London Fire Brigade maintained an efficient level of service.

The analysis is based on official open datasets published by the **City of London**, combining:

- London Fire Brigade Incident Records
- London Fire Brigade Mobilisation Records

---

### 🎯 Objectives

The project focuses on three main analytical dimensions:

- Incidents
- Response times
- Operational costs

The analysis aims to:

- Identify trends in incidents and mobilisations
- Evaluate operational response times
- Understand the evolution and drivers of intervention costs
- Identify geographical disparities
- Highlight potential opportunities for resource optimisation

---

### 🛠️ Tools & Technologies

- Python
- pandas
- Google Colab
- Power BI
- Power Query
- Data Visualization

---

### 🔄 Data Processing Workflow

The original data came from **four files: 2 Excel files and 2 CSV files** containing incident and mobilisation records.

The workflow included:

`Data Import → Exploration → Cleaning → Missing Values Management → Date Transformation → Dataset Merge → Exploratory Analysis → Power BI → Dashboard & Storytelling`

Incident and mobilisation datasets were connected using the common **IncidentNumber** identifier.

---

### 📊 Key Results

The final analysis covers approximately:

- **598K incidents**
- **930K mobilisations**
- **£301.67M estimated total operational cost**
- **£504.53 average cost per intervention**

Between 2021 and 2025:

| KPI | 2021 | 2025 | Evolution |
|---|---:|---:|---:|
| Incidents | 102K | 131K | +28% |
| Mobilisations | 158K | 206K | +30% |
| Average cost | £443.19 | £588.90 | +33% |
| Total cost | £45.24M | £76.91M | +70% |

Operational costs therefore increased significantly faster than activity volumes, with a particularly strong acceleration from 2024 onwards.

---

### 🔎 Key Insights

#### False alarms

False alarms represent the main optimisation opportunity.

They account for approximately:

- **50% of incidents**
- **41% of total costs**
- Approximately **£124M**

Despite their non-critical nature, they generate a significant operational workload.

#### Residential activity

Residential properties are at the centre of operational activity.

Dwellings represent:

- **63% of mobilisations**
- **56.6% of total costs**

A large part of this activity is linked to residential false alarms.

#### Geographic disparities

The analysis highlights a clear difference between central and peripheral London.

Central London concentrates the highest intervention volumes, while some peripheral areas such as:

- Wennington
- Erith
- Hayes

show longer intervention times and higher unit costs.

#### Operational performance

Despite increasing financial pressure, operational performance remains strong:

- **Median response time: 5.63 minutes**
- **Delayed mobilisations: 0.04%**
- **96.24% of mobilisations deployed from the assigned station**

---

### 👩‍💻 My Contribution

This project was completed as a team project.

My contribution covered several stages of the data pipeline:

- Data import
- Data exploration
- Data cleaning
- Data transformation
- Exploratory visualization
- Data preparation for Power BI

Within the Power BI analysis, my main responsibility was the **operational cost analysis**.

The objective was to:

- Understand the cost structure
- Identify the main cost drivers
- Analyze cost evolution
- Highlight potential optimization opportunities

---
