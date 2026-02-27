---
layout: single
title: "International Data Science Challenge 2026"
permalink: /
author_profile: false
header:
  overlay_image: "https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-1.2.1&auto=format&fit=crop&w=2000&q=80"
  overlay_filter: "rgba(13, 17, 23, 0.85)"
--- 

<div style="text-align: center; margin-bottom: 3em;">
  <h2 style="font-weight: 900; font-size: 2.5em; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">Ready to Hack the Future of Healthcare? 🏥⚡</h2>
  <p style="font-size: 1.2em; line-height: 1.6; opacity: 0.9;">
    Welcome to the ultimate data showdown! Hosted by <strong>UPM (Malaysia)</strong>, and teaming up with <strong>UNAIR</strong>, <strong>UNMUL</strong>, and <strong>UB (Indonesia)</strong>, this fully online global challenge is your arena. Prove that math, data, and code can actually change the world. 
  </p>
</div>

<div style="text-align: center; margin: 0 0 40px 0;">
  <img src="/images/idsc2026poster.png" alt="IDSC 2026 Official Poster" style="max-width: 100%; height: auto; border-radius: 12px; box-shadow: 0 8px 24px rgba(0,201,255,0.15); border: 1px solid rgba(0, 201, 255, 0.2);">
</div>

<div id="idsc-countdown-container" style="margin: 40px 0; text-align: center; font-family: 'Courier New', Courier, monospace;">
  <p style="text-transform: uppercase; letter-spacing: 2px; font-weight: bold; margin-bottom: 15px; font-size: 0.9em; color: #00C9FF;">
    > SYSTEM_LOCK: 10 March 2026
  </p>
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <div style="background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="days" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Days</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="hours" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Hours</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="minutes" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Mins</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px;">
      <span id="seconds" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">--</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Secs</span>
    </div>
  </div>
</div>

### 🎯 The Mission: Math Meets Hope
We believe math isn't just numbers on a whiteboard—it's the ultimate toolkit for finding hope hidden in the data. Your directive? **Mathematics for Hope in Healthcare**. You will tackle real-world clinical dilemmas using cutting-edge machine learning, deep learning, and advanced statistical modeling.

### 💻 The Challenge: Code to Save Lives
Step into the shoes of an AI clinician! Healthcare impact often depends on spotting risk patterns in physiological signals and medical imaging before a human eye can. But biomedical data is messy, noisy, and highly sensitive. Your challenge is to build models that aren't just highly accurate, but transparent, reproducible, and actually useful in the real world.

