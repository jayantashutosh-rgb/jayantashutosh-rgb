# Hi, I'm Ashutosh Jayant

MCA student exploring data analytics and public policy. My background is in Commerce, Political Science, and Economics, and I'm building Python-based projects that work with real Government of India datasets — budget documents, economic surveys, election data.

The goal is to combine domain knowledge in economics and policy with programming skills, and to produce analytical work that is reproducible and honestly documented.

## Skills

- **Languages:** Python, SQL
- **Data analysis:** Pandas, NumPy, Matplotlib, Seaborn
- **Database:** SQLite (schema design, indexes, CTEs, aggregations)
- **PDF extraction:** pdfplumber, PyMuPDF, Regex
- **Tools:** Jupyter Notebook, VS Code, Git, GitHub, Excel
- **Methods:** ETL pipeline design, data validation, exploratory analysis, text analysis, data visualisation

## Featured Projects

### Indian Economic Survey 2025-26 — Capability Approach Analysis

A text analysis of the Indian Economic Survey 2025-26 (Government of India, Ministry of Finance) that asks a narrow question: when a 740-page government document talks about development, whose vocabulary does it use?

The project builds a SQLite database from the PDF, runs SQL and Python analysis on the text, and documents what it finds. Key features:

- End-to-end pipeline: PDF extraction → cleaning → relational database (17 chapters, 676 pages, 252,587 words) → SQL queries → Python deep dives → visualizations
- Six SQL analytical queries (CTEs, aggregations, density calculations)
- Two rounds of manual qualitative classification (66 + 44 entries) with audit trail
- Six matplotlib/seaborn charts
- Findings documented separately from methodology so claims and methods can be reviewed independently
- A written limitations section

Repo: [economic-survey-capability-analysis](https://github.com/jayantashutosh-rgb/economic-survey-capability-analysis)

### India Union Budget — Capability Approach Analysis (2026)

A research-oriented analysis of India's Union Budget 2026-27 viewed through Amartya Sen's Capability Approach. Built a reproducible Python pipeline that extracts ministry-level expenditure data from official Government of India PDFs, validates it against the published Grand Total, and classifies 102 ministries into capability domains (health, education, nutrition, social protection, economic opportunity).

Key things this project does that most budget analyses don't:

- Reconciles the extracted dataset against the official Grand Total (residual variance: Rs 0.19 crore against a base of Rs 53.47 lakh crore)
- Documents contested classifications openly rather than hiding judgement calls
- Separates descriptive findings from causal claims
- Includes a written limitations section

Repo: [india-union-budget-capability-analysis](https://github.com/jayantashutosh-rgb/india-union-budget-capability-analysis)

## Other Projects

### Python Data Analysis Toolkit

Practical exercises using Pandas, NumPy, and Matplotlib — array manipulation, structured-data operations, statistical summaries, and visualisation patterns. Built as foundation work before moving to real public datasets.

### Python Programming Fundamentals

Core Python concepts including data types, functions, file handling, and exception handling. Foundation for the data analysis work above.

## Background

- **Master of Computer Applications (MCA),** Mangalayatan University, Aligarh (2025 – Present)
- **M.A. Economics,** Swami Vivekanand Subharti University (Completed 2026)
- **M.A. Political Science,** IGNOU (Completed 2022)
- **Bachelor of Commerce,** Delhi College of Arts & Commerce, University of Delhi (2016)

Extended UPSC Civil Services preparation, which built sustained engagement with economics, public policy, and government data interpretation.

## Contact

[LinkedIn](https://www.linkedin.com/in/ashutosh-jayant-954a54a0/) · jayantashutosh@gmail.com
