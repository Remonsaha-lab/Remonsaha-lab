<div align="center">

# Hi there, I'm Remon Saha 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=620&lines=Electrical+Engineering+%40+Jadavpur+University;3D+Perception+%26+Computer+Vision+Researcher;Agentic+Workflows+%26+Graph+Neural+Networks;Ex-Research+Intern+%40+BARC)](https://git.io/typing-svg)

<p align="center">
  <b>B.E. Electrical Engineering (3rd Year) • Jadavpur University</b><br>
  Passionate about AI Engineer, Agentic AI Systems.
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Remon_Saha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Remonsaha--lab-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Remonsaha-lab)
[![Email](https://img.shields.io/badge/Email-remonsaha95%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:remonsaha95@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com)

</div>

---

### 🔬 About Me

- 🎓 **Undergraduate:** 3rd-year Electrical Engineering student at **Jadavpur University** (CGPA: 8.15).
- 🏛️ **Research:** Former Research Intern at **Bhabha Atomic Research Centre (BARC)** specializing in transformer-based 3D semantic segmentation for autonomous mobile robots (AMRs).
- 🤖 **Robotics:** Core Software Member at **Jadavpur University Mechatronics Club** working on rover communication & object detection for the **International Rover Challenge (IRC)**.
- 🏆 **Award Winner:** 1st Position at **IEEE Medhamanthan 2025** for *Netravaani* (Eye-Gaze Assistive Communication System).
- 💡 **Focus Areas:** 3D Point Clouds, GNNs for Molecular Chemistry, Calibrated Agentic ML Workflows, and Edge Computer Vision.

---

### 🛠️ Technical Skills

<div align="center">

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **AI / Machine Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![PyG](https://img.shields.io/badge/PyTorch_Geometric-3B82F6?style=flat-square) ![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-15B064?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **Architectures & Paradigms** | `Transformers` • `3D Semantic Segmentation` • `Graph Neural Networks (GNN)` • `YOLOv8 / YOLOv11` • `Agentic Workflows` • `Model Calibration` |
| **Frameworks & Agents** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) |
| **Embedded & Hardware** | ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) `Intel RealSense Depth Cameras` • `AMR Perception Systems` |
| **DevOps & Tools** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |

</div>

---

### 🌟 Featured Research & Projects

#### 1. 🛡️ [DisputeGuard — Evidence-Grounded AI Risk Manager](https://github.com/Remonsaha-lab)
> *Autonomous, audited multi-modal dispute resolution & representment engine.*
- **Architecture:** 7-node deterministic workflow built with **LangGraph** and **FastAPI** handling dispute ingestion, cross-document verification, and packet generation.
- **Deterministic Validation:** 4-layer schema validator (Order/Tracking IDs, amounts, timelines, consistency) with fuzzy OCR tolerance.
- **Calibrated ML:** Trained **XGBoost with Platt scaling** across 40 engineered features, achieving **0.9499 ROC-AUC**, **94.74% contest precision**, and **0.0896 Brier score**.
- **Guardrails:** Integrated **Gemini API** with regex-based factual audit guardrails to prevent hallucinated claims, paired with automated ReportLab PDF compilation and human-in-the-loop sign-off.
- `LangGraph` `FastAPI` `XGBoost` `Gemini API` `Platt Scaling` `Python`

---

#### 2. 🔬 [BARC 3D Perception — Transformer-Based Semantic Segmentation](https://github.com/Remonsaha-lab)
> *Research conducted at Bhabha Atomic Research Centre for feature-deficient Autonomous Mobile Robots.*
- Engineered an end-to-end **RGB-D-to-3D** semantic segmentation pipeline using DIODE, Mask2Former pseudo-labels, camera back-projection, and 5 cm voxel downsampling.
- Adapted **EZ-SP** with a **TorchSparse 3D CNN encoder**, GPU-native superpoint partitioning, and modified Superpoint Transformer for point-cloud reasoning.
- Achieved **87.37% test mIoU** in Stage-1 partition learning and resolved KITTI-360 to DIODE domain shift, boosting mIoU from **31.2% zero-shot to 52.4%**.
- `PyTorch` `TorchSparse` `3D Point Clouds` `Transformers` `Superpoints`

---

#### 3. 🧪 [Molecular Property Prediction using GNNs](https://github.com/Remonsaha-lab)
> *Deep learning on graph-structured biochemical data for molecular discovery.*
- Engineered a graph neural network pipeline to predict 5 binary molecular properties directly from SMILES strings using **PyTorch Geometric** and **RDKit**.
- Architected a **5-layer residual GINEConv** model featuring multi-scale graph pooling, atom/bond topological features, and masked BCE loss for missing labels.
- Evaluated via 5-fold stratified cross-validation with AdamW and cosine annealing schedule, attaining **0.9268 ± 0.0054 mean ROC-AUC**.
- `PyG` `RDKit` `GNN` `GINEConv` `Bioinformatics` `Deep Learning`

---

#### 4. 🚀 [Autonomous Rover Vision: Crater & Traffic Cone Detection](https://github.com/Remonsaha-lab)
> *Computer vision perception stack for the International Rover Challenge (IRC).*
- Built dual object-detection pipelines utilizing **Ultralytics YOLOv11** (craters) and **YOLOv8** (traffic cones) on merged multi-sensor datasets.
- Tuned for real-time edge inference with **Intel RealSense** depth cameras on custom robotic hardware.
- Attained **73.6% mAP** for craters and **92.5% mAP** for cones through iterative augmentation and transfer learning.
- `YOLOv11` `YOLOv8` `Intel RealSense` `Robotics` `Computer Vision`

---

#### 5. 👁️ [Netravaani — Eye-Gaze Assistive Communication System](https://github.com/Remonsaha-lab)
> *🥇 1st Place Winner at IEEE Medhamanthan 2025.*
- Hands-free assistive spelling and communication system powered by custom OpenCV iris tracking.
- Coupled an intuitive React accessibility UI with an **ESP32** microcontroller over serial/WebSockets for physical task execution.
- `OpenCV` `Python` `React` `ESP32` `Human-Computer Interaction`

---

### 📊 GitHub Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Remonsaha-lab&show_icons=true&theme=radical&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Remonsaha-lab&layout=compact&theme=radical&hide_border=true" width="48%" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Remonsaha-lab&theme=radical&hide_border=true" width="96%" alt="GitHub Streak" />
</div>

---

### 📬 Connect With Me

<p align="center">
  <a href="mailto:remonsaha95@gmail.com">
    <img src="https://img.shields.io/badge/Email-remonsaha95%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Remonsaha-lab">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<div align="center">
  <sub>Designed with precision • Remon Saha © 2026</sub>
</div>
