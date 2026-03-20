# Mobile-Data-Analysis

This project is a comprehensive data visualization of the global mobile device market. Using a dataset of various brands and specifications, I built this dashboard to track how hardware features (RAM, Camera, Processors) correlate with pricing across different regions.

## 📊 Project Overview

The goal was to move beyond simple spreadsheets and create an interactive environment where users can compare brands like Apple, Samsung, and Oppo against emerging players like Infinix and Tecno.

### Key Insights from the Dashboard:
* **Market Saturation:** Analysis of model counts per brand (Oppo and Apple leading in this specific dataset).
* **The Price-to-Spec Gap:** Identifying outliers like the Nokia T21 which significantly skews average brand pricing.
* **Hardware Trends:** Most devices are settling into the 16MP-32MP range for front cameras, while 50MP has become the standard for primary back cameras.
* **Global Pricing:** Integrated currency conversion to view price points in USD, PKR, INR, AED, and CNY.

## 📁 Dashboard Structure

The report is split into four main functional areas:

1.  **Overview Page:** High-level stats on model distribution, processor variety, and camera tech.
2.  **Price Analysis:** A dedicated look at "Launched Price" averages. Includes a toggle for different currencies to see how regional markets fluctuate.
3.  **Feature V/S Price:** A granular table view for power users to compare battery capacity, screen size, and weight against the MSRP.
4.  **Matrix Visuals:** Summary tables that aggregate averages for RAM and Weight across all manufacturers.

## 🛠️ Built With

* **Power BI Desktop:** For data modeling and visualization.
* **DAX (Data Analysis Expressions):** Used for calculating regional price conversions and distinct counts.
*  **Power Query:** Handled the data cleaning, specifically formatting the "Camera" strings and "RAM" sizes into numeric values for plotting.

## 🚀 How to Use

1.  **Filter by Brand:** Use the 'Company Name' slicer at the top of the Overview or Price pages to isolate specific manufacturers.
2.  **Price Range Slicing:** On the "Feature V/S Price" page, use the range sliders to find phones that fit a specific budget or RAM requirement.
3.  **Currency Switch:** Use the chevron-style navigation buttons (AED PA, USD PA, etc.) to jump between different regional price analyses.

## 💡 What I Learned
During this build, I focused heavily on **UI/UX consistency**. I chose a muted purple and pink palette to keep the visuals clean and professional. One challenge was handling "Multi-camera" data strings (e.g., "12MP + 10MP"), which required custom splitting in Power Query to ensure the charts didn't break.

---
