India Job Market Intelligence & Skill Analysis
A professional-grade data analytics project analyzing 32,438 tech job postings from India's largest job portal (Naukri.com) to uncover hiring trends, skill demand, salary intelligence, and fresher opportunity insights for India's technology sector in 2025-26.

📊 Project Overview
India's tech hiring ecosystem lacks a centralized, data-driven intelligence layer connecting real-time skill demand signals with salary benchmarks, geographic talent distribution, and fresher employability metrics. This platform transforms raw job market data into actionable intelligence for both hiring managers and fresh graduates.

Dataset: Naukri.com India Job Market 2025-26 (Kaggle)
Raw Records: 97,929 job postings
Tech Records: 32,438 (after classification)
Skill Mentions: 241,109 across 18,702 unique skills
Companies: 6,482
Cities: 428

🔑 Top 10 Findings
#	Finding	Key Number
1	Python leads India's tech skill demand	15.3% of all postings
2	Only 1 in 5 tech roles is fresher-eligible	20.21% (6,556 postings)
3	Hyderabad & Bengaluru offer statistically equal salaries	p = 0.474
4	Senior tech roles pay 4.2x more than junior roles	₹25 vs ₹5.9 LPA
5	Generative AI commands highest salary premium	+150% above median
6	Accenture is India's largest fresher employer	1,088 fresher postings
7	Tech hiring drops 97% on weekends	157 vs 5,712 peak day
8	Spring Boot + Microservices is India's tightest skill pair	Jaccard 0.41
9	Skill count has no significant salary correlation	r = 0.020, p = 0.109
10	No Indian city achieves Top-Tier FOI score	Best: Bengaluru = 56.5/100

🗺️ Fresher Opportunity Index (FOI)
The FOI is an original composite metric developed for this project that ranks Indian cities for fresh graduate tech opportunities:

FOI = Entry-level ratio (40%)

Salary competitiveness (30%)
Market depth (20%)
Work flexibility (10%)
Rank	City	FOI Score	Tech Jobs	Fresher %	Median Salary
🥇 1	Bengaluru	56.5	9,358	17%	₹13.2 LPA
🥇 1	Hyderabad	56.5	5,502	14%	₹13.5 LPA
🥉 3	Mohali	49.6	122	47%	₹6.5 LPA
4	Gurugram	49.5	1,319	24%	₹10.5 LPA
5	Thane	48.5	148	44%	₹6.6 LPA

🛠️ Tech Stack
Layer	Tools Used
Data Collection	Kaggle (Naukri.com scrape)
Data Cleaning	Python, Pandas, NumPy, Regex
Exploratory Analysis	Pandas, Matplotlib, Seaborn, Plotly
Statistical Analysis	SciPy (Mann-Whitney U, Pearson, Spearman)
Advanced Analytics	Jaccard Similarity, Composite Scoring
Visualization	Matplotlib (25 charts), Power BI (4-page dashboard)
Documentation	Markdown, Jupyter Notebooks
Version Control	Git, GitHub

📁 Project Structure
india-tech-talent-intelligence-2026/ │ ├── 📁 data/ │ ├── raw/ ← Original dataset (not tracked) │ ├── processed/ ← Cleaned CSVs │ └── external/ ← Reference data │ ├── 📁 notebooks/ │ ├── 01_data_understanding.ipynb │ ├── 02_data_cleaning.ipynb │ ├── 03_exploratory_analysis.ipynb │ ├── 04_statistical_analysis.ipynb │ └── 05_advanced_analytics.ipynb │ ├── 📁 outputs/ │ ├── charts/ ← 25 analysis charts (PNG) │ ├── tables/ ← Key result tables (CSV) │ └── reports/ ← Executive insights (MD) │ ├── 📁 powerbi/ ← Dashboard (.pbix + screenshots) ├── 📁 scripts/ ← Reusable Python functions ├── 📁 sql/ ← SQL analysis queries └── 📁 docs/ ← Methodology & data dictionary





