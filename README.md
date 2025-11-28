# analysis-take-home

We have provided three datasets describing patients’ onboarding behaviour, demographics, and interaction with our motor-exercise feature. Please analyse this data to understand patient churn and factors influencing engagement, with a particular focus on:
- Churn rates (e.g., proportion of users not signing up and completing certain features)
- Determinants of engagement, especially the factors influencing the number of motor exercises completed.

## Available Data

### 1. patient_summary.csv
   
High-level information about onboarding behaviour:
 - patient_number: sequential ID reflecting the order in which a clinician added each patient. Once added patients have to go away and sign up on their own device.
 - UUID: unique patient identifier (created when the patient signs up to Kneu health)
 - watched_welcome_video: whether they viewed the full welcome video
 - added_medications:  whether they added medication information to the platform
 - medication_acknowledged: number of medication acknowledgments recorded

### 2. patient_demographics.csv
  
Baseline demographic data:
 - UUID
 - age: in years
 - sex_at_birth: sex assigned at birth
 
### 3. patient_movement_exercises.csv

Exercise-level engagement data. An exercise is a single test a patient does on their phone which provides a score quantifying the severity of their symptom.
    - UUID
    - scheduled_datetime: timestamp of the scheduled motor exercise
    - completed_datetime: timestamp of completion (empty if not motor exercise completed)
    - score: motor score
