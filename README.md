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

> **Welcome to my GitHub!** I am an AI & Data Science student at **VIT Bhopal** specializing in Machine Learning, Medical Computer Vision, and Natural Language Processing. Passionate about solving real-world challenges through data-driven engineering.

---

### 💡 About Me

* 🏫 **Education**: B.Tech in Artificial Intelligence & Data Science at **VIT Bhopal University**
* 🧠 **Core Domains**: Computer Vision (Medical Image Diagnostics), Deep Learning, and Sentiment Trajectory Analytics
* 🎯 **Current Focus**: Explainable AI (XAI), Model Optimization, and Open-Source Machine Learning Systems
* 🏆 **Competitive Profile**: Hackathon Enthusiast & Problem Solver on LeetCode

---

### 🛠️ Technical Skillset

<p>
  <b>💻 Languages & Core Querying:</b><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

<p>
  <b>🧠 Machine Learning & Deep Learning:</b><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace"/>
</p>

<p>
  <b>👁️ Computer Vision & Explainable AI:</b><br/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Grad--CAM-00D2FF?style=flat-square&logo=python&logoColor=black" alt="Grad-CAM"/>
  <img src="https://img.shields.io/badge/CLAHE%20Preprocessing-008080?style=flat-square&logo=opencv&logoColor=white" alt="CLAHE"/>
</p>

<p>
  <b>🌐 Developer Tools & Frameworks:</b><br/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="TailwindCSS"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

### 🚀 Featured Engineering Case Studies

#### 🫁 01. PulmoScan — AI-Powered Pulmonary X-Ray Diagnostic System
> **Medical Computer Vision & Deep Learning Interpretability**

* 🛑 **Engineering Challenge**:
  * **Class Imbalance & Low Contrast**: Radiograph datasets often exhibit acute class imbalance between rare pulmonary conditions and normal scans, coupled with low local image contrast that obscures early-stage lesions.
  * **Model Opacity**: Standard deep learning outputs are treated as uninterpretable "black boxes", reducing clinical adoptability by medical practitioners.

* 💡 **Technical Solution**:
  * Integrated **Contrast Limited Adaptive Histogram Equalization (CLAHE)** to normalize radiograph contrast and sharpen subtle lung consolidations.
  * Utilized **Weighted Focal Loss** with backbone transfer architectures (ResNet / EfficientNet) to penalize misclassifications on hard positive samples.
  * Implemented **Grad-CAM (Gradient-weighted Class Activation Mapping)** visual heatmaps to explicitly display region attributions on X-rays for transparent diagnostic verification.

* **Tech Stack**: `PyTorch` • `OpenCV` • `Grad-CAM` • `Scikit-Learn` • `Python`

---

#### 🎭 02. Emotion Drift Detection System
> **Natural Language Processing & Sentiment Acceleration Dynamics**

* 🛑 **Engineering Challenge**:
  * **Static Model Failures**: Traditional sentiment analysis evaluates messages individually in isolation, failing to track subtle, cumulative emotional decay in multi-turn support conversations.
  * **Delayed Interventions**: Standard sentiment classifiers trigger escalation warnings only after a user reaches extreme frustration, missing early intervention windows.

* 💡 **Technical Solution**:
  * Engineered a **temporal sliding-window transformer pipeline** to calculate sentiment **trajectory**, **velocity**, and **acceleration** over consecutive timestamped utterances.
  * Extracted contextual embeddings using fine-tuned **Hugging Face Transformers** to measure cosine distance shifts between baseline neutral states and negative drift vectors.
  * Built an automated escalation engine that flags high-risk conversations before severe sentiment degradation or churn occurs.

* **Tech Stack**: `Python` • `Hugging Face Transformers` • `PyTorch` • `NLP` • `Pandas`

---

### 📜 Certifications & Credentials

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
  <p><i>Feel free to connect via <a href="https://www.linkedin.com/in/yash-pratap-singh-4542692a0/">LinkedIn</a> or explore my repositories!</i></p>
</div>
