# Assignment 5: Prognostic Models

## Objective
Analyze and evaluate prognostic machine learning models designed to predict patient mortality in emergency department settings, using routine blood test results and demographic information.

## What I Did
- Reviewed a study that developed and validated ML models to predict short- and long-term mortality (3, 10, 30, and 365 days post-admission).
- Examined model predictors including blood biomarkers (LDH, BUN, leukocyte counts, albumin, suPAR), age, and sex.
- Evaluated predictive performance using AUC metrics across multiple ML algorithms.
- Reflected on clinical utility, scalability, and limitations of these prognostic models.

## Weekly Discussion Insights
- AI-based diagnostic tools, especially those using deep learning, improve diagnostic accuracy for conditions such as skin cancer.
- AI assistance increased sensitivity (true positive rate) and specificity (true negative rate) compared to clinician-only diagnoses, demonstrating reduced missed diagnoses and false alarms.
- Key metrics like sensitivity, specificity, and accuracy are essential to evaluate AI clinical effectiveness.
- Questions raised:
  - How do developers ensure fairness and accuracy across diverse patient populations?
  - What regulatory standards are required for clinical adoption?
- Organizations use **explainable AI (XAI)**, ongoing monitoring, and regulatory frameworks (FDA, WHO) to maintain fairness, transparency, and clinical safety over time.

## Assignment Summary
- ML prognostic models analyzed 48,841 emergency admissions.
- Fifteen ML algorithms were tested; AUC values ranged from 0.85–0.93 for top-performing models.
- Short-term mortality predictors: LDH, leukocytes, BUN, MCHC.
- Long-term mortality predictors: age, LDH, suPAR, albumin, BUN.
- Advantages:
  - High predictive performance with minimal, widely available data.
  - Simple workflow integration for emergency departments.
  - Supports early risk identification, triage decisions, and resource allocation.
- Limitations:
  - Retrospective single-center data, limiting generalizability.
  - External validation still needed before widespread clinical adoption.
- Personal reflection:
  - The model demonstrates how practical AI solutions can balance accuracy and usability, increasing likelihood of real-world implementation.

## References
- Stanford Medicine. (2024). AI improves accuracy of skin cancer diagnoses in Stanford Medicine-led study. Stanford Medicine News. https://news.stanford.edu/stories/2024/04/ai-skin-diagnosis
- TechTarget. (2025). Artificial intelligence tools improve skin cancer diagnostic accuracy. TechTarget Health Analytics. https://www.techtarget.com/healthtechanalytics/news/366590002/Artificial-intelligence-tools-improve-skin-cancer-diagnostic-accuracy
- World Health Organization. (2023). Ethics and governance of artificial intelligence for health. https://www.who.int/publications/i/item/9789240029200
- U.S. Food and Drug Administration. (2024). Artificial intelligence and machine learning in software as a medical device. https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-software-medical-device
- Jawad, B. N., Shaker, S. M., Altintas, I., Eugen-Olsen, J., Nehlin, J. O., Andersen, O., & Kallemose, T. (2024). Development and validation of prognostic machine learning models for short- and long-term mortality among acutely admitted patients based on blood tests. *Scientific Reports, 14*, 5942. https://www.nature.com/articles/s41598-024-56638-6
- Mamandipoor, B., Hsu, C.-N., Krause, M., Schmidt, U. H., & Gabriel, R. A. (2025). Development and external validation of a multimodal artificial intelligence mortality prediction model of critically ill patients using multicenter data. https://arxiv.org/abs/2512.19716
