---
layout: archive
title: "Guidelines & Rules 📜"
permalink: /rules/
author_profile: false
---

The challenge happens 100% online across two epic stages. Read up on the mechanics, how you will be scored, and the ground rules to make sure your team is ready to dominate! 🚀

### 🗺️ The Game Plan (Competition Structure)

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin: 30px 0;">
  
  <div style="flex: 1 1 300px; background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.2); border-top: 4px solid #00C9FF; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.05);">
    <h4 style="margin-top: 0;">🛠️ Stage 1: The Build (Asynchronous)</h4>
    <p><strong>Deadline:</strong> 25 March 2026</p>
    <p>Submit your project via the official portal:</p>
    <ul style="font-size: 0.95em;">
      <li>📄 <strong>Tech Report (Max 5 pages):</strong> Detail your problem statement, dataset justification, ML/DL methodology, preprocessing steps, results, interpretability, and clinical impact.</li>
      <li>🎥 <strong>Video Pitch (Max 3 mins):</strong> Sell your solution! Explain how your mathematical/computational solution brings "hope" to healthcare.</li>
      <li>💻 <strong>Code Repo (Recommended):</strong> Link your GitHub/GitLab with reproducible code so we can review your magic.</li>
    </ul>
    <p style="font-size: 0.85em; opacity: 0.8; margin-bottom: 0;"><em>*Judges will shortlist the Top 5 teams based on technical rigor, innovation, interpretability, and clinical relevance.</em></p>
  </div>

  <div style="flex: 1 1 300px; background: rgba(146, 254, 157, 0.05); border: 1px solid rgba(146, 254, 157, 0.2); border-top: 4px solid #92FE9D; padding: 20px; border-radius: 10px; box-shadow: 0 4px 15px rgba(146, 254, 157, 0.05);">
    <h4 style="margin-top: 0;">🔥 Stage 2: The Grand Final (Synchronous)</h4>
    <p><strong>Date:</strong> 11 April 2026</p>
    <p>The Top 5 teams will battle it out live!</p>
    <ul style="font-size: 0.95em;">
      <li>🌐 <strong>Format:</strong> Live Pitch via Zoom/Webex.</li>
      <li>⏱️ <strong>Duration:</strong> 10 mins presentation + 5 mins Q&A.</li>
      <li>🎯 <strong>Focus:</strong> Prove your model's clinical applicability, safety, interpretability, reproducibility, and real-world impact.</li>
    </ul>
  </div>

</div>

---

### 📊 How to Win (Evaluation Criteria)

Wondering how the judges will score your project? Here is the exact breakdown of the 100-point rubric:

| Criterion | Weight (%) |
| :--- | :---: |
| 🧠 **Problem Definition & Healthcare Relevance** | 15 |
| 🧮 **Mathematical/Algorithmic Rigor** | 25 |
| 📈 **Model Performance & Validation** | 20 |
| 💡 **Innovation & Creativity** | 15 |
| 🛡️ **Clinical Interpretability & Safety** | 10 |
| 🌟 **"Hope" Impact & Practical Implications** | 10 |
| 🗣️ **Presentation Quality & Clarity** | 5 |
| **Total Score** | **100** |

---

### ⚖️ The Ground Rules

Play fair and code hard. Ensure your team follows these regulations to avoid disqualification:

1. 🚫 **No Plagiarism:** Your project must be 100% original work created specifically for this challenge.
2. 📂 **Strict Dataset Compliance:** You *must* exclusively use one (or more) of the official datasets from the [PhysioNet](https://physionet.org/) list provided (bigP3BCI, Brugada-HUCA, Myocardial Perfusion SPECT, or HYGD). External labeled datasets are strictly not permitted.
3. 📚 **Cite Your Sources (REQUIRED):** All submissions must properly cite the specific dataset(s) used (using the official text on each dataset's page) **AND** include the standard PhysioNet platform citation.
4. 🤖 **Ethical AI Only:** Your models need to adhere to strict ethical principles:
   * Prioritize model interpretability and explainability (e.g., saliency maps, feature importance).
   * Include safety validations and consider potential harms.
   * Include an honest discussion of your model's limitations, data leakage prevention, and failure modes.
   * Plan for responsible deployment.
5. 🔓 **Open Source (Encouraged):** While optional, we highly encourage sharing your code for transparency and reproducibility.
6. ⏰ **No Late Submissions:** The Stage 1 deadline is absolute. Submissions received after the cutoff will not be reviewed.
7. 🧑‍⚖️ **Judges' Word is Final:** The decision of the judging panel cannot be contested.
8. 🤝 **Squad Loyalty:** Your team composition must remain exactly the same from registration through the finals.

---

### 💻 Tech Specs & Tools

Bring your favorite stack! You have complete freedom over your tech, but here is what we recommend based on the datasets:

* **Programming Languages:** Python 🐍 (highly recommended), R, MATLAB, or Julia.
* **Core Scientific Stack:** NumPy, Pandas, SciPy, scikit-learn, PyTorch, TensorFlow, or Keras.
* **Physiological Signal Tooling (EEG/ECG):** * `WFDB` (for ECG in WFDB format)
  * `MNE-Python` (for EEG/ERP workflows)
* **Medical Imaging Tooling (DICOM/NIfTI):**
  * `pydicom` (for DICOM images)
  * `nibabel` / `SimpleITK` (for NIfTI and medical image IO)
  * `MONAI` (Deep learning framework for medical imaging - optional but powerful)
* **Hardware:** You are in charge of your own compute! Free cloud platforms like Google Colab or Kaggle Notebooks are perfect for initial prototyping. Deep learning on medical images (SPECT/Fundus) may benefit from GPU acceleration.

---

### 📚 Official Learning Resources

Get familiar with the data before you start coding:
* **The Platform:** [PhysioNet](https://physionet.org/)
* **Dataset 1 (EEG):** [bigP3BCI Documentation](https://physionet.org/content/bigp3bci/1.0.0/)
* **Dataset 2 (ECG):** [Brugada-HUCA Documentation](https://physionet.org/content/brugada-huca/1.0.0/)
* **Dataset 3 (SPECT):** [Myocardial Perfusion SPECT Documentation](https://physionet.org/content/myocardial-perfusion-spect/1.0.0/)
* **Dataset 4 (Fundus):** [HYGD (Glaucoma) Documentation](https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.0.0/)

*Tip: Brush up on segmentation validation methodologies (Dice score, Hausdorff distance) if tackling imaging, and signal robustness best practices if analyzing EEG/ECG!*
