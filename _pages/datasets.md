---
layout: archive
title: "Provided Datasets: Health Gym Collection"
permalink: /datasets/
author_profile: false
---

Participants **must** use dataset(s) from the official **Health Gym** collection—a set of highly realistic synthetic medical datasets specifically designed for developing reinforcement learning algorithms in healthcare. Participants have complete flexibility to choose any dataset(s) that best align with their research question and healthcare optimization problem.

The Health Gym project addresses a critical challenge in healthcare AI research: the lack of openly accessible clinical data due to privacy concerns. These synthetic datasets were generated using advanced Generative Adversarial Networks (GANs) that preserve the statistical properties, variable correlations, and temporal dynamics of real clinical data while ensuring patient privacy and preventing re-identification.

### Available Datasets (Participant Choice)

Participants may choose from three synthetic health-related datasets:

#### 1. Acute Hypotension Dataset
* **Clinical Context:** Management of acute hypotension (low blood pressure) in intensive care unit (ICU) patients.
* **Variables (22 total):** Vital Signs (MAP, Blood Pressure), Lab Results, Respiratory metrics, GCS score.
* **Treatments (Actions):** Fluid boluses (5 categories), Vasopressors (5 categories).
* **Temporal Structure:** 48 hourly time points per patient (48-hour observation window).
* **Dataset Size:** 3,910 synthetic patients; 187,680 records; 21.7 MB.
* **RL Application:** Optimize fluid and vasopressor administration to maintain adequate blood pressure while minimizing adverse effects.

#### 2. Sepsis Dataset
* **Clinical Context:** Sepsis management in intensive care units—a life-threatening condition requiring timely intervention.
* **Variables (46 total):** Demographics, Vital Signs, Lab Results, Coagulation metrics.
* **Treatments (Actions):** Intravenous fluid inputs, Maximum vasopressor dose, Mechanical ventilation status.
* **Temporal Structure:** Up to 20 time points per patient (4-hour windows; maximum 80 hours).
* **Dataset Size:** 2,164 synthetic patients; 43,280 records; 16 MB.
* **RL Application:** Develop optimal policies for fluid resuscitation and vasopressor therapy to improve survival and transition patients to favorable health states.

#### 3. HIV Antiretroviral Therapy Dataset
* **Clinical Context:** Management of HIV infection through antiretroviral therapy (ART) in ambulatory care settings.
* **Variables (15 total):** Demographics, Disease Markers (Viral Load, CD4 count).
* **Medications (Actions):** Base drug combinations, INI, NNRTI, Extra PI, Extra pk-En.
* **Temporal Structure:** 60 monthly time points per patient (5-year observation period).
* **Dataset Size:** 8,916 synthetic patients; 534,960 records; 44.7 MB.
* **RL Application:** Optimize antiretroviral regimen selection to suppress viral load, maintain healthy CD4 counts, and minimize drug resistance and side effects over time.

---

### How to Access the Datasets
1. **Official Website:** Visit [https://healthgym.ai](https://healthgym.ai) to access all datasets and comprehensive documentation.
2. **PhysioNet Hosting:** The Acute Hypotension and Sepsis datasets are also hosted on [PhysioNet](https://physionet.org/).
3. **Format:** All datasets are provided as CSV files for easy import into Python, R, MATLAB, etc.
4. **GitHub Repository:** Code examples and tutorials are available [here](https://github.com/Nic5472K/ScientificData2021_HealthGym).

### Mandatory Citation
Teams must properly cite the Health Gym paper in their technical reports:
> *Kuo, N.I., Polizzotto, M.N., Finfer, S., Garcia, F., Sönnerborg, A., Zazzi, M., Böhm, M., Jorm, L., & Barbieri, S. (2022). The Health Gym: Synthetic Health-Related Datasets for the Development of Reinforcement Learning Algorithms. Scientific Data, 9(1). arXiv:2203.06369*
