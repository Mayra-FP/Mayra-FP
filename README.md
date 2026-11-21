# Who I am
I’m a Data Engineer and Biostatistician with a background in applied statistics and health data science. 

# What I do

I build automated, reproducible data pipelines, integrate geospatial and environmental data, and apply statistical modelling and machine learning to research questions. I turn complex datasets into structured, analysis-ready resources that support reliable research.

Tech stack: R · Python · SAS · SQL · MongoDB

# Experience

## Data Engineer | Carlos III Health Institute (ISCIII)

Goal: Support epidemiological research by automating environmental exposure assessment and data preparation.

* Designed and built an end-to-end geospatial ETL pipeline in R linking industrial emissions from the PRTR-Spain registry to population cohort records.
* Automated data ingestion through web scraping (httr2, xml2), turning XML and HTML sources into structured, geocoded datasets.
* Built a modular, orchestrated workflow with retry logic and error handling, using data.table for high-performance transformations.
* Generated individual-level exposure variables through spatial joins (sf), delivered in multiple formats (.fst, .csv, .dta, .RData) for R and Stata users.
* Deployed the pipeline to production with cron scheduling and incremental processing: new annual releases and newly added participants are processed automatically.
* Implemented data quality checks in Python on questionnaire data (duplicates, invalid and out-of-range values) and reported recurring error patterns so they could be fixed at source.
* Co-developed with Darwin Geospatial an open-source GitHub framework that unifies the project's pipelines and can be reused with other individual-level datasets.
* Cleaned and validated participant questionnaire data in Python (duplicates, invalid and out-of-range values), and reported recurring error patterns so they could be fixed at source.

# Research and technical projects

## Master's Thesis — Understanding Deep Learning: CNN for Myringosclerosis Diagnosis
Master's in Healthcare Big Data. Two CNN architectures (from-scratch and
ResNet50 transfer learning) classifying otoscopy images to detect
myringosclerosis.

Key findings: ResNet50 (transfer learning) outperformed the from-scratch CNN, with a test F1-score of 0.98 vs. 0.89, generalizing better and more reliably distinguishing pathological from healthy eardrums.

→ [View project](https://github.com/Mayra-FP/myringosclerosis-cnn-classifier)

## Master's Thesis — Industrial Proximity and Breast Cancer Risk (MCC-Spain)
Master's in Biostatistics (UCM). Mixed-effects logistic regression models
evaluating breast cancer risk by residential proximity to industrial
facilities, stratified by menopausal status, tumor subtype and stage.
Presented at SEE-APE 2023 (Porto).

Key findings: Residential proximity (≤3 km) to industrial facilities was associated with a 30% excess risk of breast cancer (OR 1.30; 95% CI 1.00–1.67), more pronounced in premenopausal women and HER2+ tumors, with pollutant-specific risk profiles differing by menopausal status.

→ [View project](https://github.com/Mayra-FP/breast-cancer-industrial-pollution-mixed-models-R)

## Bachelor's Thesis — COVID-19 Mortality Risk Factors in Spain
Applied Statistics (UCM). PLS and Ridge regression models identifying
demographic, economic and healthcare factors associated with COVID-19
deaths across Spain's provinces in 2020.

Key findings: Hospitalizations, number of hospitals, female population share, and population aged 80+ were associated with higher death counts, while detected cases, ICU admissions, and non-private hospitals were associated with lower counts.

→ [View project](https://github.com/Mayra-FP/covid-risk-factors-ridge-regression-sas)

# What I studied

* Master's Degree in Healthcare Big Data (Machine Learning/Deep Learning) - ENIIT Innova IT Business School (Universidad Católica San Antonio de Murcia)
* Master's Degree in Biostatistics — Universidad Complutense de Madrid
* Bachelor's Degree in Applied Statistics — Universidad Complutense de Madrid

# Let's connect

[LinkedIn](https://www.linkedin.com/in/mayrafuentespineda)

Madrid, Spain · Open to relocation


