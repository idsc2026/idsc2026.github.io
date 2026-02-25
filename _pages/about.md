---
layout: single
title: "International Data Science Challenge 2026"
permalink: /
author_profile: false
header:
  overlay_image: "https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-1.2.1&auto=format&fit=crop&w=2000&q=80"
  overlay_filter: "rgba(43, 24, 84, 0.75)"
--- 

<div style="text-align: center; margin-bottom: 3em;">
  <h2 style="font-weight: bold;">Are you ready to hack the future of healthcare? 🏥✨</h2>
  <p style="font-size: 1.2em; line-height: 1.6;">
    Welcome to the ultimate data showdown! Hosted by <strong>UPM (Malaysia)</strong>, in partnership with <strong>Universitas Airlangga (Indonesia)</strong>, <strong>Universitas Mulawarman (Indonesia)</strong>, and <strong>Universitas Brawijaya (Indonesia)</strong>, this fully online challenge is your chance to prove that math and code can truly change the world.
  </p>
</div>

<div id="idsc-countdown-container" style="margin: 40px 0; text-align: center; font-family: sans-serif;">
  <p style="text-transform: uppercase; letter-spacing: 2px; font-weight: bold; margin-bottom: 15px; font-size: 0.9em; opacity: 0.8;">
    ⏳ Registration Deadline: 10 March 2026
  </p>
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="days" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Days</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="hours" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Hours</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="minutes" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Mins</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="seconds" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Secs</span>
    </div>
  </div>
</div>

### 🎯 The Vibe: Mathematics & Hope
We believe math isn't just about numbers, it's about finding hope in the data. Your mission? **Mathematics for Hope in Healthcare**. You will tackle real-world clinical dilemmas using cutting-edge machine learning, deep learning, and advanced statistical modeling.

### 💻 The Challenge: Save Lives with Code
Step into the shoes of an AI clinician! Healthcare impact often depends on timely recognition of risk patterns in physiological signals and medical imaging. However, biomedical data is noisy, heterogeneous, and sensitive to bias. You are challenged to build models that are not only accurate but transparent, reproducible, and clinically meaningful.

**The Data Rules:** Teams must use **at least one** of the official datasets listed below, hosted on [PhysioNet](https://physionet.org/). *External labeled datasets are strictly prohibited.* All teams will compete in a single track, regardless of the dataset chosen.

#### The Official Datasets:
Choose your modality and define your modeling objective (e.g., classification, segmentation, signal decoding, or risk prediction):

1. **[bigP3BCI](https://physionet.org/content/bigp3bci/1.0.0/) (P300-based Brain–Computer Interface)** 🧠
   * **Modality:** EEG signals and event markers (EDF+ format).
   * **Task:** P300 detection, BCI decoding, or cross-session generalization.
   

2. **[Brugada-HUCA](https://physionet.org/content/brugada-huca/1.0.0/) (12-Lead ECG for Brugada Syndrome)** ❤️
   * **Modality:** 12-lead ECG recordings (WFDB format).
   * **Task:** Classify Brugada syndrome vs. Normal controls. 
   

3. **[Myocardial Perfusion SPECT](https://physionet.org/content/myocardial-perfusion-spect/1.0.0/)** ☢️
   * **Modality:** Cardiac nuclear imaging / Rest SPECT (DICOM + NIfTI masks).
   * **Task:** Medical image analysis, segmentation of the left ventricular wall, or preprocessing/QA.
   

4. **[HYGD](https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.0.0/) (Hillel Yaffe Glaucoma Dataset)** 👁️
   * **Modality:** Retinal fundus images (JPG + Labels.csv).
   * **Task:** Glaucomatous optic neuropathy (GON) detection and quality-aware modeling.
   

**Your Deliverables:**
* A validated method with proper train/validation/test splits.
* Interpretable insights (e.g., saliency/heatmaps for images, feature importance for metadata).
* A discussion on ethical considerations, limitations, and how your solution contributes to *"hope"* (e.g., earlier screening, reduced diagnostic burden).
* Documented preprocessing for absolute reproducibility.

<div style="display: flex; gap: 20px; flex-wrap: wrap; margin: 30px 0;">
  <div style="flex: 1; min-width: 300px; background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.2); border-left: 6px solid #00C9FF; padding: 25px; border-radius: 10px;">
    <h3 style="margin-top: 0;">🏆 The Prize Pool</h3>
    <p style="margin-top: 0; font-size: 0.9em; opacity: 0.8;">RM 1,000.00 Total!</p>
    <ul style="list-style-type: none; padding-left: 0; font-size: 1.1em;">
      <li style="margin-bottom: 8px;">🥇 <strong>Champion:</strong> RM 500.00</li>
      <li style="margin-bottom: 8px;">🥈 <strong>1st Runner Up:</strong> RM 300.00</li>
      <li style="margin-bottom: 8px;">🥉 <strong>2nd Runner Up:</strong> RM 150.00</li>
    </ul>
  </div>

  <div style="flex: 1; min-width: 300px; background: rgba(146, 254, 157, 0.1); border: 1px solid rgba(146, 254, 157, 0.2); border-left: 6px solid #92FE9D; padding: 25px; border-radius: 10px;">
    <h3 style="margin-top: 0;">🌟 Participant Perks</h3>
    <p style="margin-top: 0; font-size: 0.9em; opacity: 0.8;">For all registered teams</p>
    <ul style="list-style-type: none; padding-left: 0; font-size: 1.1em;">
      <li style="margin-bottom: 8px;">📜 <strong>E-Certificates:</strong> Official recognition for all participants.</li>
      <li style="margin-bottom: 8px;">💡 <strong>Free Workshops:</strong> Gain exclusive access to expert-led data science and presentation skills training.</li>
    </ul>
  </div>
</div>

### 🗓️ Roadmap to the Grand Final
* **🏁 25 Feb:** Official Launch & Registration Opens
* **⏳ 10 Mar:** Registration Deadline
* **🎉 14 Mar:** Intl. Mathematics Day Celebration & Workshops
* **📤 25 Mar:** Stage 1 Deadline
* **🔥 11 Apr:** Stage 2 Grand Final & Closing Ceremony

<div style="text-align: center; margin: 50px 0;">
  <a href="https://forms.gle/MFqXpuuk9rT2yF9d6" style="display: inline-block; padding: 20px 50px; font-size: 1.5em; color: white; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); border-radius: 50px; text-decoration: none; font-weight: bold; text-transform: uppercase;">
    🚀 Register Your Team Now
  </a>
</div>

<script>
window.addEventListener('DOMContentLoaded', (event) => {
  const targetDate = new Date("2026-03-10T23:59:59").getTime();
  const timer = setInterval(function() {
    const now = new Date().getTime();
    const diff = targetDate - now;
    if (diff < 0) {
      clearInterval(timer);
      document.getElementById("idsc-countdown-container").innerHTML = "<h3>Registration Closed!</h3>";
      return;
    }
    const d = Math.floor(diff / (1000 * 60 * 60 * 24));
    const h = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const m = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
    const s = Math.floor((diff % (1000 * 60)) / 1000);
    document.getElementById("days").innerText = d.toString().padStart(2, '0');
    document.getElementById("hours").innerText = h.toString().padStart(2, '0');
    document.getElementById("minutes").innerText = m.toString().padStart(2, '0');
    document.getElementById("seconds").innerText = s.toString().padStart(2, '0');
  }, 1000);
});
</script>
