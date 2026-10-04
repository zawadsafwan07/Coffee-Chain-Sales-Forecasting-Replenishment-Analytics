# ☕ Coffee Chain Sales, Forecasting & Replenishment Analytics

An end-to-end analytics project designed to transform coffeehouse transaction data into **sales insights, demand forecasts, and inventory replenishment recommendations** using Microsoft 365 Excel, followed by advanced forecasting and analytics techniques.

---

## 🔄 End-to-End Architecture

```text
┌─────────────────────────────┐
│     RAW TRANSACTION DATA    │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│  DATA CLEANING & VALIDATION │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│       HELPER COLUMNS        │
│                             │
│  • Revenue                  │
│  • Hour                     │
│  • Month                    │
│  • WeekStart                │
│  • Weekday                  │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│       SALES ANALYTICS       │
│                             │
│  • KPI Analysis             │
│  • Store Performance        │
│  • Product Performance      │
│  • Category Mix             │
│  • Time-Based Analysis      │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│      DEMAND FORECASTING     │
│                             │
│  • Moving Average           │
│  • Exponential Smoothing    │
│  • Holt-Winters             │
│  • XGBoost                  │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│     INVENTORY PLANNING      │
│                             │
│  • Safety Stock             │
│  • Reorder Point            │
│  • EOQ                      │
│  • Stockout Risk            │
│  • Overstock Risk           │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│     MANAGEMENT DASHBOARD    │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│      BUSINESS DECISIONS     │
└─────────────────────────────┘
```

---

## 📌 Project Philosophy

This project is being built **from the ground up**, starting with data quality and descriptive analytics before moving into predictive modeling and inventory optimization.

The analytical progression is:

> **Understand → Validate → Analyze → Forecast → Optimize → Decide**

Rather than simply building an Excel report, the objective is to demonstrate how **transaction-level coffeehouse data can be transformed into actionable retail intelligence**.

The final system will connect:

**Sales Performance → Customer & Product Demand → Forecasting → Inventory Planning → Replenishment Decisions**

This approach mirrors how analytics can support real-world coffeehouse and retail operations, from understanding what happened to determining **what should happen next**.
