<p align="center">
  <img src="https://raw.githubusercontent.com/Fairoos-palakkal/Fairoos-palakkal/main/assets/images/preview.png.jpg" width="100%" alt="Fairoos Palakkal – AI Developer"/>
</p>

<h1 align="center">Fairoos Palakkal</h1>
<p align="center">
  <strong>AI Developer · Computer Vision Engineer · Abu Dhabi, UAE</strong><br/>
  <em>I build AI systems that run in production — not just in notebooks.</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/mohammed-fairoos">
    <img src="https://img.shields.io/badge/LinkedIn-mohammed--fairoos-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Status-Open%20to%20Roles-F97316?style=flat-square"/>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=fairoos-palakkal&style=flat-square&color=0A66C2"/>
</p>

---

## What I Actually Do

I design and ship end-to-end computer vision pipelines — from raw input to structured output behind a production API.

My work spans face recognition systems, real-time object detection, and OCR pipelines built for real-world conditions: variable lighting, occlusion, noisy document scans. I care about latency, reliability, and deployability — not just model accuracy on clean test sets.

---

## Featured Projects

### VisionGate — Real-Time Face Recognition System

> Full-stack biometric identity system. Not a demo. Runs live.

- **Problem:** Most face recognition implementations collapse under real-world conditions — low light, partial occlusion, angle variation. VisionGate was built to handle all three.
- **Stack:** ArcFace (embedding), RetinaFace (detection), FastAPI, WebSocket streaming, Docker, Nginx
- **Capability:** Live multi-face detection and identity matching over WebSocket streams with sub-second response; containerized and reverse-proxied for production deployment
- **Architecture:** Camera input → RetinaFace detection → ArcFace embedding → cosine similarity matching → structured API response

---

### License Plate Recognition System

> End-to-end vehicle plate detection and text extraction pipeline.

- **Problem:** Automating vehicle identity extraction from camera feeds for access control and logging use cases
- **Stack:** YOLOv8 (detection), OpenCV, OCR, Python
- **Capability:** Real-time plate detection from video streams; handles partial plates, motion blur, and angle distortion
- **Output:** Structured plate string with bounding box metadata, ready for downstream database logging

---

### Emirates ID / Trade License OCR Pipeline

> Structured data extraction from UAE government documents.

- **Problem:** Manual data entry from identity and business registration documents — error-prone and slow
- **Stack:** Python, OpenCV, Tesseract, FastAPI
- **Capability:** Automated field extraction (name, ID number, expiry, license number) from scanned and photographed documents; handles skew, low resolution, and mixed Arabic/English layouts
- **Output:** Clean JSON via REST API, integrated into downstream workflows

---

### Solar Power Generation Forecast

> Regression model predicting energy output from environmental variables.

- **Problem:** Unreliable manual forecasting for solar plant output planning
- **Stack:** Scikit-Learn, Pandas, Streamlit
- **Capability:** 10-variable regression model trained on real sensor data; deployed as an interactive dashboard for non-technical stakeholders

---

### Customer Segmentation Pipeline

> Clustering-based segmentation deployed as a usable product.

- **Problem:** Raw customer data with no actionable groupings for targeting or analysis
- **Stack:** Scikit-Learn (K-Means, PCA), Flask, Python
- **Capability:** Automated segmentation pipeline with visual cluster output; deployed as a live Flask dashboard

---

## Current Focus — 2026

- **Multi-camera AI systems** — tracking identities across feeds with consistent re-ID
- **ONNX optimization** — converting trained models for faster inference on edge hardware
- **Agentic AI pipelines** — LLM-driven orchestration layered on top of vision system outputs
- **Multimodal document understanding** — combining OCR with LLM reasoning for complex document parsing

---

## Proof of Work

| Signal | Detail |
|---|---|
| Shipped systems | VisionGate: WebSocket + Docker + Nginx — fully deployed |
| Real-world scope | OCR handles Arabic/English, skew, noise — not clean benchmark data |
| Full-stack ownership | Data → Model → API → Deployment — no handoffs |
| Domain depth | Face recognition (ArcFace/RetinaFace), detection (YOLOv8), OCR, regression, clustering |

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=fairoos-palakkal&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"
    height="170"
  />
  &nbsp;
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=fairoos-palakkal&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"
    height="170"
  />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=fairoos-palakkal&theme=tokyonight&hide_border=true"/>
</p>

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLOv8-111111?style=for-the-badge&logo=yolo&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
</p>

---

## Connect

<p align="center">
  <a href="https://linkedin.com/in/mohammed-fairoos">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:fairoospalakkal35@gmail.com">
    <img src="https://img.shields.io/badge/Email-fairoospalakkal35@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/fairoos-palakkal">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<p align="center">
  <sub>Open to Computer Vision, AI Developer, and Applied ML roles — Abu Dhabi & remote</sub>
</p>
