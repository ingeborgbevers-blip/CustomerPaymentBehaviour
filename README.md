# Customer Payment Behaviour & Cash Flow Risk Analysis

![Power Bi Dashboard](PowerBI Dashboard .png)

## Overview

This project explores how customer payment behaviour affects cash flow stability within an SME-style accounts receivable environment.

Using a synthetic dataset built in Excel and analysed in Power BI, the project focuses on operational finance reporting rather than purely accounting outputs. The aim was to move beyond headline KPIs and identify where timing, exposure, and customer behaviour create genuine cash flow pressure.

The project was designed as a practical reporting and analytics case study suitable for:

* SME finance environments,
* operational reporting teams,
* ERP / SAP-style reporting demonstrations,
* Power BI portfolio work,
* and finance process improvement discussions.

---

# The Problem

At first glance, average lateness across the dataset appeared manageable:

* Average Days Late: 7.29
* Average Invoice Value: £3.45K
* Total Invoice Value: £16M

However, deeper analysis revealed a more operationally significant issue:

* 44.30% of invoices were overdue,
* several customers exceeded 50% overdue exposure,
* and a small number of higher-volume customers represented disproportionate cash flow risk.

This reflects a common finance reporting challenge:

> Average KPIs can hide exposure concentration and operational pressure.

A customer paying five days late on a low-value account may have minimal impact.

A customer paying five days late on a high-volume account may materially affect cash flow stability.

---

# The Approach

The project used a synthetic but operationally realistic accounts receivable dataset containing:

* 4,500+ invoice records,
* multiple industries,
* varying customer payment terms,
* payment behaviour categories,
* overdue risk flags,
* reminder counts,
* and invoice ageing logic.

The analysis focused on:

* customer payment behaviour,
* overdue concentration,
* exposure analysis,
* ageing trends,
* operational finance risk,
* and receivables management effectiveness.

The dashboard was intentionally designed to:

* remain executive-readable,
* prioritise operational meaning,
* and support decision-making rather than simply displaying metrics.

---

# The Solution

The Power BI dashboard combines:

## Executive KPIs

* Total Invoice Amount
* Average Invoice Amount
* Overdue Percentage
* Average Days Late
* Maximum Days Late

## Customer Behaviour Analysis

* customer-level payment behaviour,
* overdue percentages,
* payment term comparisons,
* and invoice concentration.

## Risk & Exposure Analysis

Scatter plot analysis was used to identify:

* customers with high exposure,
* high-risk concentration,
* and disproportionate operational impact.

This helped separate:

* low-impact late payment,
  from:
* meaningful cash flow exposure.

## Operational Recommendations

The dashboard also includes practical finance recommendations such as:

* reviewing payment terms,
* proactive receivables intervention,
* earlier customer engagement,
* and rewarding strong payment behaviour proportionately.

---

# Dashboard Highlights

Key observations from the final analysis included:

* 44.30% overdue invoices,
* maximum lateness of 92 days,
* several customers exceeding 50% overdue exposure,
* and one customer representing approximately 8% of total invoice value flagged as high risk.

The analysis demonstrated that:

* average lateness alone is insufficient,
* exposure concentration matters,
* and small delays on high-volume customers can materially increase financial risk.

---

# Demo

The repository includes:

* Power BI dashboard screenshots
* sample synthetic CSV datasets
* DAX measures
* calculated columns
* risk categorisation logic
* customer payment behaviour analysis

Suggested walkthrough order:

1. Executive summary page
2. Customer payment behaviour table
3. Trend analysis
4. Scatter plot exposure analysis
5. Risk category analysis
6. Operational recommendations

---

# How to Run

## Requirements

* Power BI Desktop
* CSV source files included in the repository

## Steps

1. Download or clone the repository

```bash
git clone <repository-url>
```

2. Open the `.pbix` file in Power BI Desktop

3. Refresh the data model if required

4. Review relationships:

* Customer table → Invoice table
* Date table → Invoice dates

5. Explore:

* customer behaviour trends,
* exposure concentration,
* overdue analysis,
* and operational risk indicators.

---

# Dataset Notes

This project uses synthetic data created for analytical demonstration purposes.

The dataset was intentionally designed to:

* resemble realistic SME finance behaviour,
* include operational irregularities,
* and support reporting and visualisation scenarios.

No real customer or financial information is included.

---

# Key Takeaway

The most useful finance reporting often explains timing, exposure, and behaviour together.

Because cash flow pressure rarely appears first in the averages.
