# Bank Loan Analysis Dashboard

An end-to-end Business Intelligence project developed using **Microsoft Power BI, SQL Server, Power Query, DAX, and Excel** to analyse bank loan applications, funding performance, repayment trends, and borrower characteristics.

The dashboard provides interactive insights into loan portfolio performance, helping users monitor key performance indicators (KPIs), identify lending trends, and evaluate good and bad loan applications.

---

##  Project Overview

The objective of this project is to develop an interactive Bank Loan Analysis Dashboard that provides a comprehensive view of lending operations and loan portfolio performance.

The solution transforms banking data into meaningful business insights through KPI reporting, data modelling, interactive visualisations, and detailed loan-level analysis.

##  Business Objectives

- Monitor overall loan application volume and funding performance.
- Analyse total funded amounts and repayments received.
- Evaluate good loan and bad loan performance.
- Track month-to-date (MTD) and month-over-month (MoM) trends.
- Analyse lending patterns across states, loan purposes, and borrower characteristics.
- Monitor average interest rates and debt-to-income (DTI) ratios.
- Provide detailed loan-level information for further analysis.

---

##  Technology Stack

| Technology | Purpose |
|---|---|
| SQL Server | Data storage and data extraction |
| Microsoft Excel | Data source and data preparation |
| Power Query (M) | Data cleaning and transformation |
| Power BI Desktop | Dashboard development and visualisation |
| DAX | KPI calculations and analytical measures |
| Power BI Service | Report publishing and sharing |
| Row-Level Security (RLS) | Role-based data access |

---

##  Dashboard Structure

The project consists of three interactive dashboard pages.

### 1. Summary Dashboard

Provides a high-level overview of the bank's loan portfolio through key performance indicators and loan quality metrics.

**Key Performance Indicators:**

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)

**Good Loan vs. Bad Loan Analysis:**

Good Loan Metrics:
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Received Amount
- Good Loan Application Percentage

Bad Loan Metrics:
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Received Amount
- Bad Loan Application Percentage

**Additional Analysis:**
- Loan status summary.
- Total loan applications by loan status.
- Funded amount and received amount by loan status.
- MTD funded amount and received amount.
- Average interest rate and DTI by loan status.

### 2. Overview Dashboard

Provides detailed insights into lending trends and borrower characteristics through interactive charts.

**Visualisations Included:**

- **Monthly Trends:** Line chart showing total amount received by month based on loan issue date.
- **Regional Analysis:** State-wise geographical analysis of loan activity.
- **Loan Term Analysis:** Donut chart showing the distribution of loans across different loan terms.
- **Employee Length Analysis:** Bar chart analysing lending metrics across borrower employment durations.
- **Loan Purpose Analysis:** Breakdown of loan metrics by loan purpose.
- **Home Ownership Analysis:** Treemap visualising loan distribution by home ownership status.

**Interactive Filters:**
- State
- Grade
- Good vs. Bad Loan
- Selected Measure

### 3. Details Dashboard

Provides a consolidated view of individual loan records and important loan-related attributes.

**Key Information Included:**
- Loan ID
- Loan Purpose
- Home Ownership
- Grade and Sub-grade
- Issue Date
- Total Funded Amount
- Interest Rate
- Installment Amount
- Total Amount Received

The dashboard enables users to examine loan-level information and explore the underlying records supporting portfolio-level metrics.

---

##  Key Performance Indicators (KPIs)

The dashboard tracks the following major business metrics:

| KPI | Description |
|---|---|
| Total Loan Applications | Total number of loan applications received |
| Total Funded Amount | Total amount disbursed as loans |
| Total Amount Received | Total amount received from borrowers |
| Average Interest Rate | Average interest rate across loans |
| Average DTI | Average debt-to-income ratio |
| Good Loan Percentage | Percentage of applications classified as good loans |
| Bad Loan Percentage | Percentage of applications classified as bad loans |

------

##  Project Workflow

1. **Data Collection:** Import banking datasets from SQL Server and Excel.
2. **Data Preparation:** Clean, transform, and prepare datasets using Power Query.
3. **Data Modelling:** Organise data using a structured data model and star schema approach.
4. **DAX Development:** Create calculated measures and KPIs for loan portfolio analysis.
5. **Dashboard Development:** Build interactive reports with charts, tables, slicers, and navigation.
6. **Security Implementation:** Configure Row-Level Security (RLS) for role-based report access.
7. **Deployment:** Publish reports to Power BI Service and configure scheduled data refresh.

---

## Business Insights

The dashboard enables stakeholders to:

- Monitor overall loan application and funding performance.
- Compare good loan and bad loan distributions.
- Identify monthly lending and repayment trends.
- Understand geographical lending patterns.
- Analyse loan distribution by purpose and term.
- Evaluate borrower characteristics, including employment length and home ownership.
- Examine individual loan records for detailed investigation.



---

##  Skills Demonstrated

- Business Intelligence and Data Analytics
- SQL Server and Data Extraction
- Data Cleaning and Transformation
- Power Query and DAX
- Data Modelling and Star Schema
- KPI Development and Reporting
- Interactive Dashboard Design
- Row-Level Security (RLS)
- Power BI Service and Scheduled Refresh
- Business Requirement Analysis

---

If you find this project useful, feel free to explore the repository and connect with me on LinkedIn.

**Thank you for visiting!**
