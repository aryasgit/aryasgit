<div align="center">

# Aryaman Gupta

**Electrical & Computer Engineering · Robotics · Embedded Systems · Perception · Local-First Tooling**

[![GitHub followers](https://img.shields.io/github/followers/aryasgit?style=flat&color=6e7681&labelColor=161b22&label=followers)](https://github.com/aryasgit)
&nbsp;
[![Profile Views](https://komarev.com/ghpvc/?username=aryasgit&style=flat&color=6e7681&labelColor=161b22&label=profile+views)](https://github.com/aryasgit)

</div>

---

### About

ECE student at Shiv Nadar IoE building physical robotic systems — quadrupeds, perception pipelines, and edge-deployed hardware. Work spans mechanical integration, servo control, IMU fusion, embedded firmware, and vision inference at the hardware boundary.

Not interested in toy demos. Focused on systems that work under physical and computational constraints — where hardware breaks, sensors drift, and latency budgets are real.

When the off-the-shelf tools couldn't keep up with the shape of the work — code, hardware, parts, and long debugging threads at once — I built my own. **[Engram](https://github.com/aryasgit/engram)** is the result: four local-first, MIT-licensed developer tools that started as scaffolding for BARQ and generalized.

---

### What I Actually Do

```
Robotics          →  Quadruped locomotion, FSM-based gait control, servo abstraction, IMU coupling
Perception        →  Depth estimation, segmentation, inpainting, edge inference on Jetson
Embedded Systems  →  STM32, ESP8266/NodeMCU, serial protocols, sensor interfacing, hardware debug
Systems Eng.      →  Architecture under constraint, hardware-software integration, deployment
Developer Tools   →  Local-first memory (MCP), encrypted P2P sharing, build journaling, parts ledgers
```

---

### Current Focus

- **BARQ** — 12-DOF quadruped robot: Jetson Orin Nano compute, PCA9685 servo bus, MPU6050 IMU stabilization, terrain-adaptive gait
- **Perception pipeline** — Depth-Anything-V2 monocular depth + LaMa inpainting for spatial scene reconstruction
- **Actuator systems** — Hybrid servo strategy: DS3240MG (high-torque joints) + Feetech STS3215 serial bus (feedback joints)
- **Control architecture** — FSM locomotion, posture stabilization, layered hardware abstraction
- **Engram** — A family of local-first developer tools, built to make BARQ and generalized to any hardware project

---

### Featured Work — Robotics & Perception

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

### Engram — Local-First Developer Tools

Building BARQ broke every off-the-shelf tool — Notion was too slow, Slack cached everything forever, inventory software was built for warehouses. So I built the tooling the work actually needed. **[Engram](https://github.com/aryasgit/engram)** is four local-first, MIT-licensed tools, each owning one trace an engineering project leaves behind: what you *learned*, *said*, *did*, and *have*.

| Tool | Keeps | Stack |
|---|---|---|
| [**Memcon**](https://github.com/aryasgit/memcon) | what you **learned** — persistent memory for Claude over MCP; auto-recall before answering, auto-capture after solving | Python · Qdrant · Ollama · Markdown |
| [**Memshare**](https://github.com/aryasgit/memshare) | what you **said** — end-to-end encrypted P2P code & file sharing; the relay only ever sees ciphertext | JavaScript · WebCrypto · Fastify |
| [**Thymeline**](https://github.com/aryasgit/thymeline) | what you **did** — an editorial build journal; thought to logged in one keystroke | FastAPI · SQLite · Markdown |
| [**Invpart**](https://github.com/aryasgit/invpart) | what you **have** — a parts ledger where one status flag drives every total | FastAPI · SQLite · Markdown |

```
Local-first   →  Nothing leaves your machine. No SaaS, no telemetry, no accounts.
Transparent   →  Your data is plain Markdown on disk — own it, edit it, walk away with it.
MIT           →  Read the source. Fork it. Keep it. Each works standalone.
```

<details>
<summary><strong>Why four tools instead of one dashboard</strong></summary>
<br>

Each solves one real friction from building hardware, and each runs standalone — you're never required to install more than the one that fixes your problem. They share a design language and a posture (local-first, Markdown as source of truth, engineer-shaped), not a database. Built as scaffolding for BARQ, generalized for any project shaped like it: code, hardware, parts, and the long threads between them.
</details>

---

### Tech Stack

**Core Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Robotics & Embedded**

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Perception & ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)

**Systems, Infra & Local-First**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

### Engineering Philosophy

```
Reliability over novelty.
Architecture before implementation.
Understand the constraint before optimizing around it.
Hardware doesn't forgive assumptions software can ignore.
When the tool doesn't exist, build it — local-first, you own the data.
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

| Repository | Description | Stack |
|---|---|---|
| [quadruped](https://github.com/aryasgit/quadruped) | 12-DOF legged robot: FSM gait, IMU stabilization, servo abstraction | Python · Jetson · I²C |
| [depth-lama-inpainting](https://github.com/aryasgit/depth-lama-inpainting-pipeline) | Depth-aware inpainting pipeline for spatial scene reconstruction | PyTorch · OpenCV · CUDA |
| [engram](https://github.com/aryasgit/engram) | Four local-first dev tools — memory, encrypted sharing, journaling, inventory | Python · JS · SQLite · MCP |
| [memcon](https://github.com/aryasgit/memcon) | Local memory layer for Claude over MCP — auto-recall, auto-capture | Python · Qdrant · Ollama |

---

### Currently Exploring

- Kalman filter + SLAM for onboard localization on BARQ
- Serial bus servo feedback loops (position/load telemetry)
- Sensor fusion: IMU + depth for terrain-aware footstep planning
- Edge inference optimization: TensorRT, quantization, latency profiling on Jetson
- Collapsing Memcon's retrieval to a single embedded store (sqlite-vec + FTS5) — dropping Docker/Qdrant for a one-file, transparent index

---

<div align="center">

*I don't just write code — I build systems that have to survive reality.*

</div>

---
