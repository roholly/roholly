# Rosemary Holly

**Data Science · Data Engineering · Data-Driven Strategy**  
[LinkedIn](https://www.linkedin.com/in/rosemaryholly/)

---

Whether I'm leading the work or doing it, I've never been comfortable with work I don't understand. This portfolio documents that instinct in practice. Analytical work drawn from a career spent building and operating production systems at national scale, and formal graduate study, presented together because the two inform each other.

I've spent my career extracting signal from complex, high-volume, poorly-documented data, designing collection pipelines, building enrichment and correlation systems, and delivering stakeholder-specific intelligence in high-stakes operational environments. That work has run parallel to continuous self-directed technical education, including math, computer science, programming, a post-graduate certification in data science and business analytics at UT McCombs, and now a Master of Science in Analytics at Georgia Tech. The formal methods have always followed the operational problems that made them necessary.

I'm now applying the same instinct to AI systems: working out what a model is doing when you can't check its work directly.

This portfolio is where those things meet.

---

## Portfolio

### AI Safety

| Project | What it shows |
|---|---|
| [Sandbagging Hesitation Monitor](https://github.com/roholly/sandbagging-hesitation-monitor) | Can a monitor detect when an AI model is told to underperform, using only how hesitant it was? On 200 math problems, yes: AUC 0.997 against a matched control, including answers that were still correct. Limitations stated plainly. |

### Monitoring & Anomaly Detection

| Project | What it shows |
|---|---|
| [IRS Modernized e-File Monitoring and Event Management](https://github.com/roholly/irs-mef-monitoring) | Reconstructed transaction sessions from interspersed logs across the 36 security gateways handling national e-File traffic, producing ~200 metrics every five minutes for national e-File oversight. Documentation only; source code is not public. |
| [Atlanta Climate Analysis](https://github.com/roholly/atlanta-climate-analysis) | CUSUM change detection and Holt-Winters smoothing on 20 years of daily temperatures to find each year's end of summer and test for a sustained warming trend. |
| [Power Grid Optimization](https://github.com/roholly/power-grid-optimization) | Layered framework for regional grid operations: demand forecasting, CUSUM anomaly detection, day-ahead unit commitment, and real-time dispatch. |

### Machine Learning & Operations Research

| Project | What it shows |
|---|---|
| [ReneWind Predictive Maintenance](https://github.com/roholly/renewind-predictive-maintenance) | Seven classifiers across three class-imbalance strategies on 20,000 turbines, optimized for recall because a missed failure costs far more than an inspection. |
| [Utility Shutoff Optimization](https://github.com/roholly/utility-shutoff-optimization) | Four-step pipeline design: SVM classification, logistic prioritization, integer-programming crew assignment, and route optimization. |
| [Airport Security Simulation](https://github.com/roholly/airport-security-simulation) | Two-stage discrete-event simulation (SimPy): 36 staffing configurations × 50 replications against a 15-minute wait target. |
| [Geospatial Data Integration: SSURGO & Macrostrat](https://github.com/roholly/geospatial-ssurgo-macrostrat) | Joined USDA soil and Macrostrat geology data via REST APIs to connect soil chemistry to the geology underneath. |
| [RoSmart Circuit: MIT REDD Energy App](https://github.com/roholly/RoSmart_Circuit_MIT_Data) | Proof-of-concept web app visualizing MIT's Reference Energy Disaggregation Data Set. |

### Coursework

| Project | What it shows |
|---|---|
| [EasyVisa Classification](https://github.com/roholly/easyvisa-classification) | Predicting visa certification outcomes with ensemble models, optimizing F1 because both error types carry real costs. |
| [Trade & Ahead Stock Clustering](https://github.com/roholly/trade-ahead-stock-clustering) | Clustering 337 NYSE companies by financial behavior into investor profiles. |
| [E-news Express A/B Test](https://github.com/roholly/enews-express-ab-test) | Landing-page experiment analyzed with t-tests, two-proportion z-tests, and chi-square tests. |

---

## Technical Skills

**Languages**  
Python · R · SQL · Perl · Java · comfortable working across languages as problems require

**AI & LLMs**  
Hugging Face transformers · PyTorch · token-level probability analysis · evaluation design with controls

**Machine Learning & Statistics**  
Supervised learning: regression, classification, ensemble methods (Random Forest, XGBoost, Gradient Boosting, AdaBoost, Bagging)  
Unsupervised: clustering (K-Means, hierarchical), dimensionality reduction (PCA)  
Time series: Holt-Winters exponential smoothing, CUSUM change detection  
Optimization: linear and integer programming, MILP, MINLP, network optimization  
Statistical testing: hypothesis testing, ANOVA, chi-square, A/B testing  
Simulation: discrete-event simulation

**What Drives the Work**  
The most rewarding part is the subject matter. Getting to understand a new domain, learning what the data actually represents, and figuring out how disparate pieces connect to produce something meaningful and actionable. That's the part I find genuinely interesting. The methods are in service of that. So is the commitment to letting the results say what they say, without steering them toward a more convenient answer.

**Data Engineering**  
ETL/ELT pipeline design · custom schema and data model design · API integration  
Oracle · DB2 · SQLite · MS SQL · SSIS

**Cloud**  
AWS (GovCloud and Commercial), held Cloud Service Owner role for VA Enterprise Cloud

---

## What I've Actually Built

The analytical work in this portfolio reflects methods I'm building formally. The instinct behind it is older.

For the IRS Modernized eFile program, I designed and built a centralized monitoring and event management system that processed hundreds of thousands of interspersed log lines per polling interval across 36 security gateways, reconstructing session transaction statistics by tracking state in memory by gateway device name and session ID, producing approximately 200 distinct enriched metrics every five minutes for national-scale tax filing oversight. A separate automated reporting layer integrated seven disparate data sources into a custom database and schema, delivering stakeholder-specific daily intelligence to IRS executives for program and migration decisions. Several source systems were undocumented; I reverse-engineered the backend to surface signals not otherwise accessible.

That's the problem I find interesting: taking data that is complex, high-volume, fragmented, or poorly understood, and making it tell you something actionable.

Full documentation of this system is in the [IRS Modernized e-File Monitoring and Event Management](https://github.com/roholly/irs-mef-monitoring) repository.

---

## Background

Enterprise IT across the IRS, DoD, Navy, Army, and the VA, through SRA International, IBM, Cognosante, GovernmentCIO, and Luminara Consulting, the woman-owned small business I founded (SBA-certified, D&B Past Performance score: 96%). Co-authored two IBM Redbook publications on enterprise IT service management.

Graduate study: Master of Science in Analytics, Georgia Tech (in progress) · UT McCombs Post-Graduate Certificate in Data Science & Business Analytics.

I'm drawn to roles where strategic judgment, analytical depth, and technical credibility are all expected, where leading the work and understanding the work aren't treated as separate jobs. Right now that means AI evaluation and oversight: the problem of monitoring systems whose behavior you can’t verify directly.

---

[LinkedIn](https://www.linkedin.com/in/rosemaryholly/) · [GitHub](https://github.com/roholly)
