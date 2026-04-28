# 📊 Interactive Sales Analytics Dashboard

> A production-grade business intelligence dashboard featuring real-time cross-filtering, 8 dynamic visualizations, and advanced data analytics capabilities.

![Dashboard Preview](screenshot.png)

[![Live Demo](https://img.shields.io/badge/Demo-Live-success)](your-demo-link)
[![GitHub](https://img.shields.io/badge/Code-GitHub-blue)](your-repo-link)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🎯 Project Overview

An interactive sales analytics platform that transforms raw transactional data into actionable business insights. Built with vanilla JavaScript and Chart.js, this dashboard demonstrates advanced frontend engineering, state management, and data visualization techniques.

**Key Metric:** Processes 1,287 sales transactions across 8 dimensions with <500ms filter response time.

---

## ✨ Core Features

### 1. **Cross-Filtering Architecture** 🔄
- Click any chart element to filter ALL visualizations simultaneously
- 6-dimensional filter state management (City, Category, Sales Rep, Payment, Discount, Region)
- Visual feedback with active filter badges
- Individual or batch filter removal
- Smart chart highlighting (selected elements bright, others dimmed)

### 2. **8 Interactive Visualizations** 📈

| Chart Type | Purpose | Interactivity |
|-----------|---------|---------------|
| **Horizontal Bar** | City-wise Sales (Top 10) | Click to filter by city |
| **Doughnut** | Category Performance | Click to filter by category |
| **Bar** | Sales Rep Rankings | Click to filter by rep |
| **Pie** | Payment Method Split | Click to filter by method |
| **Line** | Monthly Trend | Hover for details |
| **Multi-Bar** | Profit vs Sales | Click to filter by category |
| **Color-Coded Bar** | Discount Impact | Click to filter by discount level |
| **Doughnut** | Region Distribution | Click to filter by region |

### 3. **Real-Time KPI Metrics** 📊
- Total Sales (₹ formatted)
- Total Profit (with margin)
- Total Orders (transaction count)
- Average Order Value (AOV)

All KPIs update instantly on filter changes.

### 4. **Advanced Analytics** 🧮
- **Top 5 Products** by sales with visual progress bars
- **Bottom 5 Products** for improvement targeting
- **Profit Margin Analysis** by category
- **Discount Effectiveness** - proves 0% discount = highest profit
- **Geographic Insights** - revenue by region
- **Temporal Trends** - monthly seasonality patterns

### 5. **Responsive Design** 📱