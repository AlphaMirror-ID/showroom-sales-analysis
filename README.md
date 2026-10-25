# Showroom Sales Analysis

An end-to-end data analysis portfolio project exploring sales performance across a 10-branch car showroom dataset. The project uses a cleaned dataset and a Power BI dashboard to present sales insights in an accessible, visual format.

## Project Overview

This project analyzes showroom sales data from 10 branches to help understand sales performance and support data-informed business decisions.

**Dataset:** `showroom_mobil_10cabang_clean.csv`  
**Dashboard:** Power BI (`Dashboard-Showroom.pbix`)  
**Report:** `showroom-sales-analysis-report.pdf`

## Objectives

- Explore sales performance across showroom branches.
- Present key sales metrics and trends through a Power BI dashboard.
- Communicate findings and potential business opportunities through a written report.

*Specific metrics and findings should be added here after they have been verified against the dataset and report.*

## Tools & Technologies

- **CSV** — cleaned dataset
- **Microsoft Power BI** — interactive dashboard
- **Data analysis** — sales performance exploration and reporting

## Repository Structure

```text
showroom-sales-analysis/
├── README.md
├── data/
│   └── showroom_mobil_10cabang_clean.csv
├── dashboard/
│   ├── dashboard-overview.png
│   └── Dashboard-Showroom.pbix
└── reports/
    └── showroom-sales-analysis-report.pdf
```

## Dataset

The repository includes the cleaned dataset `showroom_mobil_10cabang_clean.csv`.

For data privacy, file size, or licensing reasons, consider checking whether the dataset is appropriate to publish publicly before committing it to the repository.

## Dashboard Preview

![Showroom Sales Dashboard](dashboard/dashboard-overview.png)

The screenshot above provides a preview of the dashboard. To explore the interactive report, download `Dashboard-Showroom.pbix` from the `dashboard/` directory and open it in Microsoft Power BI Desktop.

## Project Report

The report is available at:

[`reports/showroom-sales-analysis-report.pdf`](https://github.com/AlphaMirror-ID/showroom-sales-analysis/blob/main/reports/showroom-sales-analysis-report.pdf)

It documents the analysis and findings from the project.

## Key Findings

- **Total sales:** Rp3,092,685,000,000 across **10,000 transactions** and **10,433 units**.
- **Completion rate:** 89.7%, representing **8,966 completed transactions**.
- **Top vehicle category:** SUVs generated Rp1,680,293,000,000, contributing **54.3%** of total sales. MPVs ranked second with Rp997,200,000,000.
- **Branch performance:** Malang recorded the highest total sales at **Rp324,667,000,000**. Karawang recorded the lowest at **Rp295,398,000,000**.
- **Top product:** Honda CR-V 1.5 Turbo RS ranked first by total sales.
- **Monthly trend:** August recorded the highest sales, while June recorded the lowest.
- **Transaction status:** 542 transactions were cancelled and 492 were refunded, totaling **1,034 transactions (10.3%)** that were not completed.
- **Payment method:** Credit was the most frequently used payment method.
- **Trade-in:** 3,523 transactions (35.2%) were marked as trade-in.

*Figures above are taken from the project's showroom analysis report. Sales value is not the same as profit or margin; profitability data would be needed to assess profit performance.*

## Business Recommendations

1. **Prioritize SUV demand planning.** SUVs account for 54.3% of total sales, so monitor SUV demand, stock availability, and sales performance regularly. Keep MPVs under close review as the second-largest category.
2. **Use Malang as a comparison point, not an automatic template.** Review Malang's sales approach and compare its category mix, transaction volume, and completion rate with other branches before applying practices elsewhere.
3. **Investigate cancelled and refunded transactions.** Track the 542 cancelled and 492 refunded orders by branch, product, month, and payment method to identify where further investigation is most useful. The current aggregate figures do not establish the causes.
4. **Review the monthly sales pattern.** Compare August's high sales with June's low sales and check whether the difference relates to vehicle category, branch performance, promotions, or transaction volume before planning future campaigns.
5. **Monitor transaction completion alongside sales.** Report completed, cancelled, and refunded transactions together with total sales so that the team can distinguish gross sales activity from completed orders.
6. **Review the credit payment journey.** Since credit is the most frequently used payment method, monitor its completion and cancellation rates to identify potential process improvements. The data alone does not prove that credit causes cancellations or refunds.
7. **Track trade-in activity.** Trade-in accounts for 35.2% of transactions. Compare its sales and completion metrics with non-trade-in transactions to evaluate its role in the sales process.

## Author

**Aziyusman Maulana**

Data Analytics Portfolio Project
