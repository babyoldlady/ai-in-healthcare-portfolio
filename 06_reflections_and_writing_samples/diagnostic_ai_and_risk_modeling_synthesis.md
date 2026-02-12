# Evolving Understanding of Diagnostic AI and Risk Modeling in Healthcare

This reflection synthesizes key lessons from recent modules on diagnostic AI, risk modeling, validation, and bias governance.

---

## Phase 1: Metrics Beyond Accuracy

Early in this course, I learned that diagnostic AI must be evaluated beyond accuracy. Metrics such as:

- Sensitivity  
- Specificity  
- PPV/NPV  
- AUC  
- Calibration  

provide a more complete understanding of model behavior.

A model may discriminate well but remain poorly calibrated, meaning predicted risk does not align with observed outcomes.

---

## Phase 2: Deployment, Drift, and Recalibration

Research examining deployed models revealed that:

- Calibration can drift  
- Subgroup performance may diverge  
- Recalibration can materially shift clinical tradeoffs  

Performance must be monitored after implementation, not assumed stable.

This phase deepened my understanding of AI as a lifecycle system rather than a static tool.

---

## Phase 3: Governance and Accountability

A central unresolved question emerged:

Who decides when bias is “tolerable” for clinical use?

Monitoring, recalibration, and technical fixes are important — but governance structures ultimately determine accountability.

AI systems in healthcare operate within ethical, institutional, and regulatory frameworks, not just mathematical ones.

---

## Personal Throughline: Aging, Dementia, and Menopause Care

Throughout this coursework, I have applied these lessons to:

- Dementia risk prediction  
- Aging populations  
- Menopause-stage care  

These areas are characterized by:

- Gradual symptom development  
- Heterogeneous presentation  
- Underrepresentation in datasets  
- Documentation variability  

These features create ideal conditions for silent bias amplification if models are not carefully validated and monitored.

---

## Systems-Level Insight

AI systems in healthcare are only as reliable as:

- The quality and structure of their underlying data  
- Their calibration across subgroups  
- Their external validation  
- Their governance and monitoring frameworks  

This portfolio increasingly reflects a systems-oriented perspective on clinical AI: performance metrics, equity, validation, and governance are inseparable.
