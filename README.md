# Hi, I'm Ashutosh Jayant

MCA student exploring data analytics and public policy. My background is in
Commerce, Political Science, and Economics, and I work on Python-based projects that
use real-world datasets — Government of India documents like budgets, economic
surveys and statistical handbooks, as well as global development data from the UN,
World Bank and other sources.

The aim is to combine domain knowledge in economics and policy with programming
skills, and to produce analytical work that is reproducible and honestly documented.

## Skills

* Languages: Python, SQL
* Data analysis: Pandas, NumPy, Matplotlib, Seaborn
* Statistics: correlation, regression, hypothesis testing, clustering (scikit-learn)
* Database: SQLite (schema design, indexes, CTEs, window functions, aggregations)
* PDF extraction: pdfplumber, PyMuPDF, Regex
* Tools: Jupyter Notebook, VS Code, Git, GitHub, Excel
* Methods: ETL pipeline design, data validation, index construction, sensitivity
  analysis, text analysis, data visualisation

## Featured Projects

### India State Competitiveness Index (ISCI) — Porter's Diamond Analysis

A competitiveness index for India's states and union territories, built entirely from
official Government of India data (the RBI Handbook of Statistics on Indian States and
the MSME Annual Report) and structured around Michael Porter's Diamond framework.
Version 1.0 builds and validates the index; Version 2.0 explains it through analysis,
interpretation and simulation.

* End-to-end pipeline across 15 notebooks: PDF extraction (a 472-page handbook) →
  cleaning and feature engineering → index construction → validation → analysis →
  reporting
* 11 indicators mapped to two of Porter's four determinants; the other two are
  documented as limitations rather than guessed
* Min-Max normalization, equal weights and an 8-of-11 coverage rule, tested with a
  sensitivity analysis (Spearman correlation 0.99+ across three checks)
* KMeans clustering into three state types, followed by gap analysis, evidence-based
  development priorities, and "what-if" scenario simulations
* Keeps evidence separate from interpretation, and priority areas separate from policy
  prescriptions
* A written limitations section, plus a thesis, research-decisions and project-philosophy
  document

Repo: [india-state-competitiveness-index](https://github.com/jayantashutosh-rgb/india-state-competitiveness-index)

### Beyond GDP — Human Development and Capability Analysis

A cross-country study asking whether GDP alone explains human development, or whether
health, education, freedom, social support and governance matter as much. The project
merges four global sources (UNDP, World Bank, World Happiness Report, Transparency
International) into one dataset for 130 countries and tests the question with SQL,
statistics, clustering and an experimental capability index inspired by Amartya Sen.

* End-to-end pipeline: cleaning and merging four sources → SQLite database → SQL
  analysis → EDA → statistics → clustering → capability index
* Regression showing GDP is not a significant predictor of HDI once happiness and
  governance are included
* KMeans clustering of countries into development groups (validated with elbow and
  silhouette methods)
* An experimental capability index (built without income) that correlates 0.94 with
  HDI and 0.86 with happiness, but only 0.67 with GDP
* A written limitations section

Repo: [beyond-gdp-capability-analysis](https://github.com/jayantashutosh-rgb/beyond-gdp-capability-analysis)

### Indian Economic Survey 2025-26 — Capability Approach Analysis

A text analysis of the Indian Economic Survey 2025-26 (Government of India, Ministry
of Finance) that asks a narrow question: when a 740-page government document talks
about development, whose vocabulary does it use?

The project builds a SQLite database from the PDF, runs SQL and Python analysis on
the text, and documents what it finds. What is in the project:

* End-to-end pipeline: PDF extraction → cleaning → SQLite database (17 chapters, 676
  pages, 252,587 words) → SQL queries → Python deep dives → charts
* Six SQL analytical queries using CTEs, aggregations, and the LENGTH/REPLACE
  substring-counting pattern for keyword density
* Two rounds of manual classification (66 + 44 entries) with the full context windows
  committed for review
* Six charts built with matplotlib and seaborn
* Findings and methodology kept in separate documents so claims and methods can be
  reviewed independently
* A written limitations section

Repo: [economic-survey-capability-analysis](https://github.com/jayantashutosh-rgb/economic-survey-capability-analysis)

### India Union Budget 2026-27 — Capability Approach Analysis

A research-oriented analysis of India's Union Budget 2026-27 viewed through Amartya
Sen's Capability Approach. The project extracts ministry-level expenditure data from
official Government of India PDFs, validates it against the published Grand Total, and
classifies 102 ministries into capability domains (health, education, nutrition,
social protection, economic opportunity).

A few things this project does that most budget summaries don't:

* Reconciles the extracted dataset against the official Grand Total (residual
  variance: Rs 0.19 crore against a base of Rs 53.47 lakh crore)
* Documents contested classifications openly rather than hiding judgement calls
* Separates descriptive findings from causal claims
* Includes a written limitations section

Repo: [india-union-budget-capability-analysis](https://github.com/jayantashutosh-rgb/india-union-budget-capability-analysis)

## Other Projects

### Python Data Analysis Toolkit

Practical exercises using Pandas, NumPy, and Matplotlib — array manipulation,
structured-data operations, statistical summaries, and visualisation patterns. Built
as foundation work before moving to real public datasets.

### Python Programming Fundamentals

Core Python concepts including data types, functions, file handling, and exception
handling. Foundation for the data analysis work above.

## Background

* Master of Computer Applications (MCA), Mangalayatan University, Aligarh (2025 – Present)
* M.A. Economics, Swami Vivekanand Subharti University (Completed 2026)
* M.A. Political Science, IGNOU (Completed 2022)
* Bachelor of Commerce, Delhi College of Arts & Commerce, University of Delhi (2015)

Extended UPSC Civil Services preparation, which built sustained engagement with
economics, public policy, and government data interpretation.

## Contact

[LinkedIn](https://www.linkedin.com/in/ashutosh-jayant-954a54a0/) · jayantashutosh@gmail.com
