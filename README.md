# Credit Card Complaints Dashboard

An interactive Tableau dashboard that analyzes **86,893 credit card complaints**. It shows complaint trends over time, the most common issues, how companies respond, geographic hotspots, and how complaints are submitted.

## Dashboard Preview

![Credit Card Complaints Dashboard](images/dashboard.png)

🔗 **Live Dashboard:** [Add your Tableau Public link here]

## Objective

To help answer:
- What do customers complain about most?
- How does complaint volume change over time?
- Where are complaints concentrated across the US?
- How do companies respond, and how quickly are complaints resolved?
- Which channels do customers use to file complaints?

## Dataset

- **Source:** [e.g., Consumer Financial Protection Bureau (CFPB) / Kaggle]
- **Records:** 86,893 complaints
- **Time period:** 2016 – 2021
- **Key fields:** Date received, Company, State, Issue, Company response, Timely response, Submitted via

## Key Features

- **KPI cards:** Total complaints, rolling 12-month count, timely response rate, and in-progress complaints, each with a sparkline
- **Weekly trend:** Area chart with an average reference line, switchable between trend views
- **State-wise map:** Switch between a density map and a filled map
- **Top issues:** Ranked bar chart of complaint categories
- **Company response:** Breakdown of how complaints were resolved
- **Daily complaints calendar:** Heatmap for any selected month
- **Submitted via:** Share of complaints by channel
- **Filters:** Year, Company, and State
- **Export panel:** Download the dashboard as PDF, PowerPoint, or image

## Key Insights

- **86,893** total complaints, with **20,202** in the rolling last 12 months
- **98.90%** of complaints received a timely response, and only **0.38%** (329) are still in progress
- Weekly complaints average about **310**, with a peak of **651** in a single week
- **Billing disputes** are the top issue (14,688), followed by *Other* (9,049) and *Identity theft / fraud* (8,244)
- About **60%** of complaints are closed with an explanation, and about **21%** with monetary relief
- **68.92%** of complaints are submitted via the web, compared with just 0.05% by email
- Complaints are concentrated in densely populated areas, especially the East Coast and California

## Tools Used

- **Tableau** (Desktop / Public) for visualization, filters, and dashboard actions
- [Excel / Python / SQL, if used for data cleaning]

## How to View

1. Open the live dashboard link above, **or**
2. Download the `.twbx` file from this repository and open it in Tableau Desktop or Tableau Public.

## Repository Structure

```
├── Credit_Card_Complaints.twbx   # Tableau workbook
├── data/                         # Dataset (if allowed to share)
├── images/
│   └── dashboard.png             # Dashboard screenshot
└── README.md
```

## Author

**Shamila P.**
