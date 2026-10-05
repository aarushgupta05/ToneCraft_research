# ToneCraft Research

**AI-powered guitar tone modeling, integrated multi-effect parameter prediction, and guitar effects simulation.**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23129629.svg)](https://doi.org/10.5281/zenodo.23129629)

🌐 **ToneCraft:** https://www.tonecraft.tech  
📦 **Research Dataset:** https://doi.org/10.5281/zenodo.23129629

---

## Overview

ToneCraft is an AI-driven framework for predicting and recreating electric-guitar tones across an integrated multi-effect signal chain.

Instead of estimating one effect at a time, ToneCraft jointly predicts **16 continuous parameters** spanning six effects:

- Overdrive
- Distortion
- 3-band EQ
- Chorus
- Delay
- Reverb

The predicted parameters can be rendered through the ToneCraft FAUST-based DSP engine and used in the web simulator or guitar-effects plugin.

---

## Research Dataset

The **ToneCraft Dataset v1.0.1** is archived on Zenodo with a permanent DOI.

### Dataset contents

| Split | Processed WAV | JSON Labels | Clean DI WAV |
|---|---:|---:|---:|
| Training | 11,904 | 11,904 | 53 |
| Validation | 965 | 965 | 11 |
| Test | 996 | 996 | 13 |
| **Total** | **13,865** | **13,865** | **77** |

Each processed example contains:

- a rendered guitar-audio `.wav` file
- a corresponding `.json` metadata file
- exact effect/control parameter values
- dataset split and sampling information
- tone scenario
- quality-control measurements
- source DI information
- dataset version and provenance metadata

### Access

The Zenodo metadata record is public and permanently citable.

The dataset files are **restricted and available to researchers and educators upon request**.

➡️ **View dataset / request access:**  
https://doi.org/10.5281/zenodo.23129629

---

## Tone Scenarios

The dataset includes structured parameter combinations across four broad guitar-tone scenarios:

- **Clean**
- **Crunch**
- **High-Gain**
- **Temporal**

---

## Predicted Parameters

### Overdrive
- Drive

### Distortion
- Drive
- Tone

### 3-Band EQ
- Bass
- Mid
- Treble

### Chorus
- Rate
- Depth
- Mix

### Delay
- Time
- Feedback
- Mix

### Reverb
- T60
- Damping
- Size
- Wet Mix

---

## Research Goals

ToneCraft investigates whether a single machine-learning model can recover the controls of a complete guitar multi-effect chain directly from audio.

The project focuses on:

- integrated multi-effect parameter estimation
- guitar-tone modeling
- music information retrieval
- machine learning for audio
- digital signal processing
- reproducible audio-effects research
- practical deployment through web and plugin environments

---

## Repository

This repository will contain research and reproducibility material associated with ToneCraft, including:

- dataset documentation
- example data and metadata
- model and architecture documentation
- evaluation results
- DSP information
- research papers and presentations
- example scripts and utilities
- citation information

The full research dataset is hosted separately on Zenodo rather than directly in this GitHub repository.

---

## Citation

If you use the ToneCraft dataset, please cite:

> Gupta, A. (2026). *ToneCraft Dataset: Integrated Multi-Effect Parameter Prediction and Guitar Effects Simulation* (Version 1.0.1) [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.23129629

---

## Creator

**Aarush Gupta**  
United World College South East Asia, East Campus, Singapore

---

## Links

- **ToneCraft:** https://www.tonecraft.tech
- **Zenodo Dataset:** https://doi.org/10.5281/zenodo.23129629

---

## Dataset License

The dataset is distributed under the **ToneCraft Dataset Research Use Terms**.

Access is provided to approved requesters for research and educational purposes. Redistribution, republication, public sharing, sublicensing, or transfer of the dataset or substantial portions of it is not permitted without prior written permission from the dataset creator.
