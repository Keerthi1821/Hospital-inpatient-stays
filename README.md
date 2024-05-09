Project Goal:
Our objective for the project is to forecast the overall treatment expenses as well as Developing and Evaluating Policy, Epidemiology, Health Planning/Resource Allocation and Quality of Care Assessment within the Statewide Planning and Research Cooperative System (SPARCS) by leveraging diverse input variables through a range of supervised machine learning algorithms, predominantly regression-based, alongside other data analytics methodologies.

Overview:
SPARCS, founded in 1979 through collaboration between the healthcare sector and government entities, is an extensive data reporting framework. Initially designed to gather data on hospital discharges, SPARCS now captures detailed patient information encompassing characteristics, diagnoses, treatments, services, and costs for all hospital discharges, ambulatory surgeries, outpatient visits, and emergency department encounters across New York State.

Dataset Summary:
Data Source:
“Hospital Inpatient Discharges (SPARCS De-Identified)” dataset is collected/downloaded from the New York State Department of Health. The dataset is big as it had over 2.35 million rows and 34 columns.

All Variables:
hospital_service_area, hospital_county, operating_certificate_number, permanent_facility_id, facility_name, age_group, Zip_Code_3, gender, race, ethnicity, length_of_stay, type_of_admission, patient_disposition, discharge_year, ccs_diagnosis_code, ccs_diagnosis_description, ccs_procedure_code, ccs_procedure_description, apr_drg_code, apr_drg_description, apr_mdc_code, apr_mdc_description, apr_severity_of_illness_code, apr_severity_of_illness_description, apr_risk_of_mortality, apr_medical_surgical_description, payment_typology_1, payment_typology_2, payment_typology_3, birth_weight, abortion_edit_indicator, emergency_department_indicator, total_charges, total_costs.

Target Variable(s): 
Our primary focus is on predicting the "Total_Cost" variable as it serves as the primary target for our predictive modeling efforts. Additionally, as we delve into data analysis, we remain open to exploring other potential target variables that could unveil intriguing patterns for further investigation in areas such as policy development and assessment, epidemiology, healthcare planning and resource distribution, as well as quality of care assessment.

Data Limitations: 
The provided data file is de-identified, containing basic record-level information without any protected health information (PHI) as per HIPAA regulations. The health-related data in the file lacks individual identifiability since any potentially identifiable elements have been removed. Moreover, secondary diagnoses, procedures, and revenue codes are absent from this dataset. However, the geographical column only includes a limited number of regions such as Allegany, New York, etc. The presence of missing values in columns like Payment Technology 2 and Payment Technology 3 can impact our analysis. Additionally, columns like race and ethnicity do not accurately represent the broader population, leading to biased analyses. Furthermore, the inclusion of various coding systems columns like CCS Diagnosis Code may pose challenges for users unfamiliar with such coding systems.

Analysis Questions:
1.	Is it possible to forecast the Total Cost of Inpatient Discharges utilizing input features such as length of stay and patient disposition? If so, what methods can be employed to achieve this prediction?
2.	What are the potential determinants that could impact the development and assessment of policies, and how do these factors differ?
3.	Can we identify any straightforward patterns in Total Cost and their corresponding CCS Diagnosis Description across various facilities where services were conducted, as indicated by the Permanent Facility Identifier (PFI)?

Methodology:
Based on our initial dataset examination, we plan to employ the following methods: Data preprocessing, Exploratory Data Analysis (EDA), Feature Engineering, Model Construction, Model Selection, Model Evaluation, and Data Visualization. Owing methods based on our initial analysis of the dataset:

Conclusion:
Our project aims to predict both treatment costs and aspects related to policy development, epidemiology, health planning/resource allocation, and quality of care assessment within the Statewide Planning and Research Cooperative System (SPARCS). We intend to achieve this by utilizing various input variables and employing supervised machine learning algorithms, primarily focusing on regression techniques, along with other data analytics approaches.
