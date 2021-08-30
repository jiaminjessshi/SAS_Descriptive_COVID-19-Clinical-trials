# SAS_Descriptive_COVID-19-Clinical-trials
## 1.	Introduction
### 1.1 Purpose
This project aims to demonstrate descriptive analysis and data visualization in SAS, using a dataset about COVID-19 clinical trial studies. Sample codes can be found in this repo. 
### 1.2 Data source
Dataset used in this project is sourced from ClinicalTrials.gov. It is a database of both privately and publicly funded clinical studies worldwide, provided by the U.S. National Library of Medicine. The last update of this dataset was in April 2021. 

For more information regarding the dataset, please visit: https://www.kaggle.com/parulpandey/covid19-clinical-trials-dataset

## 2.	Demographics
### 2.1 Age
Approximately 75% of the trials enrolled adults (people older than 18 years), and 14% of the trials enrolled people across all age groups. 

![3 age bar plot-c](https://user-images.githubusercontent.com/89493265/130711300-8e0fd524-b59e-4622-ad65-617d5013141f.jpg)

### 2.2 Sex
Approximately 96% of the trials enrolled both males and females. The number of trials enrolling females only were 3.7 times those enrolling males only.

![9 sex bar plot-c](https://user-images.githubusercontent.com/89493265/130711468-266e14c3-d612-4db1-a85f-2407c1cfc192.jpg)

## 3.	Last update posted
Time period of March and May 2021 contained most trials with the last update posted. There was a steady trend observed between May 2020 and Jan 2021. Few trials (N < 100) posted their last updates prior to March 2020. 

![6 last update posted bar plot-c](https://user-images.githubusercontent.com/89493265/130711607-928b1988-f2a0-4525-852b-223f1586cb7f.jpg)

## 4.	Enrollment
The majority of the trials enrolled fewer than 100,000 people. Among the following six enrollment groups, most trials had 0-200 people, while very few trials had people enrolled among 100,001-20,000,000.

![5 enrollment histograms_v3-2](https://user-images.githubusercontent.com/89493265/131271430-28204e47-db67-4f2c-99f8-119273fef426.jpg)


## 5.	Phases
### 5.1 Phases description
* Early phase 1 (= Phase 0): Exploratory tests aiming to investigate whether a drug affects the body.
* Phase 1: The 1st time to test a drug on a small group of people, aiming to investigate drug’s safety, safe dosage, range, and potential side effects.
* Phase 2: Tests of a drug are assigned to a large group of people (N ≥ 100), aiming to examine drug’s treatment effects, safety, and the best dose.
* Phase 3: Tests of a drug are assigned to a larger group of people (N ≥ 1,000), aiming to ensure drug’s effectiveness, monitor side effects, make comparison with alternative routine treatments, and collect information related to drug’s safety.
* Phase 4: It happens after drug is approved for marketing, aiming to gather information regarding the best approach to use a drug, and its long-term risks and benefits. 
* Note that it’s acceptable to combine Phase 1 and Phase 2 as well as Phase 2 and Phase 3.

#### References
* https://www.canada.ca/en/health-canada/services/clinical-trials.html
* https://clinicaltrials.gov/ct2/about-studies/glossary

### 5.2 Visualization
Approximately 78% of the trials were in Phase 2, Phase 3, or combination designs. While around 8% of the trials had drugs approved for marketing, approximately 14% of the trials were in their early phases (Phase 1 or Early phase 1).

![8 phase bar plot-c](https://user-images.githubusercontent.com/89493265/130712645-b518e154-d648-4398-ad82-8fbd4afad423.jpg)

## 6.	Study type
### 6.1. Study type description
*	Interventional (= experimental): an intervention, eg. a drug, is assigned to a group of people.
*	Observational (= epidemiologic): no intervention assigned, but an exposure and outcome of interest are compared across populations.   
*	Expanded access (= compassionate use): An investigational medicine given to patient with a serious disease/condition for treatment outside of clinical trials, without available alternative treatments 

#### References
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4083571/
* https://www.fda.gov/news-events/public-health-focus/expanded-access

### 6.2 Visualization
The number of interventional studies were over 1.3 times that of observational studies. Only 0.5% of the studies were classified as expanded access.

![10 study type bar plot-c](https://user-images.githubusercontent.com/89493265/130712810-8a49c4e2-3820-4572-b382-faacafd40642.jpg)

## 7.	Interventions
Drug was the top 1 intervention type, and its frequency was approximately 3 times those of diagnostic test and behavioral intervention types. Biological and device were the top 4 and top 7 intervention types respectively. 

![4 int bar plot-c](https://user-images.githubusercontent.com/89493265/130712922-3022e5de-6b6b-44d0-abf9-d8678de64701.jpg)

## 8.	Study design
### 8.1 Allocation: N/A
Among trials not having information about allocation, intervention model included parallel, sequential, or single group assignments. Masking was open label, single, or double. Primary purpose included treatment, diagnostic, and health services research, etc. The most common study design was single group assignment, open label, with a primary purpose of treatment. 

![2 study design_v3_a1-c](https://user-images.githubusercontent.com/89493265/130713049-25117569-3dbc-4414-ad0b-f574cd6c4544.jpg)

### 8.2 Allocation: Non-Randomized
Among trials with non-randomized allocation, intervention model included crossover, factorial, parallel, sequential, and single-group assignments. Masking was open label, single, double, triple, or quadruple. Primary purpose included diagnostic, prevention, and screening, etc. The most frequent study design was parallel assignment, open label, with a primary purpose of treatment. 

![2 study design_v3_a2_Page_1-c](https://user-images.githubusercontent.com/89493265/130713186-08252fa3-44e6-4636-af96-620f6fd5f101.jpg)
![2 study design_v3_a2_Page_2-c](https://user-images.githubusercontent.com/89493265/130713191-434e3671-10da-4c81-a2ca-1a73fde80afc.jpg)

### 8.3 Allocation: Randomized
Among trials with randomized allocation, intervention model included crossover, factorial, parallel, sequential, and single-group assignments. Masking was open label, single, double, triple, or quadruple. Primary purpose included support, prevention, and screening, etc. The most frequent study design was parallel assignment, open label, with a primary purpose of treatment. 

![2 study design_v3_a3_Page_1-c](https://user-images.githubusercontent.com/89493265/130713556-9021fded-a109-4173-a5e9-bf932ad177d7.jpg)
![2 study design_v3_a3_Page_2-c](https://user-images.githubusercontent.com/89493265/130713551-c6652fcb-c8ce-4a5f-b4c7-12c294a88878.jpg)
![2 study design_v3_a3_Page_3-c](https://user-images.githubusercontent.com/89493265/130713552-d1507443-21b5-432a-9547-4e2d6f54712a.jpg)
![2 study design_v3_a3_Page_4-c](https://user-images.githubusercontent.com/89493265/130713553-89cde9dc-ab9b-41fd-9790-26ddff2e468b.jpg)
![2 study design_v3_a3_Page_5-c](https://user-images.githubusercontent.com/89493265/130713554-481e1374-6675-4abc-9a62-199823460a37.jpg)

### 8.4 Observational
Among observational studies, the model included case-control, case-crossover, case-only, cohort, ecological, family-based and other. Time perspective included cross-sectional, prospective, retrospective, and other. The most common study design was prospective cohort. 

![2 study design_v3_o-c](https://user-images.githubusercontent.com/89493265/130713822-7d422512-a8ac-4690-bc94-71e6659a4740.jpg)

## 9. Conclusion
*	The majority of the COVID-19 trials enrolled both male and female adults, with last updates posted between March and May 2021.  
*	Most trials enrolled 0-200 people. 
*	Approximately 78% of the trials were in Phase 2, Phase 3, or combination designs (Phase 1 | Phase 2 or Phase 2 | Phase 3).
*	Most trials either had interventional or observational study designs. 
*	Drug was the most common intervention type. 
*	Among trials with missing allocation information, the most common study design was single group assignment, open label, with a primary purpose of treatment.
*	Among trials with either non-randomized or randomized allocations, the most frequent study design was parallel assignment, open label, with a primary purpose of treatment.
*	Prospective cohort was the most common observational study design.

## 10. Technical notes
*	For each section, erroneous data were either deleted or coded as ‘Unknown.’
*	For variable having large proportion of missingness, all the missing data were coded as ‘Unknown.’
*	Blanks were coded as missing data. 


