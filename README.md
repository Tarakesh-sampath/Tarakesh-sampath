# Hi, I'm Tarakeshwaran Sampath 👋

ML engineer working across the full stack of model training — from fine-tuning speech models on a laptop to profiling and expanding LLMs on datacenter-class GPUs.

## 🔭 What I'm working on now

**LLM training efficiency** (private repos): figuring out which transformer layers actually matter and using that to train smarter, not bigger.

- Layer-importance profiling of open LLMs (Gemma family) across datasets
- Block expansion — growing a model by inserting new layers where profiling says they'll help, then continued pretraining (CPT) and instruction tuning (IFT) of the expanded model
- Scaling this from single-GPU to FSDP-sharded multi-GPU training
- Serving and benchmarking checkpoints with vLLM (OpenAI-compatible endpoints, Docker Compose)

**Quantum machine learning**: [Interference-quantum-classifier](https://github.com/Tarakesh-sampath/Interference-quantum-classifier) — a measurement-free, coherence-preserving hybrid quantum–classical classifier. Interested in quantum feature encoding and variational quantum algorithms.

## 🧰 Things I've built

### Speech & audio
- [Finetuning-whisper-model-with-LoRA-int-8](https://github.com/Tarakesh-sampath/Finetuning-whisper-model-with-LoRA-int-8) — parameter-efficient Whisper fine-tuning
- [Faster-whisper-peft](https://github.com/Tarakesh-sampath/Faster-whisper-peft) — running PEFT-tuned Whisper on the CTranslate2 backend
- [Whisper_Dataset_generator](https://github.com/Tarakesh-sampath/Whisper_Dataset_generator) — building custom ASR datasets
- [Streaming-ASR](https://github.com/Tarakesh-sampath/Streaming-ASR) and [ASR-Docker](https://github.com/Tarakesh-sampath/ASR-Docker) — real-time transcription and a containerized ASR API
- [Audio_classifier](https://github.com/Tarakesh-sampath/Audio_classifier) — audio classification experiments

### Vision
- [FaceDetection-MTCNN](https://github.com/Tarakesh-sampath/FaceDetection-MTCNN) and [Deep-Face-detection-tf-data_preparation](https://github.com/Tarakesh-sampath/Deep-Face-detection-tf-data_preparation) — face detection, including building the training dataset from scratch with Albumentations
- [Automated-Dental-Diagnosis](https://github.com/Tarakesh-sampath/Automated-Dental-Diagnosis) — ML-assisted dental imaging diagnosis

### Systems & hardware
- [Neuro-Emulator](https://github.com/Tarakesh-sampath/Neuro-Emulator) / [Gbemu](https://github.com/Tarakesh-sampath/Gbemu) — a Game Boy emulator in C++, exploring how far neural networks can go simulating the actual chip components
- [Tcp-IP-Visualiser](https://github.com/Tarakesh-sampath/Tcp-IP-Visualiser) — visualizing the TCP/IP stack in Java
- [AUTO-LFS](https://github.com/Tarakesh-sampath/AUTO-LFS) — shell tooling to auto-install git-lfs where it's missing

### Earlier ML work
- Battery modeling: [state-of-health estimation](https://github.com/Tarakesh-sampath/State-of-Health-Estimation-Battery), [depth-of-discharge estimation](https://github.com/Tarakesh-sampath/DOD-Estimation-Of-Battery), and [black-box battery models](https://github.com/Tarakesh-sampath/Battery-Modeling-Black-Box-Model)
- [EcoGuardsX](https://github.com/Tarakesh-sampath/EcoGuardsX) — Hack-o-Holic 5.0 hackathon project
- [Doc-ranker](https://github.com/Tarakesh-sampath/Doc-ranker) — document ranking / retrieval experiments

### Community
- Built web tools for my college's Youth Red Cross unit: [attendance](https://github.com/Tarakesh-sampath/YRC-Attendence), [homepage](https://github.com/Tarakesh-sampath/yrc-homepage), and [CrossLink](https://github.com/Tarakesh-sampath/CrossLink) for connecting members and events

## 🌱 Currently exploring

- Distributed training (FSDP/DDP) beyond single-GPU setups
- Quantum feature encoding and scalable quantum classifiers
- Offensive-security tooling from the ML side ([CVE2CAPEC](https://github.com/Tarakesh-sampath/CVE2CAPEC), [Pentest-R1](https://github.com/Tarakesh-sampath/Pentest-R1-fork))

## 💻 Stack

**ML**: ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) Hugging Face transformers / PEFT, vLLM, OpenCV, scikit-learn, NumPy / Pandas / Matplotlib

**Infra**: ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) CUDA, uv, git, Bash

**Also write**: ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

## 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/tarakeshwaran-sampath)
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:tarakeshwaran.sampath@gmail.com)
