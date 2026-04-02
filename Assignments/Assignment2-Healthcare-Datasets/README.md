# Assignment 2: Healthcare Dataset Analysis

## Objective
Analyze a mock healthcare dataset to calculate basic statistics and gain insight into patient demographics and health metrics, while reflecting on how healthcare datasets support AI applications in clinical settings.

## What I Did
- Reviewed a mock dataset containing patient demographics, visit details, and basic health metrics.
- Calculated the average age and average heart rate for the patient population.
- Summarized findings and discussed the limitations of small datasets.
- Reflected on the importance of structured healthcare data for AI and clinical decision support.

## Weekly Discussion Insights
- Healthcare data sources, such as EHRs (Epic, Oracle Cerner), claims data, and specialized datasets like MIMIC-IV, form the foundation for AI applications in healthcare.
- Structured and standardized data (ICD-10, CPT codes) support predictive modeling, risk stratification, and clinical decision support.
- Accurate representation of medical terminology (e.g., pulmonary embolism, pulmonary thrombolysis, hemodynamic instability) is essential for AI performance and clinician trust.
- Question raised: How can healthcare organizations best balance data quality and bias mitigation when integrating multiple data sources for AI model training?

## Dataset Overview
- 5 patient records with columns including:
  - PatientID, Age, Gender, ZipCode, VisitDate, VisitType, PrimaryConcern
  - Blood Pressure (Systolic/Diastolic), Heart Rate, BMI
  - Smoker status, Chronic Conditions, Medications Prescribed, Follow-Up Recommendations

## Analysis
- **Average Age:** 45.8 years  
- **Average Heart Rate:** 76.8 bpm  
- Observations:  
  - Patient population represents middle-aged adults with normal heart rates.
  - Findings are limited due to small dataset size; larger datasets would provide more robust insights.

## Key Learnings
- Structured healthcare datasets are critical for training AI models accurately and safely.  
- Proper data integration, standardization, and terminology improve model performance and clinician trust.  
- Basic statistical analysis provides a foundation for understanding patient populations and guiding further AI research.


## References
- Centers for Medicare & Medicaid Services. (2023). ICD-10-CM official guidelines for coding and reporting. https://www.cms.gov
- Epic Systems Corporation. (2024). With the patient at the heart: Electronic health records. https://www.epic.com
- Johnson, A. E. W., Pollard, T. J., Mark, R. G., & Horng, S. (2023). MIMIC-IV: A freely accessible electronic health record dataset. *Scientific Data, 10*(1), 1–9. https://doi.org/10.1038/s41597-023-02135-3
- Mandel, J. C., Kreda, D. A., Mandl, K. D., Kohane, I. S., & Ramoni, R. B. (2022). SMART on FHIR: A standards-based, interoperable apps platform for electronic health records. *J Am Med Inform Assoc, 29*(2), 209–215. https://doi.org/10.1093/jamia/ocab217
- Office of the National Coordinator for Health Information Technology. (2024). United States Core Data for Interoperability (USCDI). https://www.healthit.gov
- Rieke, N., Hancox, J., Li, W., et al. (2022). The future of digital health with federated learning. *NPJ Digital Medicine, 5*(1), 1–7. https://doi.org/10.1038/s41746-022-00695-3
