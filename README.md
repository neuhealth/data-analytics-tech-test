<!-- LOGO -->
<br />
<h1>
<p align="center">
  <img src="https://assets.kneu.com/images/kneu/logo-secondary-forest-kneu.png" width="200px" height="200px" alt="Logo">
  <br/>
  <br>Data Analytics Technical Test
</p>
</h1>

This exercise is designed to evaluate your ability to analyse real-world product data, generate insights, and communicate your findings clearly.

You are provided with three datasets containing information on patient onboarding behaviour, demographic characteristics, and engagement with our motor-exercise feature. Your goal is to analyse this data to understand **patient churn** and **factors driving engagement**, with particular focus on:

* **Churn rates** (e.g., proportions of users who do not complete key onboarding actions or who disengage at specific stages)
* **Determinants of engagement**, especially factors associated with the **number of motor exercises completed**

Please feel free to use any analytical approach or tools you prefer. You will be assessed on the clarity, rigour, and interpretability of your work.

## Available Data

### 1. `patient_summary.csv`

High-level information describing onboarding behaviour:

| Field                       | Description                                                                                                                                           |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **patient_number**          | Sequential identifier representing the order in which clinicians added patients. Once added, patients must independently sign up on their own device. |
| **UUID**                    | Unique patient identifier (generated at signup).                                                                                                      |
| **watched_welcome_video**   | Boolean flag indicating whether the patient watched the full welcome video.                                                                           |
| **added_medications**       | Boolean flag indicating whether the patient entered their medication information.                                                                     |
| **medication_acknowledged** | Count of medication acknowledgements recorded in the platform.                                                                                        |

### 2. `patient_demographics.csv`

Baseline demographic characteristics:

| Field            | Description                |
| ---------------- | -------------------------- |
| **UUID**         | Unique patient identifier. |
| **age**          | Age in years.              |
| **sex_at_birth** | Sex assigned at birth.     |

### 3. `patient_movement_exercises.csv`

Exercise-level engagement data. Each row corresponds to an individually scheduled motor-exercise task completed (or not completed) by a patient.

| Field                  | Description                                                         |
| ---------------------- | ------------------------------------------------------------------- |
| **UUID**               | Unique patient identifier.                                          |
| **scheduled_datetime** | Timestamp when the exercise was scheduled.                          |
| **completed_datetime** | Timestamp when the exercise was completed (empty if not completed). |
| **score**              | Motor-exercise score quantifying symptom severity.                  |

## Expected Outputs

As part of your submission, please provide:

* Your analysis in the format of your choice (e.g., notebook, slides, or written report), clearly explaining your methodology, key findings, and recommendations.
* A brief presentation summarising your work.
  * This will be delivered at the start of the panel interview.
  * Maximum length: 10 minutes
  * You should highlight your analytical approach, insights into patient churn and engagement, and any assumptions, limitations, or further questions your analysis raises

Your presentation does not need to cover every detail of your work but do focus on clarity, key insights, and how they might inform product or clinical decisions.

Your presentation does not need to cover every detail of your work—focus on clarity, key insights, and how they might inform product or clinical decisions.

