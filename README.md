# Client ROI & Lead Quality Tracker 📊

## 🚀 Project Overview

This project is a marketing analytics tool developed to audit and optimize lead generation for a luxury real estate client ("Barrington Villas"). The primary objective was to shift the client's focus from "vanity metrics" (Total Leads) to **profitability metrics** (Cost Per Qualified Lead, Sales Velocity, and ROI).

## 💼 Business Problem

The client was spending $40,000+ monthly across multiple channels (Google, FB, Magazine, Events) but lacked clarity on conversion efficiency. They faced two key issues:

1. **High volume, low quality:** Cheap leads from social media were clogging the sales pipeline.

2. **Unknown Attribution:** They couldn't link "Viewing Requests" back to the specific marketing spend that generated them.

## 🛠️ Solution Architecture

I built a relational data model using Excel to ingest raw campaign data and calculate performance efficiency.

### Data Sources (Excel File Structure)

The project is contained within a single Excel workbook (`Barrington_Villas_ROI_Model.xlsx`) with the following tabs:

* **`RAW_DATA_INPUT`**: Aggregated campaign performance (Spend, Leads, Viewings).

* **`PROPERTY_DATA`**: Inventory performance tracking (Page Views vs. Viewing Requests per Unit Type).

* **`Pitch Dashboard`**: The calculated output layer for stakeholder presentation.

### Key Technical Metrics Calculated

The system automates the calculation of the following KPIs:

* **💰 Cost Per Lead (CPL):** `Total Ad Spend / Total Leads Generated`

  * *Insight:* Identified that while Instagram had the lowest CPL ($6.67), it had the poorest conversion.

* **🎯 High-Intent Conversion Rate:** `(Viewing Requests / Total Leads) * 100`

  * *Insight:* Luxury Magazine ads had a **30% conversion rate** vs. Social Media's 5%, justifying the higher upfront cost.

* **⚡ Sales Velocity:** `Time to Viewing (Days)`

  * *Insight:* Exhibition leads convert 4x faster (10 days) than social media leads (42 days), allowing for better sales resource allocation.

## 📈 Strategic Insights Delivered

Based on the data analysis, the following recommendations were pitched:

1. **Pivot Ad Spend:** Reallocate budget from Facebook (low intent) to Luxury Magazines (high intent) to maximize ROI.

2. **Sales Prioritization:** The sales team should prioritize "Exhibition Follow-up" leads as they have the highest *Sales Velocity* (fastest time-to-close).

3. **Inventory Focus:** "The Penthouse" unit attracted the highest engagement relative to inventory size, suggesting a need for premium-focused ad creatives.

## 🔧 Tools & Technologies

* **Data Processing:** Excel (Data Cleaning, Relational Linking).

* **Analysis:** Pivot Tables, Custom Formulas for weighted averages.

* **Visualization:** Strategic Dashboarding for non-technical stakeholders.

*Note: The dataset provided in this repository is a sanitized sample used for the pitch deck demonstration.*
