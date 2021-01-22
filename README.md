# Computing-sources-for-data-application
This folder contains the computing sources for the real data application section for the book chapter "Bayesian inferences for panel count data and interval-censored data with nonparametric modeling of the baseline functions". 

There are three files in this folder. In each of them, we provide the R code that is used to analyze the dataset by applying the proposed method in the book chapter. 

> The patent study 
It is an industrial economics data set from the R package `pglm'. The data set is extracted from a larger data set that is collected by \cite{hall1986} to study  the relationship between patenting and research and development activity at the firm level by the U.S. manufacturing sector during the 1970s. This data contain 346 firms in the United States, among which 147  are in the scientific sector. From 1970 to 1979, the number of patents that were granted each year is recorded for every firm. The data set also includes the firm's book value of capital in 1972 and its annual research and development (R \& D) spending for each firm.  

> They bladder tumor study 
This is the most widely used panel count data example in the literature, which arose from a bladder cancer study conducted by the Veterans Administration Cooperative Urological Research Group. In this randomized clinical trial study, all the 118 patients had experienced superficial bladder tumors when they entered the trial. They were randomized into one of three treatment groups: placebo, thiotepa, and pyridoxine. During the study at each follow-up visit, new tumors since the last visit were counted, measured and then removed transurethrally. The number of follow-up clinical visits and follow-up times varied noticeably from patient to patient. The primary objective of the study was to determine if any treatment could significantly reduce the recurrence of bladder tumor. 

> The breast cosmesis study
This is one of the most commonly used interval-censored data set in the literature. The data came from a study of 94 early breast cancer patients who were treated with adjuvant therapy following tumorectomy. The primary goal of this study was to identify if treating patients with primary radiation therapy and adjuvant chemotherapy could have better long-term cosmetic results than treating with radiotherapy alone. Among all patients,  48 patients were treated with radiation therapy combined with chemotherapy and 46 patients  were treated with radiation therapy alone.  In this study, patients were examined periodically and actual examination times differed from patient to patient since some of them missed their visits.  The response variable of interest was the time (in months) until the appearance of breast retraction. Since the exact onset time of breast retraction was not observed due to the study design, only interval-censored data were available.  
