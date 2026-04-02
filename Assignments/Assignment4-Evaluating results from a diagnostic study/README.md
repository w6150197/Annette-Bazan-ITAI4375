# Assignment 4: Evaluating Results from a Diagnostic Study

## Objective
Analyze and evaluate results from a diagnostic study, focusing on AI-assisted diagnostic tools and their performance metrics, clinical impact, and practical considerations in healthcare.

## What I Did
- Reviewed a new multi-cancer early detection blood test that identifies tumor DNA fragments in blood.
- Evaluated test performance using sensitivity, specificity, and positive predictive value.
- Reflected on the implications of diagnostic accuracy for early detection, patient care, and clinical decision-making.
- Considered ethical and practical integration of AI diagnostic tools into clinical workflows.

## Weekly Discussion Insights
- AI-based diagnostic tools, especially those using deep learning and computer vision, can classify medical images with high accuracy.
- Models such as CNNs, SkinFLNet, ResNet50, and DenseNet121 show strong performance in detecting conditions like skin cancer.
- Understanding key metrics such as sensitivity, specificity, accuracy, and AUC is crucial to assess effectiveness compared to human clinicians.
- Post-deployment monitoring is essential:
  - Periodic revalidation with updated datasets.
  - Comparison of AI outputs with clinician decisions.
  - Tracking performance metrics to detect drift.
  - Governance frameworks to ensure transparency, accountability, and human oversight.
- Questions raised:
  - How can AI diagnostic tools be integrated without increasing cognitive load for clinicians?
  - What training or oversight is required for safe AI-assisted decision-making?

## Assignment Summary
- Evaluated a multi-cancer early detection blood test using patient DNA fragments:
  - Sensitivity: ~40.4% (detects about 4 out of 10 cancers)
  - Specificity: 99.6% (correctly identifies healthy patients)
  - Positive predictive value: 61.6% of positive results indicated cancer
- Advantages:
  - Early detection of cancers, including those without routine screenings
  - Combined with standard screening, identifies more cancers than standard methods alone
- Limitations:
  - False positives and false negatives exist
  - Requires careful clinical interpretation and follow-up
- Personal reflection:
  - Recognized the potential life-saving impact of early detection, inspired by personal family experiences with late-stage cancer.

## References
- Juan, C.-K., Su, Y.-H., Wu, C.-Y., et al. (2023). Deep convolutional neural network with fusion strategy for skin cancer recognition: Model development and validation. *Scientific Reports.* https://doi.org/10.1038/s41598-023-42693-y
- Multimodal deep learning ensemble framework for skin cancer detection. (2025). *Scientific Reports.* https://doi.org/10.1038/s41598-025-30534-3
- Food and Drug Administration. (2024). Artificial intelligence and machine learning in medical devices. https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-medical-devices
- Topol, E. J. (2023). High-performance medicine: The convergence of human and artificial intelligence. *Nature Medicine, 29*(1), 44–56. https://www.nature.com/articles/s41591-022-02146-8
- Advisory Board. (2025, October 27). This new blood test could detect more than 50 types of cancer.
- Agrawal, N. (2025, December 2). Cancer-detecting blood tests are on the rise. Do they work? *The New York Times.*
- OHSU News. Hastings. (2025, December 26). Blood test finds seven times more cancers than standard screenings. *OHSU News.*
