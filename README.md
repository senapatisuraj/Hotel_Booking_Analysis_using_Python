# Hotel Booking Analysis Project

This project involves exploratory data analysis (EDA) and insights generation using a hotel booking dataset of 119,390 records and 32 columns. The primary goal is to understand key factors influencing booking cancellations and to provide actionable recommendations to improve hotel revenue and customer satisfaction.

---

## Table of Contents

- About the Project
- Business Problem
- Key Objectives
- Data Description
- Technologies Used
- Key Findings
- Recommendations

---

## About the Project

This data analytics project analyzes a hotel booking dataset to identify factors leading to booking cancellations. It uses data cleaning, visualization, and statistical analysis techniques to extract meaningful insights that can help reduce cancellations and improve operational efficiency.

---

## Business Problem

Hotel booking cancellations can lead to significant revenue loss and resource mismanagement. Understanding the factors contributing to cancellations can help stakeholders design better policies, enhance customer experiences, and improve forecasting accuracy.

---

## Key Objectives

- Analyze booking behaviors and trends.
- Identify patterns in cancellations.
- Detect peak and low seasons for bookings.
- Suggest data-driven strategies to reduce cancellation rates.
- Improve customer segmentation and targeting.

---

## Data Description

- **Rows**: 119,390  
- **Columns**: 32  
- **Key Columns**:
  - `is_canceled`
  - `lead_time`
  - `arrival_date_month`
  - `country`
  - `customer_type`
  - `deposit_type`
  - `market_segment`
  - `booking_changes`
  - `agent`, `company`, `children`, `babies` (some missing values handled)

---

## Technologies Used

- **Language**: Python  
- **IDE**: Jupyter Notebook  
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
---

## Key Findings

- Most cancellations occurred for city hotels and during the summer months (especially July and August).
- Bookings with **longer lead times** and **no deposit policy** had higher cancellation rates.
- **Transient** and **online travel agents (OTA)** contributed the most to cancellations.
- Countries like **Portugal, UK, France, and Spain** had the highest bookings.
- Families with children were more likely to cancel than solo travelers.

---

## Recommendations

- Implement flexible cancellation policies for high-risk customer types.
- Use predictive modeling on lead time and booking channel to forecast potential cancellations.
- Increase promotional efforts during off-peak seasons.
- Offer loyalty programs to retain repeat and corporate customers.
