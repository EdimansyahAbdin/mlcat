---
title: ML-CAT Adaptive PHQ-8 and GAD-7 Assessment
emoji: 🧠
colorFrom: blue
colorTo: green
sdk: docker
app_port: 7860
pinned: false
license: mit
short_description: ML-CAT adaptive PHQ-8 & GAD-7 assessment
---

# ML-CAT: Adaptive PHQ-8 & GAD-7 Assessment

**Machine Learning-Based Computerized Adaptive Testing**  
Abdin, Jeyagurunathan, Mok, Feng, Subramaniam — IMH Singapore

---

## What this app does

This Shiny app implements **ML-CAT** for PHQ-8 (depression) and GAD-7 (anxiety)
using the M5P model tree. Each patient answers only **3–4 adaptive items** instead
of the full scale, with near full-scale accuracy:

| Scale | r | R² | MAE |
|-------|---|----|-----|
| PHQ-8 | 0.996 | 0.979 | 0.756 |
| GAD-7 | 0.997 | 0.985 | 0.610 |

## How to use

1. Select **GAD-7** (anxiety) or **PHQ-8** (depression)
2. Answer 3–4 adaptive questions
3. View estimated score and severity level
4. Download results as CSV or Excel

## Citation

Abdin E, Jeyagurunathan A, Mok YM, Feng M, Subramaniam M.  
*Optimizing PHQ-8 and GAD-7 Administration Using ML-CAT.*  
Institute of Mental Health, Singapore.

> ⚠️ For clinical monitoring purposes only. Does not replace clinical judgment.
