# ITSM Incident Analysis

## Project Overview

This project analyzes IT Service Management (ITSM) incident data to identify:

- Most affected systems
- Incident distribution patterns
- High-risk systems
- Reliability insights

The analysis was performed using Python, Pandas, and Matplotlib.

---

## Objectives

- Explore incident-system relationships
- Identify systems with repeated incidents
- Categorize systems by risk level
- Generate business insights for system monitoring

---

## Dataset

Dataset contains:

- incident_id
- system_id

Each row represents a relationship between an incident and a system.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Analysis Performed

### 1. Dataset Overview

- Shape analysis
- Data type inspection

### 2. Basic Statistics

- Total incidents
- Total systems

### 3. Top Affected Systems

Identified systems with the highest incident counts.

### 4. Incident Distribution

Visualized how incidents are distributed across systems.

### 5. Risk Classification

Systems were categorized as:

| Incident Count | Risk Level |
|--------------|------------|
| 1 | Low Risk |
| 2-3 | Medium Risk |
| 4+ | High Risk |

---

## Key Findings

- Total Incidents: 500
- Total Systems: 343
- Most systems experienced only one incident
- A small number of systems experienced repeated incidents
- High-risk systems require additional monitoring

---




## Author

Aleesha Nadeem

