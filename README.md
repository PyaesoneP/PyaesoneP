# Hi, I'm Pyae Sone

**Physician-turned-AI Engineer · AI Engineer Intern @ Tiny Equations · SUTD Trailblazers Scholar**

[![Portfolio](https://img.shields.io/badge/Portfolio-Interactive_3D-7c3aed?style=flat&logo=web)](https://pyaesonep.github.io/neural-network-portfolio)
[![Blog](https://img.shields.io/badge/Blog-dev.to-0A0A0A?style=flat&logo=devdotto&logoColor=white)](https://dev.to/pyaesonep)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/pyaesonep)
[![Email](https://img.shields.io/badge/Email-Contact-ea4335?style=flat&logo=gmail)](mailto:pyaesone.perfect2014@gmail.com)

---

I spent five years in clinical medical training before moving into offensive security and machine learning. During a red-teaming internship at LTA Singapore, I raised endpoint security compliance from 44% to 89%. I'm now an AI Engineer Intern at **Tiny Equations**, working on computer vision for an education platform built to make quality learning support accessible to any student.

My focus is AI for high-stakes domains that **fails safely**: LLM security, local and on-device inference, and rigorous evaluation. On the side, I run a free Burmese-language initiative teaching AI/ML, because access to this field shouldn't depend on where you start.

*Open to AI/ML engineering internships for late 2027.*

---

### What I'm building

* **[Aegis-MD](https://github.com/PyaesoneP/Aegis-MD)** is a local-first emergency-department triage console. A deterministic rules engine drives Australasian Triage Scale (ATS 1-5) classification, with a MedGemma-1.5 4B escalation layer, RAG over clinical guidelines, and parallel computer-vision risk stratification. All inference runs on-device behind a custom prompt-injection gateway. Hardened with 332 backend tests at 94% coverage, CI/CD, and Prometheus observability.
* **[vlm-ocr-research](https://github.com/PyaesoneP/vlm-ocr-research)** benchmarks open-source OCR and vision-language models for on-device document understanding. I built the evaluation harness (CER/WER, layout IoU, reading order) and caught a dataset confound that was silently inflating accuracy, then re-ran everything on cropped handwriting for honest numbers.
* **[custom-nn](https://github.com/PyaesoneP/custom-nn)** is a convolutional neural network built from scratch in pure NumPy, with no frameworks. Manual forward/backprop through Conv2D, MaxPool, and Dense layers, Adam with decoupled weight decay, and custom activations, including documented experiments that didn't work. Deployed full stack via FastAPI and Docker, with a live monitoring dashboard.
* **[neural-network-portfolio](https://github.com/PyaesoneP/neural-network-portfolio)** is an interactive 3D portfolio in Three.js that renders my skills and career history as an animated neural network, with real-time data flow and BFS path tracing.

---

### Writing

* **[Same weights, same prompt, different triage level](https://dev.to/pyaesonep/same-weights-same-prompt-different-triage-level-475i)** explains why a quantized model can return different outputs on different hardware, and why that's a problem for safety-critical AI. *(dev.to)*

---

### Tech stack

| Category | Technologies |
| :--- | :--- |
| **AI / ML** | PyTorch, TensorFlow, Keras, Hugging Face, RAG, LLMs, OpenCV, Scikit-learn, Pandas, NumPy |
| **MLOps & Cloud** | Docker, Kubernetes (k3s), GCP, Cloud Run, Vertex AI, CI/CD, FastAPI |
| **Security** | Red Teaming, Prompt-Injection Defense, CrowdStrike Falcon, Microsoft Sentinel |
| **Languages** | Python, JavaScript, C/C++, SQL, PowerShell |
