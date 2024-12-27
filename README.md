# Food Inspection Data Analysis Project

---

## Project Overview
This project analyzes food inspection data from Chicago and Dallas to enhance data handling, visualization, and business intelligence reporting. The workflow includes data profiling, transformation, staging, and implementing a dimensional data model. Key insights are visualized using Tableau and PowerBI dashboards, supported by thorough data validation.

---

## Table of Contents
1. [Key Features](#key-features)
2. [Data Profiling](#data-profiling)
3. [Data Staging](#data-staging)
4. [Dimensional Data Model](#dimensional-data-model)
5. [Business Intelligence Visualizations](#business-intelligence-visualizations)
6. [Testing and Validation](#testing-and-validation)
7. [Getting Started](#getting-started)
8. [Future Scope](#future-scope)

---

## Key Features
- Data profiling for enhanced usability and accuracy.
- Automation of data transformation using Talend workflows.
- Implementation of a scalable dimensional model.
- BI dashboards in Tableau and PowerBI for actionable insights.
- Validation and testing to ensure data integrity and analytical accuracy.

---

## Data Profiling
- **Handling Multi-Valued Attributes:**
  - Techniques include column splitting, row expansion, and aggregation.
  - Violation data transformed for row-level granularity.
- **Data Type Conversion:**
  - Conversion of dates, numeric fields, and categorical columns.
  - Standardization for geospatial and category-based analysis.

---

## Data Staging
- Separate workflows for Dallas and Chicago datasets.
- Efficient staging processes for geolocation, violation codes, and inspection results.

---

## Dimensional Data Model
1. **Dimensions:**
   - `AddressDim`: Standardized location details.
   - `DimDate`: Inspection date attributes (day, month, year).
   - `DimInspectionType`: Inspection categories and risk levels.
   - `DimViolations`: Violation codes, descriptions, and points.
   - `FacilityDim`: Facility details, including license and type.

2. **Facts:**
   - `InspectionFact`: Links dimensions with measures like total violation scores and results.

---

## Business Intelligence Visualizations
- **Tableau Dashboards:**
  - Inspection counts over years.
  - Inspection trends by risk and location.
- **PowerBI Dashboards:**
  - Facility type vs. inspection results.
  - Top 10 facilities by violation scores.

---

## Testing and Validation
- Inspection count trends by year.
- Location-based comparisons (Chicago vs. Dallas).
- Insights into high-risk and top-performing facilities.

---

## Getting Started
1. **Data Transformation:**
   - Use Talend workflow scripts for staging.
   - Ensure data conversions and multi-valued attribute handling as specified.
2. **Database Setup:**
   - Execute SQL scripts to create dimensional tables and facts.
3. **Visualizations:**
   - Load data into Tableau or PowerBI for analysis.
4. **Testing:**
   - Use provided test cases to validate data and insights.

---

## Future Scope
- Expand the model to additional cities and datasets.
- Integrate predictive analytics for proactive risk management.
- Develop real-time monitoring dashboards in Tableau and PowerBI.

---

Feel free to contribute or adapt this project for your needs!
