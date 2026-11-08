# WaveX – Sales \& HR Dashboard (Power BI)

An interactive two-page Power BI report that gives management a quick view of sales performance and workforce structure for a fictional company, **WaveX**.

> Note: This is a personal portfolio project built on a self-created, hypothetical dataset. All figures are fictional.

**▶** [**View the report as PDF**](WaveX_Dashboard.pdf) · **🎥** [**60-second walkthrough**](LINK-TO-VIDEO)

\---

## Preview

|Sales Overview|HR Overview|
|-|-|
|!\[Sales page](screenshots/sales.png)|!\[HR page](screenshots/hr.png)|

\---

## Business questions answered

**Sales**

* How much revenue, volume and profit are we generating?
* Which product categories and distributors drive sales, and at what production cost?
* How is revenue trending over time, and how does it compare year-over-year?
* Which countries and payment methods contribute most?

**HR**

* How large is the workforce, and how is it split by gender, department and education?
* How satisfied are employees, and does satisfaction change with years of service?
* How many employees are up for promotion?
* What share of employees live far from the workplace?

\---

## Report pages

### 1\. Sales

* **KPI cards:** Total Sales ($), Quantity Sold, Total Profit
* **Sales by Category:** bar chart
* **Sales vs. Production Cost by Distributor:** clustered column chart
* **Sales Trend:** line chart with Year → Quarter → Month → Day drill-down
* **Year-over-Year Growth (%):** column chart with the same drill-down
* **Sales by Country:** map
* **Sales by Payment Method:** donut chart
* **Year slicer:** filters the whole page

### 2\. HR

* **KPI cards:** Total Employees, % of Employees Living Far
* **Gender split:** pie chart
* **Average Job Satisfaction:** gauge
* **Satisfaction by Years of Service:** matrix
* **Employees by Education:** waterfall chart
* **Promotion Pipeline:** funnel chart
* **Department overview:** area chart
* **Q\&A visual:** ask questions in plain English (e.g. "employees by department")

Navigation buttons let users switch between the two pages.

\---

## Data model

|Table|Content|
|-|-|
|`Sales`|Transactions: date, sales ($), quantity, production cost, payment method|
|`Category`|Product category lookup|
|`Distributor`|Distributor name and country|
|`HR`|Employee records: department, gender, age, education, years in service, job satisfaction, promotion status, distance from work|

**Key DAX measures:** Total Profit · Sales YoY % · Total Employees · Average Job Satisfaction · % Distance Far

\---

## Skills demonstrated

* Data modelling and table relationships
* DAX measures, including time intelligence (YoY %)
* Date hierarchies with drill-down
* Interactive design: slicers, cross-filtering, page navigation buttons
* Turning raw data into clear, decision-ready visuals

## Author

**Pritam Mohanty** · M.A. International Management, TH Aschaffenburg
· [Email](mailto:pritammohanty88007@gmail.com)

