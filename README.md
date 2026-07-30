<!-- HEADER BANNER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0284c7,100:06b6d4&height=220&section=header&text=Yash%20Pratap%20Singh&fontSize=42&fontAlign=50&fontAlignY=35&desc=AI%20%26%20Data%20Science%20Student%20%7C%20Machine%20Learning%20%26%20Computer%20Vision%20Developer&descSize=17&descAlign=50&descAlignY=63&stroke=ffffff&strokeWidth=0.5" width="100%" alt="Yash Pratap Singh Header"/>

  <br/>

  <a href="https://www.linkedin.com/in/yash-pratap-singh-4542692a0/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="https://github.com/Yash-Singh607">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/yash_014/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>

</div>

<br/>

> **Welcome to my GitHub!** I am an AI & Data Science student at **VIT Bhopal** passionate about building high-accuracy Machine Learning models, real-time Computer Vision pipelines, and medical & sentiment analytics solutions.

---

### 💡 About Me

* 🏫 **Education**: Artificial Intelligence & Data Science Student at **VIT Bhopal University**
* 🧠 **Specializations**: Deep Learning, Computer Vision (Medical & Edge AI), Natural Language Processing, and Predictive Signal Processing
* 🎯 **Current Focus**: Medical Imaging Classification, Real-Time Vision Pipelines, and Open-Source Collaboration
* 🏆 **Activities**: Hackathon builder & active algorithmic problem solver on LeetCode

---

### 🛠️ Technical Skillset

<p>
  <b>💻 Core Languages:</b><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

<p>
  <b>🧠 AI / ML & Computer Vision:</b><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace"/>
  <img src="https://img.shields.io/badge/Grad--CAM-00D2FF?style=flat-square&logo=python&logoColor=black" alt="Grad-CAM"/>
  <img src="https://img.shields.io/badge/CLAHE-008080?style=flat-square&logo=opencv&logoColor=white" alt="CLAHE"/>
</p>

<p>
  <b>🌐 Web & Infrastructure:</b><br/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="TailwindCSS"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

### 🚀 Featured Projects & Technical Engineering Breakdown

#### 🫁 01. PulmoScan — AI-Powered Pulmonary X-Ray Diagnostic System
> **Medical Computer Vision & Deep Learning Interpretability**

* 🛑 **Problem Faced**: 
  1. Medical X-ray datasets suffer from severe class imbalance (rare pathologies vs. healthy scans), causing standard CNNs to yield high false-negative rates.
  2. Low local contrast in raw radiograph images makes subtle pulmonary lesions difficult for convolution layers to extract.
  3. Raw probability scores (`0.92 positive`) act as a "black box" and lack clinical trust without visual verification.

* 💡 **Technical Solution & Implementation**:
  1. **Contrast Limited Adaptive Histogram Equalization (CLAHE)**: Pre-processed DICOM/X-ray inputs with CLAHE in OpenCV to amplify tissue boundary clarity.
  2. **Class-Weighted Focal Loss**: Implemented Weighted Focal Loss alongside transfer learning (EfficientNet/ResNet) to heavily penalize false negatives on hard positive samples.
  3. **Grad-CAM Visual Explainability**: Generated Grad-CAM heatmaps overlaid directly on X-ray scans to highlight exact region attributions for radiologist verification.

* **Tech Stack**: `PyTorch` • `OpenCV` • `Grad-CAM` • `Scikit-Learn` • `Python`

---

#### 🎭 02. Emotion Drift Detection System
> **Natural Language Processing & Sentiment Acceleration Dynamics**

* 🛑 **Problem Faced**: 
  1. Traditional NLP models evaluate messages in isolation (static sentiment) and fail to detect gradual emotional degradation across multi-turn customer support chats.
  2. Standard models trigger escalation alerts too late, after customer frustration has already peaked and churn is imminent.

* 💡 **Technical Solution & Implementation**:
  1. **Temporal Sliding-Window Algorithm**: Built a sliding window mechanism across sequential timestamps to measure sentiment **trajectory**, **velocity**, and **acceleration**.
  2. **Contextual Transformer Shift Vectors**: Utilized fine-tuned **Hugging Face Transformer embeddings** to calculate cosine distance shifts between baseline neutral vectors and negative trajectory vectors.
  3. **Proactive Alert Engine**: Engineered an automated threshold engine that alerts support leads *before* customer churn occurs.

* **Tech Stack**: `Python` • `Hugging Face Transformers` • `PyTorch` • `NLP` • `Pandas`

---

#### 👁️ 03. Shastra Eye — Real-Time AI Surveillance Pipeline
> **Edge Computer Vision & Real-Time Analytics**

* 🛑 **Problem Faced**: Processing high-resolution video streams on standard hardware causes frame drops and inference latency during real-time surveillance.
* 💡 **Technical Solution**: Implemented multi-threaded frame decoding with PyTorch and OpenCV CUDA acceleration to enable low-latency target tracking and automated event detection on edge devices (NVIDIA Jetson).
* **Tech Stack**: `PyTorch` • `OpenCV` • `NVIDIA Jetson` • `Edge AI`

---

#### 🧠 04. Visual Stress Detection System
> **Biomedical Signal Processing & Micro-Motion Analytics**

* 🛑 **Problem Faced**: Traditional physiological stress measurement relies on intrusive physical sensors attached to the body.
* 💡 **Technical Solution**: Designed a non-invasive optical flow pipeline that analyzes sub-visual facial skin tremors and micro-expression fluctuations directly from standard webcam feeds.
* **Tech Stack**: `Python` • `OpenCV` • `Optical Flow` • `Signal Processing`

---

#### 🤖 05. Enterprise Knowledge Copilot
> **Intelligent Information Search & Retrieval**

* 🛑 **Problem Faced**: Searching through dense, multi-page enterprise PDFs yields fragmented keyword search results.
* 💡 **Technical Solution**: Built a semantic document indexing pipeline using vector similarity embeddings to locate and extract relevant contextual passages rapidly.
* **Tech Stack**: `LangChain` • `FastAPI` • `Python` • `Vector Search`

---

### 📜 Certifications

* 🎓 **Machine Learning** — NPTEL
* ☁️ **AI Fundamentals** — Microsoft Learn
* 📊 **Data Analytics Certification**
* ☕ **Java Programming Certification**
* 🗄️ **SQL & Database Management**
* 💻 **Frontend Development Certification**

---

### 📊 GitHub Activity & Statistics

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Yash-Singh607&theme=tokyonight&hide_border=true" alt="Yash's GitHub Streak" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Yash-Singh607&theme=tokyo-night&hide_border=true" alt="Activity Graph" width="100%"/>
</div>

---

<div align="center">
  <p>🤝 <b>Open for collaborations in Machine Learning, Computer Vision, and Software Engineering</b></p>
  <p><i>Feel free to connect via <a href="https://www.linkedin.com/in/yash-pratap-singh-4542692a0/">LinkedIn</a> or check out my repositories!</i></p>
</div>
