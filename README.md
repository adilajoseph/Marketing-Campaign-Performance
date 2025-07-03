# Marketing-Campaign-Performance
 It helps to track progress, identify trends, and understand how different channels are performing in real-time. 
This repository contains a simulated marketing dataset along with a detailed guide for building an interactive Power BI dashboard to analyze the performance of marketing campaigns across products, channels, regions, and time.

---

## 📁 Dataset Overview

The dataset represents weekly marketing activities from **January 1, 2023**, across four regions, four products, and four marketing channels. It includes both raw metrics (like spend, impressions, clicks) and calculated KPIs (such as CTR, CPC, and ROI) useful for evaluating campaign performance.

### **Columns Included**
| Column             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `Date`             | Weekly dates starting from Jan 1, 2023                                      |
| `Region`           | North, South, East, West                                                    |
| `Product`          | Product A, B, C, D                                                          |
| `Marketing_Channel`| Social Media, Email, Search Engine, Direct Mail                             |
| `Quarter`          | Q1, Q2, Q3, Q4 (calculated from date)                                       |
| `Spend`            | Amount spent on campaigns ($500 – $5,000)                                   |
| `Impressions`      | Number of people who viewed the marketing content (1,000 – 10,000)          |
| `Clicks`           | Number of clicks generated (100 – 1,000)                                    |
| `Conversions`      | Number of successful outcomes (1 – 50)                                      |
| `Revenue`          | Revenue generated from campaigns ($1,000 – $20,000)                         |

---

### 🔢 Derived Metrics (Calculated Columns)
| Metric | Formula | Description |
|--------|---------|-------------|
| `CTR (%)` | `(Clicks / Impressions) * 100` | Click-Through Rate |
| `CPC` | `Spend / Clicks` | Cost Per Click |
| `ROI (%)` | `((Revenue - Spend) / Spend) * 100` | Return on Investment |

---

## 🧠 Use Cases for Analysis

- **Campaign Effectiveness:** Analyze ROI, CPC, and CTR across channels and products.
- **Regional Performance:** Understand which areas yield the best results.
- **Quarterly Trends:** Uncover seasonal patterns in spend and conversions.
- **Product Insights:** Identify high-revenue and high-ROI products.
- **Channel Comparison:** Determine which marketing platforms are most effective.

---

## 📊 Power BI Dashboard Design

### Dashboard Name: `Marketing Performance Analytics Dashboard`

### 💡 Sections & Visualizations

#### 1. **Campaign Overview (KPI Cards)**
- Total Spend
- Total Revenue
- Average ROI
- Total Conversions
- Average CTR
- Average CPC

#### 2. **Spend vs Revenue Analysis**
- Clustered column or waterfall chart comparing spend and revenue by product/channel
- ROI (%) as a line overlay

#### 3. **Channel Performance**
- Pie or donut chart with Spend, Conversions, or Revenue breakdown by channel

#### 4. **Regional Insights**
- Map visualization showing regional performance using color gradients

#### 5. **Quarterly Trends**
- Line chart of metrics (Spend, Revenue, CTR) over time with filters

#### 6. **Product Performance**
- Treemap or bar chart displaying revenue or conversions by product

#### 7. **ROI & Profitability**
- Heatmap showing ROI by product/channel vs region/quarter

#### 8. **Engagement Metrics**
- Stacked bar or line + column chart for Clicks, Impressions, and CTR

#### 9. **Interactive Slicers**
- Date range
- Region
- Product
- Marketing Channel
- Quarter
- ROI range

---

## 🚀 Advanced Features (Optional)

- **Drill-through Pages:** Deep dive into product, region, or channel data
- **Custom Tooltips:** Hover to view CTR, CPC, ROI
- **Conditional Formatting:** Highlight positive ROI in green, negative in red
- **What-If Analysis:** Use sliders to simulate the impact of projected spend

---

## 🧰 Tools Used

- Power BI Desktop
- DAX (for calculated columns)
- Power Query (for transformations)
