# Coursera_IBM_DataAnalyst_Note
Project Overview
This repository showcases the end-to-end data analysis workflow completed as part of the IBM Data Analyst Professional Certificate. The project focuses on analyzing the market value of programming languages by correlating average annual salaries with job demand.

As a Product Manager, the goal of this project was not only to process data but to derive actionable insights that could guide strategic investments in talent development and technology stacks.

# 🚀 Analysis Workflow
## 1. Data Collection (Web Scraping & API)
Technical Implementation: Utilized Requests and BeautifulSoup to scrape structured data from HTML tables and integrated external data via REST APIs.

Business Rationale: Automated the gathering of primary market data to ensure real-time accuracy, eliminating the need for manual research.

PM Perspective: This skill is vital for Competitive Intelligence. It allows a PM to monitor competitor pricing, feature releases, or market shifts automatically without relying on third-party reports.


## 2. Data Wrangling (Cleaning & Preparation)
Technical Implementation: Performed data auditing using Pandas. Handled missing values (dropna), removed duplicates, and normalized data types (e.g., converting currency strings like "$120,000" into floats for calculation).

Business Rationale: Ensures the "Sanity" of the data. Reliable decisions cannot be made on "noisy" or "dirty" data (Garbage In, Garbage Out).

PM Perspective: Essential when merging disparate datasets from different global regions or CRM systems to create a "Single Source of Truth."


## 3. Exploratory Data Analysis (EDA)
*Technical Implementation: Leveraged SQL for complex querying and Pandas group-by operations to identify trends, outliers, and correlations between language popularity and compensation.

*Business Rationale: Uncovering hidden patterns to validate or pivot business hypotheses.

*PM Perspective: Used to identify the ROI of specific segments. For a PM, this translates to knowing exactly where to allocate resources for the highest impact.


## 4. Data Visualization
*Technical Implementation: Developed high-impact visual stories using Matplotlib and Seaborn. Focused on sorted bar charts and distribution plots to ensure clarity.

*Business Rationale: Data is only as good as the story it tells. Visuals are used to drive consensus among stakeholders.

*PM Perspective: A critical tool for Executive Communication. This enables me to persuade leadership teams at headquarters by presenting complex market trends in an intuitive, 3-second summary.


## 5. Interactive Dashboard (Plotly Dash / Power BI)
Technical Implementation: Built a dynamic, web-based dashboard using Dash. Implemented callback functions to allow users to filter data by year or region interactively.

Business Rationale: Transitions from static reporting to Self-Service Analytics, empowering local teams to explore data relevant to their specific needs.

PM Perspective: Scales the data-driven culture within the organization. By automating the reporting layer, I can focus more time on Product Strategy rather than manual data updates.

