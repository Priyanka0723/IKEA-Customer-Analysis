IKEA Customer Analytics Dashboard
A beginner-friendly data analytics project that explores customer
behavior, revenue, and customer churn using an IKEA-themed Power BI
dashboard.

The main goal is simple: help a business understand its customers so
it can make better decisions.
Note: This is a portfolio analytics project. The IKEA name and visual
style are used to present the dashboard; this project should not be
understood as an official IKEA report.

1. What is this project about?
Imagine a shop has thousands of customers. Some customers buy often,
some buy only once, and some stop buying completely.

A business needs answers to questions such as:
- How many customers do we have?
- How much revenue do customers generate?
- Which customer groups are the largest?
- How many customers have stopped purchasing?
- Which countries have high customer value?
- How does customer activity or churn change over time?
- Which customers should the business try to keep?
This dashboard puts important information into charts, summary cards,
filters, and a customer analysis table. Instead of checking many rows of
data one by one, a user can explore the information visually.
2. Why did I build it?
I built this project to practise turning sales and customer data into
useful business information.

Raw data is like a large notebook full of transactions. It can be
difficult to understand by looking at every row. Data analysis helps
organise that information and find patterns.

This project demonstrates how a Data Analyst can: - organise and analyse
customer data; - measure revenue and customer behaviour; - group
customers by their purchasing patterns; - compare results by time,
country, and customer segment; - present findings in an interactive
dashboard.
3. Tools used
Update this list if your final workflow used different tools.
- Power BI --- to build the interactive dashboard and charts.
- SQL --- to query and analyse structured data, if used in the
  final workflow.
- Python (Pandas) --- to clean, prepare, or analyse data, if used
  in the final workflow.
- Excel --- to inspect or prepare data, if used in the final
  workflow.
The screenshots show the final Power BI dashboard. The tools above
describe the wider project workflow; keep only the tools you personally
used.
4. How I did the project
Here is the process in simple steps.
Step 1: Understand the data
I started with customer and transaction data. A transaction is a record
of a purchase. When many transactions are combined, they can help
explain what customers buy and how much they spend.
Step 2: Prepare the data
Before analysing data, it is important to check for issues such as
missing values, incorrect data types, duplicate records, or values that
do not make sense.

Clean data helps make the results more reliable. The exact cleaning
steps depend on the source data and the workflow used.
Step 3: Analyse the business questions
I focused on customer count, revenue, customer segments, churn, and
customer value. I also compared customer behaviour across months,
quarters, years, and countries.
Step 4: Create the Power BI report
I arranged the results into three pages: 1. Home 2. Business Overview 3.
RFM Analysis

I used summary cards, bar charts, line charts, a table, slicers, and
navigation controls so a viewer can explore the report.
Step 5: Make the report interactive
The report includes filters for Month, Quarter, Year, Country, Segment,
and IsChurned. These help the viewer focus on a particular part of the
data.

The navigation cards on the Home page lead to the Business Overview and
RFM Analysis pages. The Clear all slicers control is intended to reset
the report filters.
5. The three dashboard pages
Page 1 --- Home
The Home page is the starting point of the report.

It contains: - a Business Overview card to open the main business
dashboard; - an RFM Analysis card to explore customer groups; - a
Key Metrics Glossary explaining important terms.

The glossary explains: - Churned % --- the percentage of customers
who have stopped purchasing, according to the project's churn
definition. - Recency (R) --- how recently a customer purchased. -
Frequency (F) --- how often a customer purchased. - Monetary (M)
--- how much a customer spent. - Customer Value --- a measure of the
revenue generated per customer, as defined in the report.
Page 2 --- Business Overview
This page gives a high-level view of the business.

Summary cards shown in the screenshot: - Total Customers:
5,881 - Total Revenue: $17M - Churned: 50.9% - Average
Customer Value: 2,954

These figures reflect the displayed report and may change when filters
are applied.

Charts included: - Total Customers by Segment - Customer
Relationship by Segment, split by churn status - Total Customers by
Month - Total Customers by Quarter - Total Customers by Year

Why this page is useful

A business user can compare customer groups, look for changes over time,
and examine how churn is distributed across segments. For example, the
screenshot shows that Lost is the largest displayed segment,
followed by Loyal and Champions. That can help the analyst ask
follow-up questions about why customers are classified in each group and
what actions may be appropriate.
Page 3 --- RFM Analysis
RFM stands for Recency, Frequency, and Monetary value. It is a
common way to understand customer purchasing behaviour.

