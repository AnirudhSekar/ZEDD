# Zero-Shot Embedding Drift Detection (ZEDD)

**A Lightweight Defense Against Prompt Injection in Instruction-Following LLMs**

## Overview
ZEDD is a **zero-shot, embedding-based detection method** designed to identify semantic drift caused by **prompt injection attacks** in instruction-following large language models (LLMs). 

Without requiring fine-tuning upon each detection, ZEDD flags adversarial inputs by monitoring deviations in embedding distributions using statistical models like **Gaussian Mixture Models (GMM)** and **Kernel Density Estimation (KDE)**.


## Features
- **Zero-shot detection** – no task-specific retraining required.  
- **Embedding-based anomaly detection** – tracks semantic drift in embedding space.  
- **Flexible statistical detectors** – supports GMM, KDE, etc.  
- **Adaptive thresholds** – adjust sensitivity to balance detection vs. false positives.  

## Download and Usage
```bash
git clone https://github.com/MrinalA2009/ZEDD.git
cd ZEDD
```
Now you can either open in Google Colab or run
```bash
jupyter notebook Zero_Shot_Embedding_Drift_Detection_A_Lightweight_Defense_Against_Prompt_Injection_in_Instruction_Following_LLMS.ipynb
```
to open and run in any other Jupyter-Notebook based platform.





