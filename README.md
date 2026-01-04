# 📦 Inventory Heatmap & Stock-Out Alerts for Essential Goods

## Description
This project implements a Snowflake-native inventory intelligence system designed to help hospitals, NGOs, and public distribution systems maintain continuous availability of essential goods such as medicines and food.

The solution integrates daily inventory and usage data, automatically computes stock health using consumption trends and supplier lead times, and classifies items into Critical, Warning, and Healthy categories. An interactive Streamlit dashboard provides a single view of inventory health, visualizes risk using heatmap-style tables and severity-based charts, and generates actionable reorder quantity and priority recommendations that procurement teams can export and execute immediately.

Built using Snowflake SQL, Dynamic Tables, and Streamlit, the system is scalable, auto-refreshing, and validated using a real-world Kaggle dataset. By proactively identifying stock-out risks and reducing over-stocking, the solution supports AI for Good objectives by minimizing waste and preventing shortages of critical supplies.

## Problem
Hospitals, NGOs, and public distribution systems often face shortages or wastage of essential goods due to fragmented inventory data and delayed insights.

## Solution
This project provides a Snowflake-native inventory intelligence system that:
- Creates a single view of stock health
- Identifies early stock-out risks
- Visualizes risk using heatmap-style views
- Recommends reorder quantities with priorities
- Enables CSV export for procurement teams

## Architecture
Kaggle Dataset → Snowflake SQL → Dynamic Tables → Alerts & Reorder Views → Streamlit Dashboard

## Tech Stack
- Snowflake (SQL, Dynamic Tables, Streamlit)
- Python
- Kaggle Dataset

## AI for Good Impact
Ensures availability of essential goods while reducing waste.

## Screenshots
See the screenshots folder.