Think of three simple questions:
- Recency: How recently did this customer buy something?
- Frequency: How often does this customer buy?
- Monetary: How much does this customer spend?
The report includes: - a country-level table with customer count,
revenue, and average R, F, and M scores; - a chart showing the top five
countries by average customer value; - churn percentage by month; -
churn percentage by quarter; - churn percentage by year; - a
Segment/Country switch and the shared filters.

Why this page is useful

It helps compare customers and countries in more detail. A business can
use this type of analysis to investigate loyal customers, identify
customers who may need attention, and decide where further analysis is
needed.

RFM scores are indicators of purchasing behaviour; they do not, by
themselves, explain why a customer bought or stopped buying.
6. Key terms in very simple English
  Term                                Simple meaning
  Customer                            A person or business that buys
                                      something

  Revenue                             Money earned from sales

  Segment                             A group of customers with similar
                                      behaviour

  Churn                               When a customer stops purchasing,
                                      according to the project's
                                      definition

  Recency                             How long ago the customer last
                                      purchased

  Frequency                           How often the customer purchases

  Monetary value                      How much the customer spends

  Slicer                              A filter that lets the viewer
                                      choose which data to see

  Dashboard                           A visual summary of important
                                      information

  KPI                                 A key number used to monitor
                                  business performance
7. Example questions this dashboard can help answer
- Which customer segment has the most customers?
- How does customer count change from month to month?
- How does churn change across months, quarters, and years?
- How do customer scores compare across countries?
- Which countries appear at the top of the customer-value chart?
- What happens to the dashboard when I filter by year, country, or
  segment?
The dashboard helps reveal patterns. Additional investigation is needed
before treating a pattern as the cause of a business problem.
8. Main takeaways from the screenshots
These are observations from the dashboard as shown, not proof of the
reasons behind the patterns:
- The Business Overview page displays 5,881 customers and $17M
  total revenue before any additional filter selections.
- The displayed churn KPI is 50.9%.
- The Lost segment has the largest customer count in the segment
  chart.
- The quarterly customer chart rises from Q1 to Q4 in the displayed
  view.
- The RFM page shows differences in average R, F, and M scores across
  countries.
- The churn charts show that churn varies over time, so it is useful
  to examine the period and filters before drawing conclusions.
9. How to explore the report
1. Open the Power BI report.
2. Start on the Home page.
3. Select Business Overview or RFM Analysis.
4. Use the Month, Quarter, Year, Country, Segment, and IsChurned
   filters to narrow the results.
5. Compare the cards, charts, and table.
6. Use Clear all slicers to return to the unfiltered view, if the
   button is configured for that action.
7. Use the back arrow or page navigation to return to the previous
   page, if configured.
Files to add to this GitHub repository
A suggested repository structure is:
IKEA-Customer-Analytics/
├── README.md
├── IKEA_Customer_Analytics.pbix
├── screenshots/
│   ├── home.png
│   ├── business-overview.png
│   └── rfm-analysis.png
└── data/
    └── README.md
Use your actual file names. Add the .pbix file if you are able to
share it, and only include data files that you are permitted to publish.
If the dataset has licensing or privacy restrictions, link to the
original source instead of uploading it.

Once the screenshots are uploaded to the screenshots/ folder, you can
display them in this README with:
## Dashboard screenshots

### Home
![Home page](screenshots/home.png)

### Business Overview
![Business Overview page](screenshots/business-overview.png)

### RFM Analysis
![RFM Analysis page](screenshots/rfm-analysis.png)
10. Skills demonstrated
This project can demonstrate skills such as: - data analysis and
business-question framing; - customer and revenue KPI reporting; -
customer segmentation and RFM concepts; - time-based and country-based
comparisons; - dashboard design and data visualisation; - report
navigation and interactive filtering; - explaining analytical results in
business-friendly language.

Only list SQL, Python, Excel, or other tools as hands-on skills if you
used them yourself in this project.
11. Final note
This project is a practice exercise in using data to understand customer
behaviour and business performance. The dashboard helps turn rows of
sales data into information that people can explore and discuss.

The main lesson: a Data Analyst does more than create charts. They
use data to answer questions, explain patterns, and help people make
better decisions.
