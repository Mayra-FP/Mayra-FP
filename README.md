# Who I am
I’m a Data Engineer and Biostatistician with a background in applied statistics and health data science. 

# What I do

I build automated, reproducible data pipelines, integrate geospatial and environmental data, and apply statistical modelling and machine learning to research questions. I turn complex datasets into structured, analysis-ready resources that support reliable research.

Tech stack: R · Python · SAS · SQL · MongoDB

# Experience

## Data Engineer | Carlos III Health Institute (ISCIII)
* Designed and implemented an automated geospatial ETL pipeline in R integrating industrial pollution data from the PRTR-Spain registry with population cohort records.
* Automated web scraping (httr2, xml2) of publicly available datasets: annual emissions and facility administrative data (XML), and the facility inventory, parsed from HTML into a structured dataset with geographic coordinates exported to XLSX (openxlsx).
* Built a modular, orchestrator-based workflow with retry logic and error handling for data retrieval, cleaning, and transformation (data.table).
* Linked pollution sources to participants’ residential locations through spatial analysis (sf) and generated individual-level environmental exposure variables, exported to .fst, .RData, .csv, and .dta for use across R and Stata.
* Implemented automatic detection of newly published annual data and exposure assignment for newly added participants, scheduled with cron in the cohort’s production environment.
* Collaborated with Darwin Geospatial to unify the project’s pipelines into a common, open-access GitHub framework that researchers can run locally and adapt to other individual-level datasets.
* Learned geospatial analysis and large-data optimization in R on the job, using AI assistants to explore and validate efficient approaches.
* Supported epidemiological research by streamlining environmental exposure assessment and data preparation.

# Research and technical projects

## Master's Thesis — Understanding Deep Learning: CNN for Myringosclerosis Diagnosis
Master's in Healthcare Big Data. Two CNN architectures (from-scratch and
ResNet50 transfer learning) classifying otoscopy images to detect
myringosclerosis.

Key findings: ResNet50 (transfer learning) outperformed the from-scratch CNN, with a test F1-score of 0.98 vs. 0.89, generalizing better and more reliably distinguishing pathological from healthy eardrums.

→ [View project](myringosclerosis-transfer-learning-cnn-python/)

## Master's Thesis — Industrial Proximity and Breast Cancer Risk (MCC-Spain)
Master's in Biostatistics (UCM). Mixed-effects logistic regression models
evaluating breast cancer risk by residential proximity to industrial
facilities, stratified by menopausal status, tumor subtype and stage.
Presented at SEE-APE 2023 (Porto).

Key findings: Residential proximity (≤3 km) to industrial facilities was associated with a 30% excess risk of breast cancer (OR 1.30; 95% CI 1.00–1.67), more pronounced in premenopausal women and HER2+ tumors, with pollutant-specific risk profiles differing by menopausal status.

→ [View project](breast-cancer-industrial-pollution-mixed-models-R/)

## Bachelor's Thesis — COVID-19 Mortality Risk Factors in Spain
Applied Statistics (UCM). PLS and Ridge regression models identifying
demographic, economic and healthcare factors associated with COVID-19
deaths across Spain's provinces in 2020.

Key findings: Hospitalizations, number of hospitals, female population share, and population aged 80+ were associated with higher death counts, while detected cases, ICU admissions, and non-private hospitals were associated with lower counts.

→ [View project](covid-risk-factors-ridge-regression-sas/)

# What I studied

* Master's Degree in Healthcare Big Data (Machine Learning/Deep Learning) - ENIIT Innova IT Business School (Universidad Católica San Antonio de Murcia)
* Master's Degree in Biostatistics — Universidad Complutense de Madrid
* Bachelor's Degree in Applied Statistics — Universidad Complutense de Madrid

# Let's connect

[LinkedIn](https://www.linkedin.com/in/mayrafuentespineda)
Madrid, Spain · Open to relocation


