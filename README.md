<div align="center">

<!-- BANNER: terminal profile.sh --live (FS/SERPENTINE 1-BIT particle portrait + telemetry) -->
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-dark.svg" width="100%" alt="profile.sh --live">
</picture>

<br/>

<!-- IDENTITY LINE -->
<a href="https://github.com/iam-shivanshu">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=58A6FF&center=true&vCenter=true&repeat=true&width=680&height=55&lines=Shivanshu+%2F+Embedded+Systems+%26+IoT;Building+things+that+plug+into+the+real+world;ESP8266+%7C+Firebase+%7C+Local+AI;Hardware+%E2%86%92+Software+%E2%86%92+Shipped" alt="Shivanshu — Embedded Systems & IoT" />
</a>

<br/>

<!-- IDENTITY PILLS -->
<p>
  <img src="https://img.shields.io/badge/ESP8266%20%2F%20Arduino-Embedded%20Systems-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Embedded Systems" />
  &nbsp;
  <img src="https://img.shields.io/badge/Firebase%20%2F%20PWA-Cloud%20%26%20Web-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Cloud & Web" />
  &nbsp;
  <img src="https://img.shields.io/badge/Python%20%2F%20AI-Voice%20%26%20Automation-3776AB?style=flat-square&logo=python&logoColor=white" alt="AI & Automation" />
  &nbsp;
  <img src="https://img.shields.io/badge/Location-India-FF9933?style=flat-square&logo=googlemaps&logoColor=white" alt="India" />
</p>

<br/>

</div>

---

## `> whoami`

I'm a builder who finds the boundary between software and the physical world interesting — and keeps building there.

My projects tend to start with a real problem: a DVR's motion signal going unused, a water tap with no one to remind you to close it, a voice command that should just *work* without a cloud subscription. I reverse-engineer what's available, figure out the minimum hardware to solve it cleanly, and ship it as open source.

Right now I'm deep in **embedded systems** (ESP8266 / Arduino), **IoT automation with Firebase**, and **voice-driven AI interfaces**. I care about work that's deployable on real hardware, not just runnable in a notebook.

<br/>

---

## `> ls ./what-i-build`

<table>
<tr>
<td width="50%" valign="top">

### 🔌 Embedded Systems & IoT
Hardware-first projects that solve real-world problems without unnecessary complexity. One chip, one sensor, one clear purpose.

- Ultrasonic sensing & proximity logic
- Hardware sigma-delta audio (no decoder chips)
- Active-low relay control & boot-safe GPIO
- Single-supply power design (5V/12V)

</td>
<td width="50%" valign="top">

### 🏠 Home & Building Automation
Turning dumb infrastructure into responsive systems — no proprietary hub required.

- CCTV DVR motion → room automation bridge
- Per-room ESP8266 mesh via relay logic
- Firebase Realtime DB remote override
- PWA control panel (works offline)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ Voice & AI Interfaces
Making computers respond to humans naturally — locally when possible, cloud when it matters.

- Offline neural TTS → flash-baked PCM audio
- Speech recognition + LLM response loop
- Ollama (Mistral) local inference
- No-cloud, no-subscription voice systems

</td>
<td width="50%" valign="top">

### ♻️ Conservation & Impact
Building systems that change behaviour through smart feedback — not just monitoring.

- Proximity-triggered water conservation alerts
- Real-time behavioral nudge via audio playback
- Deployable in schools, hostels, public spaces
- Zero connectivity required after deployment

</td>
</tr>
</table>

<br/>

---

## `> cat tech-stack.txt`

**Microcontrollers & Firmware**

