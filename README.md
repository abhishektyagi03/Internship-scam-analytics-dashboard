# 🚨 Internship Scam Analytics Dashboard | Power BI

An interactive **Power BI Internship Scam Analytics Dashboard** created to analyze internship listings, identify genuine and scam opportunities, compare scam reports across cities and domains, and explore stipend, placement-promise, company, and remote-work risk indicators.

## 📌 Dashboard Preview

![Internship Scam Analytics Dashboard](Dashboard/internship_scam_analytics_dashboard.png)

## 🎯 Project Objective

The objective of this project is to transform internship listing data into an interactive business intelligence dashboard that helps users understand the scale and distribution of potential internship scams.

The dashboard focuses on genuine versus scam listings, scam reports by city and domain, stipend distribution, placement promises, remote-work patterns, and company-level scam reporting. It is designed to support awareness, risk analysis, and data-driven evaluation of internship opportunities.

## 📈 Key KPIs

The dashboard highlights the following business metrics:

* 📋 **Total Listings** — 10K shown in the dashboard
* 🛡️ **Genuine Listings** — 9,529 shown in the dashboard
* 🚨 **Scam Listings** — 471 shown in the dashboard
* 💰 **Average Stipend** — 25K shown in the dashboard
* 📊 **Total Listings** — 10K shown in the dashboard

> KPI values depend on the underlying dataset and active dashboard filters. The screenshot shows the dashboard filtered to the Africa region and the displayed year selection includes 2011–2014.

## 🎛️ Dashboard Filters

The dashboard includes interactive filters for:

* **Domain**
* **City**
* **Duration in Months**
* **Website Age in Years**

Users can combine these filters to compare scam activity across internship domains, cities, internship durations, and website age groups.

## 📊 Dashboard Features

* Genuine versus scam listing analysis
* Scam listing analysis by city
* Scam reporting by internship domain
* Stipend distribution analysis
* Placement-promise comparison
* Remote versus non-remote scam analysis
* Company-level scam report analysis
* Interactive Power BI filtering
* Risk-focused visual analytics

## 📊 Visualizations Used

### 1. Genuine vs Scam

A donut chart comparing genuine and scam internship listings. The displayed dashboard shows 9.53K genuine listings and 471 scam listings.

### 2. Scam Listings by City

A horizontal bar chart ranking cities by scam report count, helping identify locations with higher reported scam activity.

### 3. Scam Listings by Domain

A donut chart comparing scam reports across internship domains such as AI, Data Analytics, Finance, HR, Marketing, and Web Development.

### 4. Company-Level Scam Reports

A detailed table showing companies and their corresponding scam report counts for more granular risk analysis.

### 5. Stipend Distribution

A column chart showing the number of internship listings across stipend ranges, helping identify suspicious or unusually concentrated stipend patterns.

### 6. Placement Promise vs Scam

A comparison chart analyzing scam listings based on whether a placement promise is present.

### 7. Scam by Remote Work

A donut chart comparing scam listings associated with remote and non-remote internship opportunities.

### 8. Interactive Slicers

The dashboard provides slicers for Domain, City, Duration in Months, and Website Age in Years, allowing users to perform focused risk analysis.

## 💡 Analytical Questions Answered

This dashboard can help answer questions such as:

* How many internship listings are genuine versus potentially fraudulent?
* Which cities have the highest number of scam reports?
* Which internship domains show higher scam activity?
* What stipend ranges are most common among listings?
* How frequently are placement promises associated with scam listings?
* Are remote internship listings associated with different scam patterns?
* Which companies have the highest number of scam reports?
* How does website age relate to internship listing risk?
* How do scam patterns change when Domain, City, Duration, or Website Age filters are applied?

## 🔎 Key Insights

Based on the dashboard displayed:

* The dashboard shows approximately **10K total internship listings**.
* **9,529 listings** are classified as genuine, while **471 listings** are classified as scams in the displayed view.
* Scam activity is distributed across multiple internship domains, including AI, Data Analytics, Finance, HR, Marketing, and Web Development.
* Scam listings can be compared across cities to identify locations with higher reported activity.
* Stipend distribution provides an additional signal for evaluating internship listings and identifying unusual patterns.
* Placement promises and remote-work status are separately analyzed to identify possible relationships with scam listings.
* Company-level scam reports provide a more granular view of potentially risky organizations.

> These observations are based on the visible dashboard screenshot. They should be validated against the underlying dataset before being used for formal reporting or decisions about specific organizations.

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Cleaning & Transformation**
* **Data Visualization**
* **Business Intelligence**
* **Exploratory Data Analysis**

## 🔄 Project Workflow

```text
Raw Internship Listing Data
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX Measures / Calculations
        ↓
KPI Development
        ↓
Interactive Visualizations
        ↓
Internship Scam Analytics Dashboard
```

## 🧹 Data Preparation

The internship listing dataset can be prepared using **Power Query** before creating the dashboard.

Typical preparation steps include:

* Removing unnecessary fields
* Handling missing values
* Correcting data types
* Standardizing city, domain, company, and internship attributes
* Grouping stipend values into meaningful ranges
* Preparing duration and website-age fields for filtering
* Validating genuine/scam classifications and scam-report counts
* Creating calculated columns or measures where required

## 🧮 Key Metrics

The project focuses on metrics such as:

```text
Total Listings
Genuine Listings
Scam Listings
Average Stipend
Scam Reports
Scam Listings by City
Scam Listings by Domain
Stipend Distribution
Placement Promise Analysis
Remote Work Analysis
Company Scam Reports
```

## 📂 Repository Structure

```text
Internship-Scam-Analytics-Dashboard/
│
├── 📊 Internship_Scam_Analytics_Dashboard.pbix
├── 📁 Dataset/
│   └── internship_scam_data.csv
├── 🖼️ Dashboard/
│   └── internship_scam_analytics_dashboard.png
└── 📄 README.md
```

> Update the file names above if your actual repository uses different names.

## 🚀 How to Use

1. Clone or download this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open the `.pbix` project file.
4. If required, update the dataset path in Power Query.
5. Click **Refresh** to load the latest data.
6. Use the **Domain, City, Duration in Months, and Website Age in Years** filters.
7. Interact with the KPI cards and visuals to perform deeper internship scam analysis.

## 📚 Skills Demonstrated

`Power BI` · `Data Analytics` · `Power Query` · `DAX` · `Data Modeling` · `KPI Analysis` · `Scam Detection` · `Risk Analysis` · `Data Visualization` · `Business Intelligence` · `Exploratory Data Analysis` · `Dashboard Design`

## 👨‍💻 Author

**Abhishek Tyagi**
MCA | Aspiring Data Scientist | Data Analytics Enthusiast

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ **Star** and sharing your feedback.

---

### 🏷️ Tags

`Power BI` `Internship Scam` `Scam Analytics` `Fraud Detection` `Risk Analysis` `Data Analytics` `Business Intelligence` `DAX` `Power Query` `Dashboard` `Data Visualization` `KPI Dashboard` `Internship Analysis` `Data Analyst` `Data Science`

