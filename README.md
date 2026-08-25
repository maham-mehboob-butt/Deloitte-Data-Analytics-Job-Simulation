# Deloitte Data Analytics Job Simulation

> Completed through Forage

## Project Overview

This project documents my work completed during the **Deloitte Data Analytics Job Simulation** on Forage.

The simulation focused on practical **business analytics and forensic technology**, using data analysis to investigate operational performance and employee compensation patterns for a fictional client, **Daikibo**.

The practical tasks completed as part of the simulation included:

* **Task 1 — Data Analysis**
* **Task 2 — Forensic Technology**

The project involved working with **Tableau and Excel** to analyze operational telemetry data and investigate potential gender pay disparities across job roles and factory locations.

---

## Task 1 — Data Analysis

### Objective

The first task focused on analyzing telemetry and system data for the fictional client **Daikibo** using Tableau.

### Key Tasks

The analysis involved:

* Building an interactive Tableau dashboard.
* Applying data filters to explore different operational conditions.
* Analyzing telemetry and system data across factory locations.
* Identifying key performance and operational metrics.
* Comparing operational activity across different locations.

### Tool Used

* **Tableau**

The dashboard was used to transform operational data into interactive visual insights that could support business analysis and decision-making.

---

## Task 2 — Forensic Technology

### Objective

The second task focused on conducting a **pay equity analysis** using employee compensation data across different job roles and factory locations.

### Data Preparation

The employee compensation data was prepared and sanitized in **Excel** using the provided `Equality Table.xlsx` dataset.

The analysis involved calculating and classifying the **Equality Score** based on the magnitude of the compensation difference.

### Equality Score Classification

The following nested Excel formula was used:

```excel
=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))
```

The `ABS()` function was used to evaluate the magnitude of the compensation difference regardless of whether the score was positive or negative.

### Classification Logic

| Equality Score           | Classification        |
| ------------------------ | --------------------- |
| -10 to +10               | Fair                  |
| -20 to -11 or +11 to +20 | Unfair                |
| Below -20 or above +20   | Highly Discriminative |

### Analysis

The analysis was used to evaluate potential **gender pay disparities** across:

* Job roles
* Factory locations
* Employee compensation differences
* Equality Score classifications

The classification helped identify areas where compensation differences may require further investigation.

---

## Tools & Technologies

* **Tableau** — interactive dashboards, filtering, and operational data analysis
* **Microsoft Excel** — data preparation, sanitization, formulas, and pay equity analysis

### Analytical Techniques

* Data Cleaning & Preparation
* Data Filtering
* Interactive Dashboard Development
* Operational Data Analysis
* Forensic Data Analysis
* Pay Equity Analysis
* Gender Pay Disparity Analysis
* Rule-Based Classification
* Excel Formula Analysis

---

## Key Skills Demonstrated

* Data Analysis
* Data Cleaning & Preparation
* Data Visualization
* Dashboard Development
* Tableau
* Microsoft Excel
* Forensic Technology
* Pay Equity Analysis
* Data Classification
* Business Analytics
* Analytical Problem Solving
* Data-Driven Decision Making

---

## Certificate

Completed the **Deloitte Data Analytics Job Simulation** through Forage.

The certificate provides evidence of completion of the practical work completed during the simulation.

📜 **[View Certificate →](./Deloitte_Certificate/Deloitte_Data_Analytics_Job_Simulation_Certificate.pdf)**

---

## Project Structure

```text
Deloitte-Data-Analytics-Job-Simulation/
│
├── Deloitte_Certificate/
│   └── Deloitte_Data_Analytics_Job_Simulation_Certificate.pdf
│
└── README.md
```

Original assessment materials and confidential/proprietary content are not included in this repository.

---

## Disclaimer

This repository is a personal portfolio summary of my work completed during the **Deloitte Data Analytics Job Simulation** on Forage.

The client **Daikibo** and associated datasets are part of the simulation environment. This repository documents the analytical approach and skills demonstrated during the simulation and does not reproduce proprietary or confidential assessment materials.
