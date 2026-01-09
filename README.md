# Insight Arbiter

**Turning conflicting metrics into confident business decisions**

---

## 🚀 Overview

**Insight Arbiter** is a decision-intelligence prototype built using Tableau that addresses one of the most common and unresolved problems in business analytics: **conflicting metrics across dashboards**.

When dashboards disagree—such as revenue increasing while profit declines—teams often debate numbers instead of making decisions. Insight Arbiter detects these conflicts, explains why they occur, evaluates metric confidence, understands decision context, and guides users toward the right decision.

---

## 🧩 Problem Statement

In real-world organizations:
- Different teams rely on different dashboards
- Key KPIs often conflict (e.g., Revenue ↑ vs Profit ↓)
- Meetings stall due to confusion over which metric to trust
- Decisions are delayed or avoided

Traditional BI tools visualize data but do not help resolve **metric conflicts**.  
Insight Arbiter fills this gap by shifting analytics from reporting to **decision intelligence**.

---

## 💡 Solution

Insight Arbiter acts as an interpretive layer on top of Tableau dashboards. It:

- Detects conflicting KPIs automatically
- Explains the root cause of metric disagreement
- Assigns confidence levels to each metric
- Understands the decision context (e.g., Pricing vs Growth)
- Previews the impact of prioritizing one metric over another
- Recommends which metric to use for the current decision

Dashboards remain unchanged—Insight Arbiter interprets them.

---

## 🛠️ Built With

- **Tableau Cloud** – Dashboard hosting, sharing, and deployment
- **Tableau Desktop / Web Authoring** – Dashboard creation and logic
- **Tableau Calculated Fields & Parameters** – Conflict detection, confidence scoring, decision logic
- **CSV Files** – Sample enterprise datasets (Sales & Finance)

No external APIs, machine learning frameworks, or third-party platforms are required.

---

## 📁 Project Structure

```text
.
├── data/
│   ├── sales_data.csv
│   └── finance_data.csv
├── dashboards/
│   ├── Sales Dashboard
│   ├── Finance Dashboard
│   └── Insight Arbiter Dashboard
├── demo/
│   └── demo_video.mp4
└── README.md
