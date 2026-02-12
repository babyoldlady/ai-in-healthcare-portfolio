# Diagnostic AI: Metrics, Calibration, and Generalizability

## Overview

In this module, I examined how computer vision and deep learning (CNNs) are being used to support medical diagnosis in dermatology, radiology, pathology, and ophthalmology. A central lesson emerged clearly: diagnostic AI cannot be evaluated by “accuracy” alone. 

Clinical AI systems must be evaluated across multiple performance dimensions, including:

- Sensitivity  
- Specificity  
- Positive Predictive Value (PPV)  
- Negative Predictive Value (NPV)  
- Area Under the Curve (AUC)  
- Calibration  

A model that performs well on paper may still fail in practice if it is miscalibrated, biased, or deployed in a different population than the one it was trained on.

---

## Development-Stage Validation: Structured Performance Reporting

Juan et al. (2023) developed a deep convolutional neural network (SkinFLNet) for skin cancer classification using model fusion and lifelong learning techniques. Importantly, the study reported:

- Sensitivity
- Specificity
- Overall accuracy
- Comparisons with board-certified dermatologists

This structured reporting illustrates how model design choices, validation datasets, and clinician benchmarks shape claims of “clinician-level” performance. Development-stage validation is necessary — but not sufficient.

---

## Deployment Reality: Calibration Drift and Subgroup Bias

Liou et al. (2024) examined a deployed malnutrition prediction model within a large healthcare system. While overall discrimination was acceptable, the authors identified:

- Miscalibration across risk groups  
- Performance variation across demographic subgroups  
- The need for targeted recalibration  

Their findings demonstrate a critical operational insight: discrimination (AUC) does not guarantee equitable or clinically appropriate performance.

Recalibration materially shifted sensitivity–specificity tradeoffs, showing that small statistical adjustments can have meaningful clinical consequences.

---

## Why This Matters for Aging, Dementia, and Menopause Care

My ongoing academic interest centers on:

- Dementia risk prediction  
- Aging populations  
- Menopause-stage care  

These domains are particularly vulnerable to:

- Gradual symptom onset  
- Heterogeneous presentation  
- Inconsistent structured documentation  
- Underdiagnosis in certain populations  

Subtle miscalibration in these contexts could delay diagnosis, amplify disparities, or reinforce documentation gaps.

Diagnostic AI must therefore be continuously evaluated, not just approved and deployed.

---

## Key Insight

Diagnostic AI systems are only as trustworthy as the quality, structure, monitoring, and interpretability of the data on which they rely.  

Development metrics are important — but post-deployment governance determines real-world safety and equity.
