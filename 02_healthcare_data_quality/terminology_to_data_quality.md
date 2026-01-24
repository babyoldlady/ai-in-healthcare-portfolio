# From Medical Terminology to Data Quality Challenges

Accurate medical terminology is not just a clinical concern—it directly determines the quality and reliability of healthcare data used to train and deploy AI systems. When terminology is inconsistently applied, underdocumented, or overly subjective, it introduces structural weaknesses that propagate through datasets and models.

## Underdocumented Menopause and Perimenopause
Menopause and perimenopause are frequently described informally in clinical notes or documented only after symptom escalation. Inconsistent use of diagnostic codes and reliance on patient self-reporting result in sparse or delayed labels, limiting an AI model’s ability to identify these transitions longitudinally. This underdocumentation disproportionately affects women’s health data and reduces the visibility of clinically meaningful patterns.

## Subjective Cognitive Decline and Label Ambiguity
Subjective cognitive decline highlights the limitations of “clean” labels in healthcare data. Because the condition relies on patient-reported experience rather than objective test results, it is often missing from structured fields or excluded from training datasets entirely. This creates blind spots in models designed to detect early cognitive change and reinforces overreliance on later-stage diagnoses.

## EHR Inconsistency and Downstream Bias
Electronic health records aggregate data from multiple providers, systems, and documentation practices, leading to variability in terminology, coding, and completeness. These inconsistencies introduce label noise and bias that AI systems may unintentionally learn and amplify, affecting model fairness, interpretability, and clinical trust.

**Related artifact:**
- *A01 Medical Terminology in AI-Enabled Healthcare* (Folder `01_medical_terminology_and_ai`)
