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
  <h2 style="font-weight: 900; font-size: 2.8em; background: linear-gradient(90deg, #FFD700 0%, #FF8C00 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; text-transform: uppercase; letter-spacing: 2px;">Will You Be the 2026 Champion? 🏆</h2>
  <p style="font-size: 1.3em; line-height: 1.6; color: #fff; font-weight: 300;">
    The arena is set. Hosted by <strong>UPM (Malaysia)</strong> with <strong>UNAIR, UNMUL, and UB (Indonesia)</strong>. 
    <br><br>
    <span style="color: #00C9FF; font-weight: bold;">Bring the trophy to your country. Make your university proud!</span>
  </p>
</div>

<div id="idsc-countdown-container" style="margin: 40px 0; text-align: center; font-family: 'Courier New', Courier, monospace;">
  <p style="text-transform: uppercase; letter-spacing: 3px; font-weight: bold; margin-bottom: 15px; font-size: 1.1em; color: #FFD700;">
    ⚡ REGISTRATION CLOSES IN:
  </p>
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <div style="background: rgba(255, 215, 0, 0.1); border: 1px solid #FFD700; padding: 20px; border-radius: 12px; min-width: 100px;">
      <span id="days" style="display: block; font-size: 3em; font-weight: 900; color: #FFD700;">--</span>
      <span style="font-size: 0.8em; text-transform: uppercase; font-weight: bold; color: #fff;">Days</span>
    </div>
    <div style="background: rgba(255, 215, 0, 0.1); border: 1px solid #FFD700; padding: 20px; border-radius: 12px; min-width: 100px;">
      <span id="hours" style="display: block; font-size: 3em; font-weight: 900; color: #FFD700;">--</span>
      <span style="font-size: 0.8em; text-transform: uppercase; font-weight: bold; color: #fff;">Hours</span>
    </div>
    <div style="background: rgba(255, 215, 0, 0.1); border: 1px solid #FFD700; padding: 20px; border-radius: 12px; min-width: 100px;">
      <span id="minutes" style="display: block; font-size: 3em; font-weight: 900; color: #FFD700;">--</span>
      <span style="font-size: 0.8em; text-transform: uppercase; font-weight: bold; color: #fff;">Mins</span>
    </div>
    <div style="background: rgba(255, 215, 0, 0.1); border: 1px solid #FFD700; padding: 20px; border-radius: 12px; min-width: 100px;">
      <span id="seconds" style="display: block; font-size: 3em; font-weight: 900; color: #FFD700;">--</span>
      <span style="font-size: 0.8em; text-transform: uppercase; font-weight: bold; color: #fff;">Secs</span>
    </div>
  </div>
  <p style="margin-top: 15px; font-size: 0.9em; color: #aaa;">Deadline: 10 March 2026, 23:59 (GMT+8)</p>
</div>

<div style="text-align: center; margin: 50px 0;">
  <a href="https://forms.gle/MFqXpuuk9rT2yF9d6" style="display: inline-block; padding: 25px 60px; font-size: 1.6em; color: #0d1117; background: linear-gradient(90deg, #FFD700 0%, #FF8C00 100%); border-radius: 50px; text-decoration: none; font-weight: 900; text-transform: uppercase; box-shadow: 0 10px 20px rgba(255, 215, 0, 0.4); transition: transform 0.3s ease;">
    🚀 REGISTER FOR GLORY
  </a>
</div>

<script>
(function() {
  function startCountdown() {
    // TARGET DATE: March 10, 2026 at 23:59:59 GMT+8
    const targetDate = new Date("2026-03-10T23:59:59+08:00").getTime();

    const updateTimer = () => {
      const now = new Date().getTime();
      const diff = targetDate - now;

      if (diff <= 0) {
        const container = document.getElementById("idsc-countdown-container");
        if (container) {
          container.innerHTML = "<h3 style='color: #ff4757; text-transform: uppercase; border: 2px solid #ff4757; padding: 20px; border-radius: 12px;'>🏆 Registration is Now Closed</h3>";
        }
        return;
      }

      // Calculations for days, hours, minutes and seconds
      const d = Math.floor(diff / (1000 * 60 * 60 * 24));
      const h = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const m = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
      const s = Math.floor((diff % (1000 * 60)) / 1000);

      // Helper function to update elements safely
      const setVal = (id, val) => {
        const el = document.getElementById(id);
        if (el) el.innerText = val.toString().padStart(2, '0');
      };

      setVal("days", d);
      setVal("hours", h);
      setVal("minutes", m);
      setVal("seconds", s);
    };

    // Run immediately and then every second
    updateTimer();
    const interval = setInterval(() => {
      const now = new Date().getTime();
      if (targetDate - now <= 0) {
        updateTimer();
        clearInterval(interval);
      } else {
        updateTimer();
      }
    }, 1000);
  }

  // Ensure script runs even if it's placed at the bottom or top
  if (document.readyState === "complete" || document.readyState === "interactive") {
    startCountdown();
  } else {
    document.addEventListener("DOMContentLoaded", startCountdown);
  }
})();
</script>
