# 📞 Flipkart Customer Service Analysis Dashboard

> Analysing 30,000 customer support calls to identify the root causes of poor satisfaction and recommend actionable solutions to improve customer retention.

---

## Dashboard Overview
[Flipkart Customer Service Analysis] <img width="914" height="550" alt="Dashboard_Flipkart_Customer_Service_Analysis" src="https://github.com/user-attachments/assets/5aff64db-37c0-4dad-9b89-7042877540b8" />


## 📊 Project Overview

| Attribute | Detail |
|-----------|--------|
| **Tool** | Microsoft Excel |
| **Data** | 30,000 customer calls |
| **Time Period** | October 2020 |
| **Call Centers** | Delhi, Mumbai, Kolkata, Chennai |
| **Channels** | Call-Center, Chatbot, Email, Web |
| **Call Reasons** | Billing Questions, Payments, Service Outage |

---

## 🔢 Key Metrics

| Metric | Value |
|--------|-------|
| Total Calls Analysed | 30,000 |
| Avg CSAT Score | 5.54 / 10 |
| Negative Sentiment | 51.8% (15,526 calls) |
| Billing-Related Calls | 71.4% (21,410 calls) |
| Calls Above SLA | 12.7% |
| Avg Call Duration | 25 minutes |

---

## 📁 Files in This Repository

```
📁 Flipkart-Customer-Service/
│
├── 📊 Dashboard_Flipkart_Customer_Service_Analysis.jpg   # Excel dashboard screenshot
├── 📑 Flipkart_Customer_Service_Analysis_Presentation.pdf # Full analysis presentation
└── 📄 README.md                                           # This file
```

---

## 📐 Metric Tree

```
🎯 BUSINESS GOAL: Improve Customer Retention
│
└── ⭐ PRIMARY METRIC: CSAT Score (Avg 5.54 / 10)
        │
        ├── 😤 SENTIMENT (51.8% Negative)
        │       └── · Call Center Location
        │
        ├── ⏱ RESPONSE TIME (12.7% Above SLA)
        │       └── · Contact Channel
        │
        └── 📞 CALL DURATION (Avg 25 mins)
                └── · Call Reason
```

---

## 🔍 Dashboard Components

The Excel dashboard includes:
- **KPI Cards** - Total Calls, Avg CSAT Score, Negative Sentiment %, Billing Calls %
- **Sentiment Overview Table** - Call counts and CSAT scores by sentiment category
- **Average CSAT by Sentiment Chart** - Bar chart showing CSAT range from 2.46 to 9.49
- **Call Reason Split** - Pie chart (Billing 72%, Payments 14%, Service Outage 14%)
- **Call Center Performance Table** - CSAT and SLA breach % by city
- **Channel Performance Table** - CSAT and negative sentiment % by contact channel

---

## 💡 Key Findings

**Finding 1 - Sentiment Drives CSAT**

| Sentiment | Calls | % | CSAT |
|-----------|-------|---|------|
| Very Negative | 5,425 | 18.1% | 2.46 |
| Negative | 10,101 | 33.7% | 4.52 |
| Neutral | 8,003 | 26.7% | 6.47 |
| Positive | 3,557 | 11.9% | 8.00 |
| Very Positive | 2,914 | 9.7% | 9.49 |

**Finding 2 - Billing Calls Dominate Volume**

71.4% of all calls are billing-related — this is a product design problem, not a support problem.

**Finding 3 - Call Center Performance**

| City | Total Calls | Avg CSAT | Above SLA |
|------|-------------|----------|-----------|
| Chennai | 2,541 | 5.63 | 12.3% |
| Delhi | 12,531 | 5.57 | 12.7% |
| Mumbai | 10,002 | 5.53 | 12.7% |
| Kolkata | 4,926 | 5.46 | 12.9% |

---

## 🧪 Hypothesis Results

| # | Hypothesis | Result |
|---|-----------|--------|
| H1 | Response Time → CSAT | ❌ Not Confirmed |
| H2 | Sentiment → CSAT | ✅ Confirmed |
| H3 | Channel → Satisfaction | ❌ Not Confirmed |
| H4 | Call Center → Performance | ⚠️ Partial |
| H5 | Call Reason → Sentiment | ❌ Not Confirmed |

---

## 💡 Top 3 Recommendations

1. **Invest in Agent Training** - 51.8% of calls are Negative/Very Negative. Sentiment directly predicts CSAT. Agent empathy training is the #1 lever.

2. **Fix Billing UX** - 71% of calls are billing issues. Clearer invoices, proactive SMS alerts, and a self-service portal will slash inbound volume.

3. **Review Kolkata Call Center** - Kolkata has the lowest CSAT (5.46) and highest SLA breach rate (12.9%). Audit and train urgently.

---

## 🛠️ Tools Used

- **Microsoft Excel** - Pivot tables, charts, KPI cards, dashboard layout

---

## 👩‍💻 Author

**Vaishali Parmar**  
Data Analyst | Next Leap Program  
Milestone 1 - Flipkart Customer Service Analysis

---

*This project is part of the Next Leap Data Analytics Program*
