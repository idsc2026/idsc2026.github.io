---
layout: archive
title: "The Data: PhysioNet 🫀"
permalink: /datasets/
author_profile: false
---

To hack healthcare, you need the right data. For IDSC 2026, our theme is **Mathematics and Hope in Healthcare**. Participants **must** use dataset(s) from the official **PhysioNet** platform listed below. You have complete flexibility to choose the dataset that best aligns with your team's computational strengths, whether that's signal processing, computer vision, or time-series classification. 

*(Note: External labeled datasets are strictly prohibited. You must train your models using only the provided official datasets.)*

<div style="background: rgba(146, 254, 157, 0.1); border-left: 5px solid #92FE9D; padding: 20px; border-radius: 8px; margin: 25px 0;">
  <h4 style="margin-top: 0; margin-bottom: 10px;">🩺 Why PhysioNet? (Real Data, Real Hope)</h4>
  <p style="margin: 0; font-size: 0.95em;">Unlike perfectly clean synthetic datasets, biomedical data in the real world is noisy, heterogeneous, and sensitive to bias. By using PhysioNet's open-access medical databases, you are tackling real-world clinical dilemmas. Your challenge is to build computational models that are accurate, transparent, reproducible, and clinically meaningful enough to provide <em>hope</em> through earlier screening and better decision support!</p>
</div>

### 🗂️ Choose Your Arena (Official Datasets)

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin: 30px 0;">

  <div style="flex: 1 1 300px; background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.2); border-top: 4px solid #00C9FF; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.05);">
    <h3 style="margin-top: 0;">🧠 1. bigP3BCI</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> P300-based Brain–Computer Interface (BCI) speller studies.</p>
    
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Modality:</strong> EEG signals (+ optional eye-tracking).</li>
      <li><strong>Format:</strong> EDF+ standard format.</li>
      <li><strong>Details:</strong> Standardized structure aligned with emerging IEEE P2731 terminology. Includes event markers, demographics, and ALS status.</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #008eb3;"><strong>🎯 Mission:</strong> P300 detection, BCI decoding, and cross-session generalization.</p>
  </div>

  <div style="flex: 1 1 300px; background: rgba(255, 107, 107, 0.05); border: 1px solid rgba(255, 107, 107, 0.2); border-top: 4px solid #FF6B6B; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(255, 107, 107, 0.05);">
    <h3 style="margin-top: 0;">❤️ 2. Brugada-HUCA</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> 12-lead ECG recordings for Brugada syndrome study.</p>
    
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Modality:</strong> 12-lead ECG (100 Hz, 12-second strips).</li>
      <li><strong>Format:</strong> WFDB format (.dat/.hea) + CSV metadata.</li>
      <li><strong>Details:</strong> 363 subjects total (76 Brugada, 287 normal controls), expert-reviewed.</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #d64545;"><strong>🎯 Mission:</strong> Binary classification of Brugada syndrome versus Normal controls.</p>
  </div>

  <div style="flex: 1 1 300px; background: rgba(155, 93, 229, 0.05); border: 1px solid rgba(155, 93, 229, 0.2); border-top: 4px solid #9B5DE5; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(155, 93, 229, 0.05);">
    <h3 style="margin-top: 0;">☢️ 3. Myocardial Perfusion SPECT</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> Rest myocardial perfusion scintigraphy image database.</p>
    
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Modality:</strong> Cardiac nuclear imaging.</li>
      <li><strong>Format:</strong> DICOM images + NIfTI volumes/masks.</li>
      <li><strong>Details:</strong> 3D volumes intended to support advanced medical image analysis research.</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #7b42b5;"><strong>🎯 Mission:</strong> Volume segmentation (e.g., left ventricular wall masks) and image preprocessing/QA.</p>
  </div>

  <div style="flex: 1 1 300px; background: rgba(255, 183, 3, 0.05); border: 1px solid rgba(255, 183, 3, 0.2); border-top: 4px solid #FFB703; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(255, 183, 3, 0.05);">
    <h3 style="margin-top: 0;">👁️ 4. Hillel Yaffe Glaucoma (HYGD)</h3>
    <p style="font-size: 0.9em; opacity: 0.9;"><strong>Context:</strong> Gold-standard annotated fundus dataset for eye disease.</p>
    
    <ul style="font-size: 0.85em; padding-left: 20px;">
      <li><strong>Modality:</strong> Retinal fundus images.</li>
      <li><strong>Format:</strong> JPG images + `Labels.csv`.</li>
      <li><strong>Details:</strong> Glaucomatous optic neuropathy (GON) labels based on comprehensive ophthalmic examination. Includes image quality scores.</li>
    </ul>
    <p style="font-size: 0.85em; margin-bottom: 0; color: #cc9202;"><strong>🎯 Mission:</strong> Glaucoma (GON) detection and quality-aware medical computer vision modeling.</p>
  </div>

</div>

---

### 🛠️ How to Access Data & Recommended Tools
1. 🌐 **PhysioNet Access:** Visit the official pages to follow the download instructions:
   * [bigP3BCI](https://physionet.org/content/bigp3bci/1.0.0/)
   * [Brugada-HUCA](https://physionet.org/content/brugada-huca/1.0.0/)
   * [Myocardial Perfusion SPECT](https://physionet.org/content/myocardial-perfusion-spect/1.0.0/)
   * [HYGD](https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.0.0/)
2. 💻 **Data Tooling:** Make sure your team utilizes the right libraries for these specialized formats!
   * **EEG/ECG:** `WFDB` (for Brugada), `MNE-Python` (for bigP3BCI).
   * **Imaging:** `pydicom`, `nibabel`, `SimpleITK`, or `MONAI` (for SPECT and HYGD).
   * **Core Stack:** Python, scikit-learn, PyTorch/TensorFlow.
3. 🔄 **Reproducibility:** You MUST rigorously document your data loading, preprocessing steps, and train/val/test splits in your final code repository.

<div style="background: rgba(255, 213, 79, 0.1); border-left: 5px solid #FFD54F; padding: 20px; border-radius: 8px; margin-top: 30px;">
  <h4 style="margin-top: 0; margin-bottom: 10px;">📌 Mandatory Citation Policy</h4>
  <p style="margin: 0; font-size: 0.9em; font-style: italic;">To ensure open-source integrity, all submissions <strong>MUST</strong> contain two types of citations:</p>
  <ul style="margin: 10px 0 0 0; font-size: 0.9em;">
    <li><strong>1. The Dataset Citation:</strong> You must cite the specific dataset(s) you chose. The exact citation string can be found at the bottom of each dataset's PhysioNet page.</li>
    <li><strong>2. The Platform Citation:</strong> You must cite the PhysioNet platform itself, as requested on their website.</li>
  </ul>
</div>
