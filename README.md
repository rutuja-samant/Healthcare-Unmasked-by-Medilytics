# Healthcare-Unmasked-by-Medilytics
This repository hosts the comprehensive analysis of multi-year hospital data in New York. Leveraging Python libraries such as Pandas, Matplotlib, and Seaborn, this project explores demographic influences on disease patterns, treatments, and predictive modeling for hospital charges.

Hospitals and the healthcare industry form a foundation in any society by providing critical care, diagnostic services, and life-saving treatments. Using the dataset of de-identified Inpatient Discharges from a myriad of New York Hospitals, we want to perform several analyses of the patient data, the diseases and their procedures, the financial aspect of the industry, etc. 

The project will give a comprehensive overview of the hospital data in New York over multiple years. It is important to gain insights into the dynamics of the healthcare system of New York, which has a diverse and ever-growing population. Understanding these dynamics is essential for healthcare planning, as it equips policymakers, healthcare administrators, and researchers with valuable information to comprehend the evolving healthcare needs of the population.

We will explore how demographic factors influence disease contraction and treatment outcomes, and understand the shifting vulnerabilities of the population to specific diseases over time to ensure that the right treatments are available to those in need.  Additionally, we will examine the evolving landscape of treatments and how hospitals have specialized in various areas as it helps hospitals be equipped to provide the best care for their communities. We also plan on developing predictive models that can foresee future patient admissions for certain diseases in a county to strategize better policies and help hospitals plan better. We will predict accurate total estimate charges to ensure that patients have access to affordable care and help insurance providers manage costs better. We’ll identify hospitals with higher charges and explore alternatives that contribute to cost-effective healthcare. 
This analysis will serve as a vital tool for enhancing healthcare planning strategies, enabling informed resource allocation, and forming the foundation for evaluating the performance of New York's healthcare system. By identifying patterns and shifts in healthcare demands, this project will not only aid in optimizing healthcare delivery but also contribute to the overall improvement of public health in these crucial and populous states.

# Questions of Interest
1. How do a population’s demographic factors into disease contraction and treatment?
2. How has the population's vulnerability to certain diseases changed over the years?  
3. How have treatments for certain diseases changed over the years?
4. Is there a way hospitals can better predict discharge charges and decrease the difference between the estimated charge and actual charges incurred at the time of discharge?

# Dataset Description
Dataset Source: https://health.data.ny.gov/browse?q=Hospital%20Inpatient%20Discharges%20(SPARCS%20De-Identified)%3A%20&sortBy=relevance 

The "Hospital Inpatient Discharges (SPARCS De-Identified) Dataset" provided by the New York State Department of Health, contains a rich and anonymized repository of healthcare information capturing the landscape of inpatient care in the state of New York. The dataset offers priceless insights into patient admissions, diagnoses, medical procedures, and a wide array of healthcare-related variables such as Clinical Classification Software (CCS) and All Patient Refined (APR). 
This dataset is accessible through the New York State's official website and is curated by the Division of Information and Statistics, a branch of the New York State Department of Health. It resides within the Statewide Planning and Research Cooperative System (SPARCS) data repository, a trusted source for healthcare information in the state of New York. For the project, we have combined datasets from the year 2012 to 2021 that we acquired from the government health website. In total, the data has over 23 million observations combined from all the years where each row represents the information about a specific inpatient who was discharged from the hospital. Each patient has over 33 attributes describing the demographics of the patient, details about the hospital the patient was admitted to, the disease contracted by the patient, the procedure performed by the hospital, and the financial costs the patient and the hospital had to undertake. 


# Data Processing Tasks
1. Acquiring Data 
Get the data from the official website of the New York state. Download and load it into Google Colab notebook.

2. Exploratory Data Analysis
Analyze the data by performing exploratory data analysis to understand the processing and cleaning tasks to be done on the data for the actual analysis.

3. Drop Columns
Remove columns that are not consistent throughout all the datasets of the years.

4. Merge Data
Combine a decade worth of medical data.

5. Find Redundant Data
Remove columns that may be redundant to increase computational speed and cost.

6. Check for Consistency
Verify the data is consistent across all column types/names. Check for anomalous data, spelling mistakes and cross reference APR/CCS codes to ensure the data is consistent.

7. Null Values
Clean Null values and clean the data.
 
8. Sampling the Data
Depending on computational costs, sample data to represent the entire population.

9. Encode Data
Apply a numerical value to categorical data for model training.



