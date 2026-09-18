OCD Patient Dataset: Demographics & Clinical Data Analysis


# OVERVIEW # 
This project analyzes and explores demographic and clinical patterns among 1,500 individuals diagnosed with Obsessive-Compulsive Disorder (OCD). The goal is to uncover patterns in patient
 demographics, symptom types, and severity scores that could support clinical understanding of the disorder. 

# OBJECTIVES #
  - What is the gender distribution among patients?
  - How is ethnicity distributed across the patient population?
  - What percentage of patients have a family history of OCD?
  - Which obsession and compulsion types are associated with the highest symptom severity (Y-BOCS)?
  - How is symptom severity distributed across the population (Mild, Moderate, Severe, Extreme)?
  - Does family history correlate with higher severity?
  - Does comorbidity (depression/anxiety) vary by gender, marital status, or age?
  - Is medication type associated with a specific obsession category?

# DATASET #
  - Souce: https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data/data
  - Size: 1,500 patient records
  - Fields: Patient ID, Age, Gender, Ethnicity, Marital Status, Education, OCD Diagnosis Date, Duration of Symptoms (months), Previous Diagnoses, Family History of OCD (true/false)

# KEY FINDINGS
  - The cohort averages 46.78 years old, with ethnicity spread nearly evenly across four groups (African, Asian, Caucasian, Hispanic).
  - 50.67% of patients have a family history of OCD — roughly an even split.
  - About two-thirds of patients (~1,000 of 1,500) fall into the "Extreme" Y-BOCS severity band, far outweighing Severe, Moderate, and Mild combined.
  - Symptom type is the clearest driver of severity variation: Praying, Counting, and Ordering-related symptoms show the highest average Y-BOCS scores (~40-42), Checking the lowest (~38), and Washing shows the widest spread with outliers at both extremes.
  - Family history did not correlate with higher severity — the Yes/No split within the Extreme band closely matches the overall population split.
  - Comorbidity count (depression + anxiety) showed no meaningful variation by gender or marital status, staying within a narrow 0.98-1.07 range across all groups.
  - Symptom duration and average Y-BOCS score both stayed flat across age bins, showing no age-related trend.
  - Medication class (SSRI, SNRI, Benzodiazepine, or none) was distributed evenly across obsession types, with no strong prescribing pattern by symptom category.

Overall, clinical presentation (obsession/compulsion type) proved to be a more meaningful lens for understanding severity in this dataset than demographic or familial factors, most of which showed flat, evenly distributed patterns.

# DASHBOARD
Live interactive dashboard: https://public.tableau.com/views/OCDAnalysis/OCDDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# TECH #
  - Python (pandas, numpy)
  - Data visualization: Tableau
