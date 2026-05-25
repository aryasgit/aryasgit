<div align="center">

# Aryaman Gupta

**Electrical & Computer Engineering · Robotics · Embedded Systems · Perception**

[![GitHub followers](https://img.shields.io/github/followers/aryasgit?style=flat&color=6e7681&labelColor=161b22&label=followers)](https://github.com/aryasgit)
&nbsp;
[![Profile Views](https://komarev.com/ghpvc/?username=aryasgit&style=flat&color=6e7681&labelColor=161b22&label=profile+views)](https://github.com/aryasgit)

</div>

---

### About

ECE student at Shiv Nadar IoE building physical robotic systems — quadrupeds, perception pipelines, and edge-deployed hardware. Work spans mechanical integration, servo control, IMU fusion, embedded firmware, and vision inference at the hardware boundary.

Not interested in toy demos. Focused on systems that work under physical and computational constraints — where hardware breaks, sensors drift, and latency budgets are real.

---

### What I Actually Do

```
Robotics          →  Quadruped locomotion, FSM-based gait control, servo abstraction, IMU coupling
Perception        →  Depth estimation, segmentation, inpainting, edge inference on Jetson
Embedded Systems  →  STM32, ESP8266/NodeMCU, serial protocols, sensor interfacing, hardware debug
Systems Eng.      →  Architecture under constraint, hardware-software integration, deployment
```

---

### Current Focus

- **BARQ** — 12-DOF quadruped robot: Jetson Orin Nano compute, PCA9685 servo bus, MPU6050 IMU stabilization, terrain-adaptive gait
- **Perception pipeline** — Depth-Anything-V2 monocular depth + LaMa inpainting for spatial scene reconstruction
- **Actuator systems** — Hybrid servo strategy: DS3240MG (high-torque joints) + Feetech STS3215 serial bus (feedback joints)
- **Control architecture** — FSM locomotion, posture stabilization, layered hardware abstraction

---

### Featured Work

<details>
<summary><strong>BARQ — Quadruped Robotics Platform</strong></summary>
<br>

A 12-DOF legged robot built from mechanical design through software deployment.

**Hardware:** Jetson Orin Nano · PCA9685 PWM controller · MPU6050 6-axis IMU · DS3240MG / STS3215 servos  
**Software:** Python controller · FSM-based gait engine · IMU-coupled postural stabilization · terrain-adaptive arc correction  
**Architecture:** Hardware abstraction layer → locomotion FSM → servo abstraction → I²C bus  
**Focus:** Physical robustness, real-world debugging, deployment reliability

<!-- REPLACE: Add your quadruped repo link below -->
> Repository: [aryasgit/quadruped](https://github.com/aryasgit/quadruped)
</details>

<details>
<summary><strong>Depth-Aware Inpainting Pipeline</strong></summary>
<br>

End-to-end vision pipeline for spatially-aware image completion.

**Stack:** Depth-Anything-V2 · LaMa · OpenCV · PyTorch · CUDA  
**Pipeline:** Monocular depth estimation → forward warping → masked inpainting → spatial reconstruction  
**Context:** DIBR (Depth-Image-Based Rendering) for novel view synthesis on edge compute  

<!-- REPLACE: Add your pipeline repo link below -->
> Repository: [aryasgit/depth-lama-inpainting-pipeline](https://github.com/aryasgit/depth-lama-inpainting-pipeline)
</details>

<details>
<summary><strong>AI Surveillance System</strong></summary>
<br>

Multi-camera intelligent surveillance architecture for institutional deployment.

**Stack:** YOLOv8 · ByteTrack · FastAPI · SQLite  
**Scope:** 10-camera coverage, real-time tracking, event logging, REST API  
**Architecture:** Detection → tracking → event store → query API  

<!-- REPLACE: Add your surveillance repo link below -->
> Repository: [aryasgit/ai-surveillance](https://github.com/aryasgit/ai-surveillance)
</details>

---

### Tech Stack

**Core Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-555555?style=flat&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Robotics & Embedded**

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat&logo=nvidia&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Perception & ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)

**Systems & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

### Engineering Philosophy

```
Reliability over novelty.
Architecture before implementation.
Understand the constraint before optimizing around it.
Hardware doesn't forgive assumptions software can ignore.
```

---

### GitHub Stats

<!-- REPLACE: Change "aryasgit" to your GitHub username in all three URLs below -->

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=aryasgit&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideNums=C9D1D9&currStreakNum=C9D1D9&sideLabels=8B949E&dates=8B949E&background=0D1117)](https://git.io/streak-stats)

</div>

<div align="center">

[![Arya's GitHub Stats](https://github-readme-stats.vercel.app/api?username=aryasgit&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF&hide=contribs&count_private=true)](https://github.com/aryasgit)
&nbsp;&nbsp;
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aryasgit&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=6)](https://github.com/aryasgit)

</div>

---

### Pinned Projects

Check out the repos below — they reflect what I actually build.

<!-- REPLACE: GitHub lets you pin up to 6 repos from your profile page.
     Suggested pins (in order of priority):
     1. quadruped / BARQ
     2. depth-lama-inpainting-pipeline
     3. ai-surveillance
     4. Any embedded/STM32 projects
     5. ROS2 work
     6. ML coursework (if public)
-->

| Repository | Description | Stack |
|---|---|---|
| [quadruped](https://github.com/aryasgit/quadruped) | 12-DOF legged robot: FSM gait, IMU stabilization, servo abstraction | Python · Jetson · I²C |
| [depth-lama-inpainting](https://github.com/aryasgit/depth-lama-inpainting-pipeline) | Depth-aware inpainting pipeline for spatial scene reconstruction | PyTorch · OpenCV · CUDA |
| [ai-surveillance](https://github.com/aryasgit/ai-surveillance) | Multi-camera detection and tracking system | YOLOv8 · ByteTrack · FastAPI |

---

### Currently Exploring

- Kalman filter + SLAM for onboard localization on BARQ
- Serial bus servo feedback loops (position/load telemetry)
- Sensor fusion: IMU + depth for terrain-aware footstep planning
- Edge inference optimization: TensorRT, quantization, latency profiling on Jetson

---

<div align="center">

*I don't just write code — I build systems that have to survive reality.*

</div>

---

<!-- ═══════════════════════════════════════════════════════════════════
SETUP CHECKLIST (delete this section before publishing):

 1. Replace ALL instances of "aryasgit" with your GitHub username
 2. Go to github.com/aryasgit and pin these 6 repos manually
 3. Make sure your repos are public (or use count_private=true in stats)
 4. For streak stats: works automatically once you push to public repos
 5. Profile view counter auto-activates on first profile load

RECOMMENDED ADDITIONAL TOOLS:
- github-readme-activity-graph (contribution activity heatmap)
  → github.com/Ashutosh00710/github-readme-activity-graph
- Wakatime badge (coding time tracker, integrates with VS Code)
  → wakatime.com
- shields.io for any custom badges (shields.io)

RECOMMENDED THEMES for stats cards:
  github_dark / github_dark_dimmed / tokyonight / merko / gruvbox

FUTURE IMPROVEMENTS:
- Add a "Writing / Notes" section once you publish technical writeups
- Add Wakatime weekly coding stats once you have enough history
- Consider a custom header SVG (low-profile, just name + tagline)
  → Use github.com/anuraghazra/github-readme-stats for advanced config
═══════════════════════════════════════════════════════════════════ -->