![ESP8266](https://img.shields.io/badge/ESP8266-000000?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

**Cloud, Backend & Web**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**AI, Scripting & Tooling**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

<br/>

---

## `> ls ./projects --sort=impact`

<br/>

### ⚡ [esp8266-dvr-motion-automation](https://github.com/iam-shivanshu/esp8266-dvr-motion-automation)

> **Turn your existing CCTV DVR's motion detection into an automatic room controller — no new cameras, no proprietary hub.**

An ESP8266 intercepts the DVR's existing motion-detection output and drives relays to control lights or appliances per room. An optional Firebase-backed PWA gives you remote override from anywhere in the world. The whole system costs under ₹500 per room and works with any DVR that exposes motion signals.

**Stack:** `C++ / Arduino` · `ESP8266` · `Firebase Realtime DB` · `HTML/JS PWA` · `Active-Low Relay`

<p>
  <img src="https://img.shields.io/github/stars/iam-shivanshu/esp8266-dvr-motion-automation?style=flat-square&color=58A6FF" alt="Stars" />
  <img src="https://img.shields.io/github/languages/top/iam-shivanshu/esp8266-dvr-motion-automation?style=flat-square&color=00979D" alt="Language" />
  <img src="https://img.shields.io/badge/status-deployed-22c55e?style=flat-square" alt="Status" />
</p>

---

### 🔊 [esp8266-water-conservation-alert](https://github.com/iam-shivanshu/esp8266-water-conservation-alert)

> **A smart tap reminder that speaks to you. No Wi-Fi, no app, no cloud — just a chip, a sensor, and a speaker.**

An ultrasonic sensor watches a water tap. When someone approaches within 40 cm, a spoken voice message plays: *"Please don't waste water."* The audio is neural-TTS-generated, preprocessed (DC-block, band-limit, soft-limit), and baked into flash as a 16-bit PCM array — no SD card, no MP3 decoder needed. Custom messages take one Python command to swap in.

**Stack:** `C / Arduino` · `ESP8266 Hardware Sigma-Delta` · `Python (PyAV)` · `Neural TTS` · `Offline`

<p>
  <img src="https://img.shields.io/github/stars/iam-shivanshu/esp8266-water-conservation-alert?style=flat-square&color=58A6FF" alt="Stars" />
  <img src="https://img.shields.io/github/languages/top/iam-shivanshu/esp8266-water-conservation-alert?style=flat-square&color=3776AB" alt="Language" />
  <img src="https://img.shields.io/badge/status-deployable-22c55e?style=flat-square" alt="Status" />
</p>

---

### 🤖 [chatbot-project](https://github.com/iam-shivanshu/chatbot-project)

> **A fully local voice AI chatbot — speak a question, hear an answer. No API key required.**

Listens via microphone, transcribes with speech recognition, queries Ollama (Mistral) locally, and speaks the response aloud with text-to-speech. Runs entirely on your machine. Say "exit" to stop.

**Stack:** `Python` · `SpeechRecognition` · `Ollama / Mistral` · `pyttsx3` · `100% Local`

<p>
  <img src="https://img.shields.io/github/stars/iam-shivanshu/chatbot-project?style=flat-square&color=58A6FF" alt="Stars" />
  <img src="https://img.shields.io/badge/AI-Local%20LLM-8B5CF6?style=flat-square" alt="Local LLM" />
  <img src="https://img.shields.io/badge/status-working-22c55e?style=flat-square" alt="Status" />
</p>

<br/>

---

## `> git log --stat`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=iam-shivanshu&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&ring_color=58A6FF" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=iam-shivanshu&show_icons=true&theme=default&hide_border=true&title_color=0969DA&icon_color=0969DA" />
  <img src="https://github-readme-stats.vercel.app/api?username=iam-shivanshu&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" alt="GitHub Stats" height="165" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=iam-shivanshu&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=iam-shivanshu&layout=compact&theme=default&hide_border=true&title_color=0969DA" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iam-shivanshu&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages" height="165" />
</picture>

</div>

<br/>

### Contribution activity

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iam-shivanshu/iam-shivanshu/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iam-shivanshu/iam-shivanshu/output/snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/iam-shivanshu/iam-shivanshu/output/snake.svg" />
</picture>
</div>

<br/>

---

## `> cat ./current-focus.md`

```
Currently exploring:
  ├── ESP32 migration (dual-core, Bluetooth, more GPIO)
  ├── MQTT for multi-device IoT coordination
  ├── Whisper-based local speech transcription
  └── Computer vision on edge (OpenCV + Pi)

Open to:
  ├── Collaborations on embedded / IoT projects
  ├── Open-source contributions in hardware + firmware
  └── Discussions on offline-first, local AI systems
```

<br/>

---

## `> cat contact.md`

<div align="center">

<a href="https://github.com/iam-shivanshu">
  <img src="https://img.shields.io/badge/GitHub-iam--shivanshu-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br/><br/>

*Building in public. Everything is open source.*

</div>

---

<div align="center">
  <sub>Profile auto-updated · Built with purpose, not templates</sub>
</div>
