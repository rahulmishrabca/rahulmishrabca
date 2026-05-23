<div align="center">

# Hi, I'm Rahul Kumar 👋

### Senior Analytics & Decision Science Leader | FinTech & Lending | 11+ Years

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rkmisraofcl-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rkmisraofcl)
[![GitHub](https://img.shields.io/badge/GitHub-rahulmishrabca-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulmishrabca)
[![Email](https://img.shields.io/badge/Email-rahul.mishrabca%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahul.mishrabca@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=rahulmishrabca&style=for-the-badge&color=1A5276&label=PROFILE+VIEWS)](https://github.com/rahulmishrabca)

</div>

---

## 🎯 What I Do — And The Business Impact

I turn raw lending data into decisions that move the needle. My work sits at the intersection of **credit risk, product funnels, and AI-powered analytics** — with direct ownership of P&L outcomes.

| Metric | Result |
|---|---|
| 📈 Postpaid Monthly Business Scaled | **₹224 Cr/month (EBITDA+)** |
| 💳 Merchant Loan Disbursements | **₹2,000+ Cr/month** |
| 🚀 Incremental Business Driven | **₹1,800 Cr** |
| 🔄 Loan Conversion Improvement | **13.5× (0.02% → 0.27%)** |
| 📉 Low-quality Lead Elimination | **~80% reduction** |
| 👥 Funnel Sign-up Uplift | **~30% increase** |

---

## 📊 Impact-First Project Grid

### 🔹 [SQL Analytics Projects](https://github.com/rahulmishrabca/sql-analytics-projects)

| | Details |
|---|---|
| **Business Problem** | Identify drop-off points in the BNPL "Lead-to-Activation" journey across product variants (Delite, Lite, Mini) |
| **Technical Solution** | Trino SQL on Hive — stage-wise funnel queries, month-on-month pivot comparisons, 7-day rolling rejection rate anomaly detection |
| **Key Result** | Identified bureau pull failure spike (4% → 41%) within 6 days; fix recovered ~380 lost accounts worth ₹1.9 Cr |
| **Techniques Used** | CTEs, Window Functions (`LAG`, `AVG OVER`), `DATE_FORMAT` for Trino, Conditional Aggregation Pivots |

---

### 🔹 [PySpark Data Engineering](https://github.com/rahulmishrabca/pyspark-data-engineering)

| | Details |
|---|---|
| **Business Problem** | Process 8GB+ daily lending datasets across 4 product lines on AWS EMR without executor OOM failures |
| **Technical Solution** | Optimized PySpark pipelines with predicate pushdown, repartition tuning, HDFS staging before S3 write, chunk-based processing |
| **Key Result** | Eliminated Exit Code 137 OOM failures; enabled near real-time performance dashboards for finance and leadership |
| **Techniques Used** | Coalesce/Repartition strategies, Snappy compression, AWS Glue ingestion, S3 partitioned Parquet exports |

---

### 🔹 [Data Storytelling](https://github.com/rahulmishrabca/data-storytelling)

| | Details |
|---|---|
| **Business Problem** | Postpaid conversion dropped ~50% week-on-week — was it a credit quality issue or a system failure? |
| **Technical Solution** | Stage-wise rejection reason breakdown in Trino SQL, timeline correlation with backend change logs |
| **Key Result** | Root cause identified as bureau API timeout config change (not user quality) — resolved in 24 hours after rollback |
| **Techniques Used** | Structured root cause analysis, rolling baseline anomaly detection, business impact sizing |

---

### 🔹 [Analytics Dashboards & Reports](https://github.com/rahulmishrabca/analytics-dashboards)

| | Details |
|---|---|
| **Business Problem** | Finance and product teams needed a single monthly view of funnel health across all BNPL product variants |
| **Technical Solution** | Monthly structured report — lead volume, conversion rate, rejection rate, stage drop-off, anomaly flags, recommendations |
| **Key Result** | Standardized reporting reduced ad-hoc data requests by enabling self-serve stakeholder reviews |
| **Techniques Used** | Multi-dimensional pivot analysis, MoM delta calculations, anomaly flagging, executive-level narrative writing |

---

## 🛠️ Technical Skills — By Use Case

### 🔧 Data Engineering
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![AWS EMR](https://img.shields.io/badge/AWS_EMR-FF9900?style=flat&logo=amazonaws&logoColor=white)
![AWS Glue](https://img.shields.io/badge/AWS_Glue-FF9900?style=flat&logo=amazonaws&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat&logo=amazons3&logoColor=white)
![HDFS](https://img.shields.io/badge/HDFS-66CCFF?style=flat&logo=apachehadoop&logoColor=black)

`PySpark (Optimization, Partitioning)` · `HiveQL (Partitioned Tables)` · `AWS EMR` · `AWS Glue (NoSQL ingestion)` · `Parquet / Snappy`

### 🔍 Query & Exploration
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat&logo=trino&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)

`Trino on Hive` · `Window Functions (LAG, LEAD, AVG OVER)` · `CTEs` · `Conditional Aggregation Pivots` · `BigQuery`

### 🤖 AI & Automation
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Pro-CC785C?style=flat&logoColor=white)

`LLM Pipelines (Claude Pro, Gemini Pro)` · `Agentic AI orchestration` · `Automated Slack alerting` · `GenAI for analytics productivity`

### 📊 Business Intelligence
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=flat&logo=looker&logoColor=white)

`Funnel Analytics` · `Lead Scoring Models` · `Cohort Analysis` · `A/B Testing` · `Portfolio Monitoring` · `KPI Design`

---

## 🏗️ Data Pipeline Architecture

```
Raw Data Sources              Processing Layer           Output Layer
─────────────────             ────────────────           ────────────
NoSQL (Paytm App)  ──┐
                      ├──► AWS Glue ──► Hive/S3 ──► Trino SQL ──► Dashboards
Lending Events     ──┘                                           (Power BI /
                                                                  Tableau)
                      ┌──► AWS EMR (PySpark)
                      │     ├── Predicate Pushdown
Daily Snapshots    ───┤     ├── Repartition (600 partitions)
(lead_history_     │     ├── HDFS Staging
snapshot_v3)       │     └── S3 Parquet Export
                      │
                      └──► Trino on Hive ──► Funnel Reports
                                          ──► Anomaly Alerts (Slack)
                                          ──► Finance Validation
```

---

## 📈 GitHub Activity

<div align="center">

![Commits](https://img.shields.io/badge/Total_Commits-35+-1A5276?style=for-the-badge&logo=git&logoColor=white)
![Repos](https://img.shields.io/badge/Public_Repos-5-2471A3?style=for-the-badge&logo=github&logoColor=white)
![Profile Views](https://komarev.com/ghpvc/?username=rahulmishrabca&style=for-the-badge&color=0B1F3A&label=PROFILE+VIEWS)

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=rahulmishrabca&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://github.com/rahulmishrabca)

<br/>

[![Rahul's GitHub Stats](https://github-readme-stats.vercel.app/api?username=rahulmishrabca&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github)](https://github.com/rahulmishrabca)
&nbsp;
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rahulmishrabca&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)](https://github.com/rahulmishrabca)

</div>

---

## 🧠 Decision Science Focus Areas

```
Credit & Risk Analytics    ████████████████████  Expert
Funnel Optimization        ████████████████████  Expert
A/B Testing & Pricing      ████████████████░░░░  Advanced
Portfolio Monitoring       ████████████████████  Expert
LLM / Agentic AI           ██████████████░░░░░░  Advanced
PySpark / Data Eng.        ████████████░░░░░░░░  Proficient
```

---

## 💼 Career Timeline

```
2014 ──► Associate, Catalog Team (SQL + Excel, 8-member team)
2016 ──► Junior Manager, Growth Analytics (5-member team, KPI dashboards)
2019 ──► Asst. Manager, Offline Analytics (EDC POS, merchant analytics)
2022 ──► Deputy Manager, Lending Analytics (₹2,000 Cr portfolio)
2023 ──► Manager, Lending Analytics (₹3,000 Cr portfolio, funnel optimization)
2024 ──► Executive Manager (13.5x loan conversion improvement)
2025 ──► Senior Manager (₹224 Cr postpaid, AI orchestration, Micro Loans launch)
```

---

## 🏆 Recognition

> 🏅 **Legends Award** &nbsp;|&nbsp; ⭐ **Rock Star** (Multiple Years) &nbsp;|&nbsp; 🥇 **Leader Board Reward** &nbsp;|&nbsp; 🌟 **Hall of Fame**

---

## 📫 Let's Connect

<div align="center">

| Platform | Link |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/rkmisraofcl](https://linkedin.com/in/rkmisraofcl) |
| 🐙 GitHub | [github.com/rahulmishrabca](https://github.com/rahulmishrabca) |
| 📧 Email | rahul.mishrabca@gmail.com |
| 📍 Location | India |

*"Without data, you're just another person with an opinion."*

</div>