**The Dataset Directives:** Teams must use **at least one** of the official datasets listed below, hosted directly on [PhysioNet](https://physionet.org/). *External labeled datasets are strictly prohibited.* Everyone fights in the same arena, regardless of the dataset you pick.

#### Pick Your Poison (The Datasets):
Choose your modality and lock in your modeling objective (e.g., classification, segmentation, signal decoding, or risk prediction):

1. **[bigP3BCI](https://physionet.org/content/bigp3bci/1.0.0/) (P300-based Brain–Computer Interface)** 🧠
   * **The Data:** EEG signals and event markers (EDF+ format).
   * **The Mission:** P300 detection, BCI decoding, or cross-session generalization.
   

2. **[Brugada-HUCA](https://physionet.org/content/brugada-huca/1.0.0/) (12-Lead ECG for Brugada Syndrome)** ❤️
   * **The Data:** 12-lead ECG recordings (WFDB format).
   * **The Mission:** Classify Brugada syndrome vs. Normal controls. 
   

3. **[Myocardial Perfusion SPECT](https://physionet.org/content/myocardial-perfusion-spect/1.0.0/)** ☢️
   * **The Data:** Cardiac nuclear imaging / Rest SPECT (DICOM + NIfTI masks).
   * **The Mission:** Medical image analysis, segmentation of the left ventricular wall, or preprocessing/QA.
   

4. **[HYGD](https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.0.0/) (Hillel Yaffe Glaucoma Dataset)** 👁️
   * **The Data:** Retinal fundus images (JPG + Labels.csv).
   * **The Mission:** Glaucomatous optic neuropathy (GON) detection and quality-aware modeling.
   

**Your Final Payload (Deliverables):**
* 🛠️ **The Method:** A validated pipeline with strict train/val/test splits.
* 🔍 **The Insights:** Interpretable outputs (e.g., saliency/heatmaps for images, feature importance).
* 🗣️ **The Impact:** A real-world discussion on ethics, limitations, and how your model sparks *"hope"* in clinics.
* 📦 **The Repo:** Beautifully documented preprocessing for absolute reproducibility.

<div style="display: flex; gap: 20px; flex-wrap: wrap; margin: 30px 0;">
  <div style="flex: 1; min-width: 300px; background: rgba(0, 201, 255, 0.05); border: 1px solid rgba(0, 201, 255, 0.2); border-left: 6px solid #00C9FF; padding: 25px; border-radius: 10px;">
    <h3 style="margin-top: 0; color: #00C9FF;">🏆 The Prize Pool</h3>
    <p style="margin-top: 0; font-size: 0.9em; opacity: 0.8;">RM 1,000.00 Total Payload!</p>
    <ul style="list-style-type: none; padding-left: 0; font-size: 1.1em;">
      <li style="margin-bottom: 8px;">🥇 <strong>Champion:</strong> RM 500.00</li>
      <li style="margin-bottom: 8px;">🥈 <strong>1st Runner Up:</strong> RM 300.00</li>
      <li style="margin-bottom: 8px;">🥉 <strong>2nd Runner Up:</strong> RM 150.00</li>
    </ul>
  </div>

  <div style="flex: 1; min-width: 300px; background: rgba(146, 254, 157, 0.05); border: 1px solid rgba(146, 254, 157, 0.2); border-left: 6px solid #92FE9D; padding: 25px; border-radius: 10px;">
    <h3 style="margin-top: 0; color: #92FE9D;">🌟 Player Perks</h3>
    <p style="margin-top: 0; font-size: 0.9em; opacity: 0.8;">For all registered squads</p>
    <ul style="list-style-type: none; padding-left: 0; font-size: 1.1em;">
      <li style="margin-bottom: 8px;">📜 <strong>E-Certificates:</strong> Official proof of your grind.</li>
      <li style="margin-bottom: 8px;">💡 <strong>Exclusive Workshops (with E-Cerificates):</strong> Level up your data science and pitching skills with industry pros.</li>
    </ul>
  </div>
</div>

### 🗓️ Roadmap to the Grand Final
* **🏁 25 Feb:** System Online & Registration Opens
* **⏳ 10 Mar:** Registration Lock-in Deadline
* **🎉 14 Mar:** Intl. Mathematics Day Celebration & Workshops
* **📤 25 Mar:** Stage 1 Deadline (Code & Pitch Drop)
* **🔥 11 Apr:** Stage 2 Grand Final & Winner Reveal

<div style="text-align: center; margin: 50px 0;">
  <a href="https://forms.gle/MFqXpuuk9rT2yF9d6" style="display: inline-block; padding: 20px 50px; font-size: 1.5em; color: #0d1117; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); border-radius: 50px; text-decoration: none; font-weight: 900; text-transform: uppercase; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.4); transition: transform 0.2s;">
    🚀 Initialize Registration
  </a>
</div>

<script>
function startCountdown() {
  const targetDate = new Date("2026-03-10T23:59:59+08:00").getTime();
  
  function updateTimer() {
    const now = new Date().getTime();
    const diff = targetDate - now;
    
    if (diff < 0) {
      document.getElementById("idsc-countdown-container").innerHTML = "<h3 style='color: #ff4757; font-family: monospace;'>[ REGISTRATION OFFLINE ]</h3>";
      return true;
    }
    
    const d = Math.floor(diff / (1000 * 60 * 60 * 24));
    const h = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const m = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
    const s = Math.floor((diff % (1000 * 60)) / 1000);
    
    document.getElementById("days").innerText = d.toString().padStart(2, '0');
    document.getElementById("hours").innerText = h.toString().padStart(2, '0');
    document.getElementById("minutes").innerText = m.toString().padStart(2, '0');
    document.getElementById("seconds").innerText = s.toString().padStart(2, '0');
    
    return false;
  }

  const isClosed = updateTimer();
  
  if (!isClosed) {
    const timerInterval = setInterval(function() {
      if (updateTimer()) {
        clearInterval(timerInterval);
      }
    }, 1000);
  }
}

if (document.readyState === 'loading') {
  document.addEventListener('DOMContentLoaded', startCountdown);
} else {
  startCountdown();
}
</script>
