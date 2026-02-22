---
layout: archive
title: "The Data: Health Gym 🧬"
permalink: /datasets/
author_profile: false
---

To hack healthcare, you need the right data. For IDSC 2026, participants **must** use dataset(s) from the official **Health Gym** collection. You have complete flexibility to choose any dataset(s) below that best aligns with your team's research question and algorithmic approach!

<div style="background: rgba(146, 254, 157, 0.1); border-left: 5px solid #92FE9D; padding: 20px; border-radius: 8px; margin: 25px 0;">
  <h4 style="margin-top: 0; margin-bottom: 10px;">🤖 Why Health Gym? (The Magic of GANs)</h4>
  <p style="margin: 0; font-size: 0.95em;">The Health Gym project solves the ultimate AI healthcare dilemma: patient privacy. These datasets are <strong>100% synthetic</strong>, generated using advanced Generative Adversarial Networks (GANs). They perfectly preserve the statistical properties, variable correlations, and temporal dynamics of real clinical data, with zero risk of patient re-identification!</p>
</div>

### 🗂️ Choose Your Arena (Available Datasets)

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin: 30px 0;">

  <div style="flex: 1 1 300px; background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.2); border-top: 4px solid #00C9FF; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.05);">
    <h3 style="margin-top: 0;">📉 1. Acute Hypotension</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> Management of low blood pressure in ICU patients.</p>
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Variables (22):</strong> Vital Signs (MAP, BP), Lab Results, Respiratory metrics, GCS score.</li>
      <li><strong>Treatments (Actions):</strong> Fluid boluses (5 categories), Vasopressors (5 categories).</li>
      <li><strong>Structure:</strong> 48 hourly time points (48-hour window).</li>
      <li><strong>Size:</strong> 3,910 synthetic patients (21.7 MB).</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #008eb3;"><strong>🎯 Mission:</strong> Optimize fluid and vasopressor administration to maintain adequate blood pressure while minimizing adverse effects.</p>
  </div>

  <div style="flex: 1 1 300px; background: rgba(255, 107, 107, 0.05); border: 1px solid rgba(255, 107, 107, 0.2); border-top: 4px solid #FF6B6B; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(255, 107, 107, 0.05);">
    <h3 style="margin-top: 0;">🦠 2. Sepsis Management</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> ICU management of a life-threatening response to infection.</p>
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Variables (46):</strong> Demographics, Vital Signs, Lab Results, Coagulation metrics.</li>
      <li><strong>Treatments (Actions):</strong> IV fluid inputs, Max vasopressor dose, Mechanical ventilation.</li>
      <li><strong>Structure:</strong> Up to 20 time points (4-hour windows; max 80 hours).</li>
      <li><strong>Size:</strong> 2,164 synthetic patients (16 MB).</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #d64545;"><strong>🎯 Mission:</strong> Develop optimal policies for fluid resuscitation and vasopressor therapy to improve survival and health states.</p>
  </div>

  <div style="flex: 1 1 300px; background: rgba(155, 93, 229, 0.05); border: 1px solid rgba(155, 93, 229, 0.2); border-top: 4px solid #9B5DE5; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(155, 93, 229, 0.05);">
    <h3 style="margin-top: 0;">🧬 3. HIV Antiretroviral Therapy</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> Management of HIV infection via ART in ambulatory care.</p>
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Variables (15):</strong> Demographics, Disease Markers (Viral Load, CD4 count).</li>
      <li><strong>Treatments (Actions):</strong> Base drug combinations, INI, NNRTI, Extra PI, Extra pk-En.</li>
      <li><strong>Structure:</strong> 60 monthly time points (5-year period).</li>
      <li><strong>Size:</strong> 8,916 synthetic patients (44.7 MB).</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #7b42b5;"><strong>🎯 Mission:</strong> Optimize ART regimens to suppress viral load, maintain healthy CD4 counts, and minimize side effects over time.</p>
  </div>

</div>

---

### 🔑 How to Access the Datasets
Grabbing the data is completely free and requires zero restrictive data use agreements!
1. 🌐 **Official Website:** Visit **[healthgym.ai](https://healthgym.ai)** to download datasets and read comprehensive documentation.
2. 🫀 **PhysioNet:** The Acute Hypotension and Sepsis sets are also hosted on the legendary **[PhysioNet repository](https://physionet.org/)**.
3. 📊 **Format:** All files are provided as clean **CSV files** ready for Python, R, or MATLAB.
4. 💻 **GitHub Repo:** Need a head start? Check out official code examples and tutorials **[right here](https://github.com/Nic5472K/ScientificData2021_HealthGym)**.

<div style="background: rgba(255, 213, 79, 0.1); border-left: 5px solid #FFD54F; padding: 20px; border-radius: 8px; margin-top: 30px;">
  <h4 style="margin-top: 0; margin-bottom: 10px;">📌 Mandatory Citation</h4>
  <p style="margin: 0; font-size: 0.9em; font-style: italic;">Teams must properly cite the Health Gym creators in their technical reports:</p>
  <blockquote style="margin: 10px 0 0 0; font-size: 0.9em; border-left: 3px solid #ccc; padding-left: 10px;">
    Kuo, N.I., Polizzotto, M.N., Finfer, S., Garcia, F., Sönnerborg, A., Zazzi, M., Böhm, M., Jorm, L., & Barbieri, S. (2022). The Health Gym: Synthetic Health-Related Datasets for the Development of Reinforcement Learning Algorithms. Scientific Data, 9(1). arXiv:2203.06369
  </blockquote>
</div>
