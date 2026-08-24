## Hi there 👋 my name is Paula Kalenczuk

Data analyst and polymer chemist. I work on different types of data: measurements from laboratories and production such as spectra and process parameters, market and provision data in diagnostics and healthcare.

Dresden, Germany · M.Sc. Polymer Chemistry · four years as a research assistant at TU Dresden, Chair of Microsystems Engineering

### What I bring

- **Merging and cleaning data** - Python (numpy, pandas), XML and CSV, bulk loading into PostgreSQL and BigQuery, REST APIs
- **Modelling** - fact, dimension and bridge tables, primary and foreign keys, star schemas, dbt
- **Analysis** - regression, PCA, PLS, outlier diagnostics, model validation
- **Reporting** - Qlik Sense, Excel, PowerPoint

### Tools

Python (pandas, scikit-learn, scipy, numpy, matplotlib) · SQL (PostgreSQL, BigQuery) · dbt · Qlik Sense · Excel including VBA · MATLAB · Git · Docker

### Projects

**[NIR chemometrics: active-ingredient content in tablets](https://github.com/paula020300/NIR_tablet_assay_modelling)**

*Description:* an analysis of measurements from 655 pharmaceutical tablets. Each tablet was analysed with near-infrared spectroscopy, and the drug content was predicted from that near-infrared measurement.

*Goal:* find out how precisely the active-ingredient content of a tablet can be predicted solely from its near-infrared spectrum, and whether this chemometric model is good enough to sort tablets into in-spec and out-of-spec.

*Steps:* preprocessing, exploratory analysis, outlier diagnostics, model selection, validation.

*Result:* a successful quality-control model. It predicts the active-ingredient content of an unknown tablet (test RMSE 4.35 mg), reduces the prediction error by 73% against the mean baseline, and reliably separates tablets that meet the pre-defined specification from those that do not.

*Python, scikit-learn, chemotools, scipy, Git*

**[Data jobs: market analysis](https://github.com/paula020300/sql_project_data_jobs)**

*Description:* a SQL analysis of a 2023 job-postings dataset, loaded into a local PostgreSQL database as four related tables, roughly 2.7 million rows, five queries addressing different aspects, with the charts generated in Python.

*Goal:* analyse the data by answering five questions about data analyst postings. Which postings pay the most; which skills those postings ask for; which skills appear most often; which skills have the highest average salary; and which skills are both frequent and well paid.

*Steps:* database and table setup, bulk loading from CSV, five queries, chart generation, write-up with limitations.

*Result:* there is a discrepancy between demand and pay. SQL appears in 92,628 postings, more than any other skill, and its salary average of $96,435 is located below all 25 of the best-paid skills. Only 14 skills pass both filters: a minimum of 100 postings and a minimum average salary of $100,000. The best-paid skills are data engineering tools rather than analysis tools: Kafka, Airflow, Spark, Snowflake, Databricks.

*PostgreSQL, pgAdmin, VS Code with SQLTools, Python (pandas, matplotlib), Git*

### Currently working on

advanced SQL · dbt and data warehousing · Power BI

<!--
**paula020300/paula020300** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
