---
layout: single
title: "International Data Science Challenge 2026"
permalink: /
author_profile: false
header:
  overlay_image: "https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-1.2.1&auto=format&fit=crop&w=2000&q=80"
  overlay_filter: "rgba(43, 24, 84, 0.75)" # A sleek, modern deep purple overlay
---

<img src="/images/idsc-poster.png" alt="IDSC 2026 Official Poster" style="width:100%; max-width:800px; display:block; margin: 0 auto 30px auto; border-radius: 12px; box-shadow: 0 8px 16px rgba(0,0,0,0.15);">

<div style="text-align: center; margin-bottom: 3em;">
  <h2 style="font-weight: bold;">Are you ready to hack the future of healthcare? 🏥✨</h2>
  <p style="font-size: 1.2em; line-height: 1.6;">
    Welcome to the ultimate data showdown! Hosted by <strong>Universiti Putra Malaysia (UPM)</strong>, in partnership with <strong>Universitas Airlangga (UNAIR)</strong> and <strong>Universitas Mulawarman (UNMUL)</strong>, this fully online challenge is your chance to prove that math and code can truly change the world.
  </p>
</div>

<div id="idsc-countdown-container" style="margin: 40px 0; text-align: center; font-family: 'Inter', sans-serif;">
  <p style="text-transform: uppercase; letter-spacing: 2px; font-weight: bold; margin-bottom: 15px; font-size: 0.9em; opacity: 0.8;">
    ⏳ Registration Deadline: 10 March 2026
  </p>
  
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.1);">
      <span id="days" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">00</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Days</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.1);">
      <span id="hours" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">00</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Hours</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.1);">
      <span id="minutes" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">00</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Mins</span>
    </div>
    <div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.3); padding: 15px; border-radius: 12px; min-width: 80px; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.1);">
      <span id="seconds" style="display: block; font-size: 2.5em; font-weight: 900; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">00</span>
      <span style="font-size: 0.7em; text-transform: uppercase; font-weight: bold; opacity: 0.7;">Secs</span>
    </div>
  </div>
</div>

<script>
  // Set the target: 10 March 2026, 23:59:59 (GMT+8)
  const countDownDate = new Date("March 10, 2026 23:59:59").getTime();

  const x = setInterval(function() {
    const now = new Date().getTime();
    const distance = countDownDate - now;

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    document.getElementById("days").innerHTML = days.toString().padStart(2, '0');
    document.getElementById("hours").innerHTML = hours.toString().padStart(2, '0');
    document.getElementById("minutes").innerHTML = minutes.toString().padStart(2, '0');
    document.getElementById("seconds").innerHTML = seconds.toString().padStart(2, '0');

    if (distance < 0) {
      clearInterval(x);
      document.getElementById("idsc-countdown-container").innerHTML = "<h3 style='color: #FF6B6B;'>🚀 Registration Closed! See you in the competition!</h3>";
    }
  }, 1000);
</script>

### 🎯 The Vibe: Mathematics & Hope
We believe math isn't just about numbers—it's about finding hope in the data. Your mission? **Mathematics for Hope in Healthcare**. You will tackle real-world clinical dilemmas using cutting-edge reinforcement learning, machine learning, and advanced statistical modeling to optimize personalized treatments for conditions like sepsis and HIV. 

### 💻 The Challenge: Save Lives with Code
Step into the shoes of an AI clinician! 🩺
* **The Data:** Dive into the official **[Health Gym collection](https://healthgym.ai)**—highly realistic, privacy-preserving synthetic health datasets. 
* **The Mission:** Develop algorithms that recommend the ultimate treatment sequences, dosages, and timings.
* **The Impact:** Flex your analytical skills, collaborate across borders, and prove that ethical AI can revolutionize patient care.

<div style="background: rgba(0, 201, 255, 0.1); border: 1px solid rgba(0, 201, 255, 0.2); border-left: 6px solid #00C9FF; padding: 25px; border-radius: 10px; margin: 30px 0; box-shadow: 0 4px 15px rgba(0, 201, 255, 0.1);">
  <h3 style="margin-top: 0;">🏆 The Prize Pool (RM 1,000.00 Total!)</h3>
  <p>Bring your A-game, pitch your solution, and take home the glory (plus an E-Certificate for every competitor):</p>
  <ul style="list-style-type: none; padding-left: 0; font-size: 1.1em;">
    <li style="margin-bottom: 8px;">🥇 <strong>Champion:</strong> RM 500.00</li>
    <li style="margin-bottom: 8px;">🥈 <strong>1st Runner Up:</strong> RM 300.00</li>
    <li style="margin-bottom: 8px;">🥉 <strong>2nd Runner Up:</strong> RM 150.00</li>
    <li>🏅 <strong>Consolation (x2):</strong> RM 25.00</li>
  </ul>
</div>

### 🗓️ Roadmap to the Grand Final
Mark your calendars—don't miss a beat! ⏰

* **🏁 25 Feb:** Official Launch & Registration Opens
* **⏳ 10 Mar:** Registration Deadline
* **🎉 14 Mar:** **Intl. Mathematics Day Celebration & Level-Up Workshops**
  * 🧠 *Data Science/ML Workshop* — Assoc. Prof. Dr. Shukor Sanim Mohd Fauzi (UiTM)
  * 🎤 *Presentation Skills Workshop* — Dr. Ghazila Binti Ghazi (UPM)
* **📤 25 Mar:** Stage 1 Deadline (Submit your Tech Report, Video Pitch & Code)
* **🌟 02 Apr:** Top 5 Finalists Announced
* **🔥 11 Apr:** Stage 2 Grand Final (Live Pitches!), Winner Announcement & Closing Ceremony

---

<div style="text-align: center; margin: 50px 0;">
  <p style="font-size: 1.1em; margin-bottom: 20px;"><em>Got your squad ready? Check the Guidelines & Rules tab at the top, then hit the button below!</em></p>
  <a href="YOUR_LINK_HERE" style="display: inline-block; padding: 20px 50px; font-size: 1.5em; color: white; background: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%); border-radius: 50px; text-decoration: none; font-weight: bold; box-shadow: 0 10px 20px rgba(0, 201, 255, 0.4); text-transform: uppercase; letter-spacing: 1px;">
    🚀 Register Your Team Now
  </a>
</div>
