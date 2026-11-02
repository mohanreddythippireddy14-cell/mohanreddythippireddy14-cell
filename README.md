<p align="center">
  <a href="https://mohanreddythippireddy14-cell.github.io">
    <img src="https://mohanreddythippireddy14-cell.github.io/assets/charts/banner.svg" width="100%" alt="Thippireddy Mohan Reddy: AI, computer vision and agentic AI. 3rd globally at STIR 2026.">
  </a>
</p>

<p align="center">
  <a href="https://mohanreddythippireddy14-cell.github.io"><img src="https://img.shields.io/badge/Website-portfolio-4f46e5?style=for-the-badge" alt="Website"></a>
  <a href="https://www.linkedin.com/in/thippireddy-mohan-reddy-732a78382/"><img src="https://img.shields.io/badge/LinkedIn-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mohanreddythippireddy14@gmail.com"><img src="https://img.shields.io/badge/Email-mohanreddythippireddy14%40gmail.com-0d9488?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Second-year B.Tech student at **IIIT Allahabad** (IT, Business Informatics · CGPA 8.22) and research member of the
**CIR Robotics Research Group**. I work on surgical video point tracking, detection and depth pipelines, probabilistic
supervision of deep models, and multi-agent LLM systems with guardrails. Looking for **research and engineering
internships** in AI, computer vision and agentic systems.

| Achievement | |
|---|---|
| **3rd globally** (team) | STIR Challenge 2026, MICCAI EndoVis |
| **2nd nationally** | Strategy Wiz, MNNIT Allahabad, 2025 |
| **99.363 percentile** | JEE |
| **Certified** | [Deep Learning Specialization](https://www.deeplearning.ai/certificates/0a9c8e89-d559-431c-9a19-ce1ee0566b3e), DeepLearning.AI |

## Research

**CIR Robotics Research Group, IIIT Allahabad** (Prof. G.C. Nandi) · 2026 to present

- Generative affordance and predictive world-model guidance for dexterous articulated manipulation.
- Video point-tracking research (SurgQueST), including a pipeline audit that found a core implementation gap.

## Projects

### [STIR Challenge 2026: surgical tissue tracking](https://github.com/mohanreddythippireddy14-cell/STIR-CHALLENGE-2026-MICCAI-ENDOVIS) · 3rd globally

Co-authored the 2D methodology report for our Track-On2 based submission, benchmarked 10+ trackers under a
200 ms/frame streaming budget, and built a Kalman-predicted handoff that matched an expensive re-anchoring gain at +0.4% latency.

<img src="https://mohanreddythippireddy14-cell.github.io/assets/charts/stir-accuracy-latency.svg" width="100%" alt="Accuracy vs latency for 10+ trackers, with the 200 ms budget shaded">

| Tracker | ATA | p95 (local) | Frame by frame |
|---|---:|---:|---|
| DenseTrack2D (offline) | 0.743 | 485 ms | ✗ |
| CoTracker3 online | 0.686 | 127 ms | ✓ |
| Streaming DenseTrack2D (mine) | 0.686 | 156 ms | ✓ |
| MFT (official reference) | 0.400 | 2,303 ms | ✗ too slow |

### HBIPT: probabilistic supervisor for point tracking

A runtime supervisor on LiteTracker with a recursive Bayesian belief filter over 8 hypothesis families and gated actions.
Bit-identical to the stock tracker on **60/60** sequences at **+1.1%** latency; showed that nearest-point scoring hides
identity failures (strict index matching drops AJ by ~0.30).

### [Road damage detection and severity triage](https://github.com/mohanreddythippireddy14-cell/Pothole_detection)

YOLOv8 detection and segmentation plus Depth-Anything-V2 depth feed an ASTM D6433-based severity engine.
1,986 merged images with a leakage-free split · **5-fold CV mAP@50 0.73** · 2.3% background false-positive rate.

<p>
  <img src="https://mohanreddythippireddy14-cell.github.io/assets/pothole-high.jpg" width="49%" alt="Deep pothole rated HIGH">
  <img src="https://mohanreddythippireddy14-cell.github.io/assets/charts/pothole-metrics.svg" width="49%" alt="Detection and segmentation metrics">
</p>

### [CogAIt: Socratic multi-agent tutor](https://github.com/mohanreddythippireddy14-cell/CogAIt) · [live app](https://cog-ai-t.vercel.app)

8 orchestrated agents that raise help across four levels without revealing answers, with a think-first gate,
rate limiting and a judge agent that audits replies for leaked answers. React · Convex · Gemini · Groq · Cloud Run.

### [Autonomous content engine](https://github.com/mohanreddythippireddy14-cell/billionaire-thoughts)

Writes, renders (1080×1920) and uploads a video to three platforms three times a day, and reviews its own analytics weekly.

<img src="https://mohanreddythippireddy14-cell.github.io/assets/charts/shorts-schedule.svg" width="100%" alt="Daily upload schedule on India time">

### More

| Project | What it does | Stack |
|---|---|---|
| [SiteBook](https://github.com/mohanreddythippireddy14-cell/SiteBook) | Construction-site attendance and wages, with PDF/Excel pay reports | React Native · Firebase |
| [RupeeGrow](https://github.com/mohanreddythippireddy14-cell/rupeegrow) · [try it](https://mohanreddythippireddy14-cell.github.io/rupeegrow/) | Compound interest and SIP calculator for India, Hindi and English | HTML · JS · PWA |

## Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Computer vision:** YOLOv8 · segmentation · point tracking (CoTracker3, LiteTracker, Track-On2, MFT) · RAFT · Depth-Anything-V2 · stereo · DINOv2\
**ML methods:** fine-tuning · knowledge distillation · pseudo-labelling · Bayesian inference · Kalman filtering · uncertainty estimation\
**Agentic AI:** multi-agent orchestration · guardrails and response validation · LLM-as-judge · Gemini · Groq
