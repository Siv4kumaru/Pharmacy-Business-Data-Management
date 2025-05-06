# Strengthening Inventory Resilience: Pharmacy Retail Analysis & Optimization 🏥💊

**BDM Capstone Project | IITM Online BS Degree Program** 🎓
**Author:** Sivakumar P (Roll number: 21f3001256)

---

## 🎯 Overview

This repository documents the BDM capstone project focused on analyzing and improving inventory management, supplier dynamics, and sales understanding for **Shree Chendur Medical Centre**, a local B2C pharmacy and clinic in Srirangam, Tiruchirappalli. The project leverages data analytics to address operational challenges like stockouts, supplier dependency, and unclear product profitability, ultimately aiming to enhance inventory resilience and overall financial health. ✨

The analysis covers data from **April 2023 to May 2024**.

---

## 🤔 Problem Statement

Shree Chendur Medical Centre faced several operational challenges:

1.  **Frequent Stockouts 📉:** Inadequate inventory planning led to recurring stockouts of key products, causing lost sales and customer dissatisfaction. Planning based on averages failed to account for significant sales volatility.
2.  **Supplier Concentration Risk 🔗:** Excessive reliance on a limited number of primary suppliers exposed the pharmacy to supply chain disruptions and limited negotiation power.
3.  **Lack of Profitability Insights ❓:** Difficulty in discerning the true profitability of individual products and suppliers hindered informed procurement and strategic decision-making.

---

## 💾 Data Source & Preparation

*   **Source:** Raw data consisted of 12 individual monthly summary reports (April 2023 - May 2024) generated in **PDF format** 📄 from the pharmacy's legacy billing software. Datasets included:
    *   Consolidated Closing Stock
    *   Daywise Sales
    *   Purchase Bills
*   **Extraction:** An automated workflow using **Python** 🐍 with the `PDFPlumber` and `re` (Regular Expressions) libraries was developed to extract text and tabular data accurately.
*   **Cleaning & Transformation:** The extracted data was processed using the `Pandas` library in Python. Monthly data was consolidated, cleaned, structured, and enriched. The final cleaned datasets were exported to **CSV format** 📊 for analysis. Excel was also used for auxiliary data organization.

**(Consider adding a simple flow diagram image here: PDF -> Python Script -> Clean CSV)**
`[Optional: Insert Flow Diagram Image]`

---

## 🛠️ Methodology & Analysis

A multi-faceted analytical approach was employed using **Tableau** 📊 for visualization and insights generation:

1.  **Sales vs. Purchase Trends:** Stacked Bar Charts 📈 to visualize monthly sales revenue against purchase costs.
2.  **Sales Volatility Analysis:**
    *   Average Daily/Weekly Sales (Bar Plots) provided a baseline.
    *   **Box Plots** 📦 revealed significant daily variability and outliers, crucial for inventory planning.
3.  **Supplier Dependency Analysis:** Bar charts showing purchase volume per supplier highlighted concentration.
4.  **Profitability Analysis:**
    *   **Pareto Chart (80/20 Rule)** 🎯 identified key profit drivers.
    *   **Pie Charts** 🥧 and **Tree Maps** 🌳 visualized sales and profit contributions by supplier.
5.  **Product Performance Segmentation:** A **Scatter Plot with Quadrant Segmentation** ✨ (Profit vs. Inventory Turnover Rate - ITR) categorized products for strategic focus.

**(Suggestion: If you have a Tableau Public profile or can share screenshots, link key visualizations here!)**
*   *Example Box Plot Insight:* `[Optional: Insert Box Plot Screenshot/Link]`
*   *Example Pareto Chart:* `[Optional: Insert Pareto Chart Screenshot/Link]`
*   *Example Scatter Plot:* `[Optional: Insert Scatter Plot Screenshot/Link]`

---

## 💻 Tools Used

*   **Data Extraction & Cleaning:** Python 🐍 (Pandas, PDFPlumber, re, os)
*   **Data Analysis & Organization:** Python 🐍, Microsoft Excel 📊
*   **Data Visualization:** Tableau 📊

---

## 💡 Key Findings & Insights

*   **Seasonality & Margins 📅:** Sales peaked Nov-Jan. December showed exceptional profit margins. Early months faced margin pressure.
*   **Sales Volatility 🎢:** High daily sales variability and outliers confirmed averages are insufficient for stocking.
*   **Supplier Concentration ⚠️:** Significant risk identified, with >50% purchase volume from top 3 suppliers.
*   **Profit Concentration 💰:** Profit heavily concentrated among a few key suppliers (Biomaxx, Glaxo) - Pareto principle confirmed.
*   **Performance Segmentation 🧩:** Products clearly grouped into 'Stars', 'Pillars', 'Question Marks', and 'Bad' categories, requiring tailored strategies.

---

## ✅ Recommendations

Based on the analysis, the following actionable recommendations were provided:

1.  **Enhance Inventory Management 📦:** Implement safety stock calculations incorporating observed sales volatility (e.g., using upper quartiles).
2.  **Strategic Supplier Diversification 🤝:** Gradually diversify the supplier base while securing relationships with key profit drivers. Explore direct manufacturer links.
3.  **Targeted Profitability Management 🎯:**
    *   Protect margins for 'Pillars' (High Profit, Low Turnover).
    *   Ensure efficiency for 'Stars' (High Profit, High Turnover).
    *   Analyze margins urgently for 'Question Marks' (Low Profit, High Turnover).
    *   Evaluate/delist 'Bad' quadrant items (Low Profit, Low Turnover).
    *   Address loss-making entities directly.

---

## 🚀 Future Developments: E-commerce Integration for the medicine Distributor 🛒📱

Building upon these insights, I am developing a **Integrated e-commerce application** collaborating with multiple connections i made through this project!

*   **Goal:** Convenient Data Delivery and integrity to order and maintain bills through exsisting software, for medical distributors. 🌐
*   **Status:** Demo & final tinkering stages, preparing for consumer launch in the end of june!🎉
*   **Impact:** Modernizes operations, improves customer access, and leverages inventory insights from this project for better online stock management.

## 🙏 Acknowledgments

*   **Shree Chendur Medical Centre:** For providing the necessary data and opportunity. 💊
*   **IIT Madras:** For the excellent framework and guidance via the Online BS Degree Program and BDM Capstone Project. 🎓

---
