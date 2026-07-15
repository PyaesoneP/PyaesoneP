# Hi, I'm Pyae Sone

**Physician-turned-AI Engineer · AI Engineer Intern @ Tiny Equations · SUTD Trailblazers Scholar**

[![Portfolio](https://img.shields.io/badge/Portfolio-Interactive_3D-7c3aed?style=flat&logo=web)](https://pyaesonep.github.io/neural-network-portfolio)
[![Blog](https://img.shields.io/badge/Blog-dev.to-0A0A0A?style=flat&logo=devdotto&logoColor=white)](https://dev.to/pyaesonep)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/pyaesonep)
[![Email](https://img.shields.io/badge/Email-Contact-ea4335?style=flat&logo=gmail)](mailto:pyaesone.perfect2014@gmail.com)

---

I build and evaluate AI systems for high-stakes domains, particularly **healthcare and education**.

My path into computing followed more than five years of medical education and clinical training at the University of Medicine 1, Yangon, including Final Part II postings in Obstetrics & Gynaecology and Paediatrics.

I later graduated from Singapore Polytechnic with a **Diploma in Computer Engineering, Diploma with Merit, and a 3.94/4.00 GPA**. During a cybersecurity internship at Singapore's Land Transport Authority, I worked on endpoint hardening, security monitoring, and adversarial testing, improving measured CIS compliance from **44% to 89%**.

I am currently an **AI/ML Engineer Intern at Tiny Equations**, working on truthful handwriting recognition, OCR/VLM evaluation, educational grading systems, and backend ML pipelines. I will begin SUTD's Computer Science and Design programme in September 2026 as a **Trailblazers International Scholar**.

## Research interests

- Trustworthy multimodal AI and rigorous model evaluation
- OCR, document intelligence, and evidence-preserving AI
- Medical and educational AI
- Robust computer vision and vision-language models
- Local and privacy-conscious inference
- AI security, auditability, and safe failure modes

## Selected work

### [VLM-OCR for Handwritten Essay Feedback](https://github.com/PyaesoneP/vlm-ocr-research)

Empirical evaluation of 14 OCR and vision-language models for handwritten document understanding.

- Built evaluation pipelines for CER, WER, bounding-box IoU, and reading order
- Detected a dataset confound that allowed models to read printed text instead of handwriting
- Rebuilt the benchmark around cropped handwriting and corrected multiple metric bugs
- Investigating how fluent models silently normalise student errors before grading

### [Aegis-MD](https://github.com/PyaesoneP/Aegis-MD)

A local-first emergency-department triage research prototype combining deterministic safety rules, MedGemma, RAG, computer vision, and adversarial safeguards.

- Designed around local inference and privacy-conscious deployment
- Public cloud demonstration available using non-sensitive inputs
- 332 backend tests with 94% coverage
- Includes CI/CD, Docker deployment, monitoring, and prompt-injection defences
- Research prototype only; not clinically validated

### [Convolutional Neural Network from Scratch](https://github.com/PyaesoneP/custom-nn)

A CNN implemented in pure NumPy without deep-learning frameworks.

- Manual forward and backward propagation through Conv2D, MaxPool, and Dense layers
- Vectorised convolution using `im2col` and `col2im`
- Adam optimisation, regularisation experiments, FastAPI deployment, and monitoring
- Documents both successful approaches and experiments that failed

### [Interactive Neural-Network Portfolio](https://github.com/PyaesoneP/neural-network-portfolio)

A Three.js portfolio that represents my projects, skills, and career progression as an animated neural network with real-time data flow and BFS path tracing.

## Writing

### [Same weights, same prompt, different triage level](https://dev.to/pyaesonep/same-weights-same-prompt-different-triage-level-475i)

An engineering investigation into why quantised models can produce different outputs across hardware and what this means for reproducibility in safety-sensitive AI.

## Technical toolkit

**ML and research:**  
`Python` · `PyTorch` · `TensorFlow` · `NumPy` · `Hugging Face` · `OpenCV` · `Scikit-learn`

**ML systems:**  
`FastAPI` · `Docker` · `Ollama` · `llama.cpp` · `RAG` · `Prometheus` · `CI/CD`

**Cloud and infrastructure:**  
`Google Cloud` · `Cloud Run` · `Vertex AI` · `Linux` · `Kubernetes fundamentals`

**Security:**  
`Endpoint hardening` · `CrowdStrike Falcon` · `Microsoft Sentinel` · `Red/Purple Teaming` · `AI Security`

## Currently

- Building truthful OCR and multimodal evaluation pipelines
- Strengthening algorithms, mathematics, PyTorch, and ML systems foundations
- Preparing to begin SUTD Computer Science and Design in September 2026
- Open to **UROP and undergraduate research opportunities** in trustworthy AI, computer vision, medical AI, and educational AI
- Targeting AI/ML and software-engineering internships for late 2027