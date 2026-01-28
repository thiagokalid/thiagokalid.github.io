---
title: Machine learning–driven flaw detection for ultrasonic pipe inspections with acoustic lens
date: 2025-12-20
draft: false
summary: "Anomaly-detection models to help flaw detection process."

links:

tags:
  - Machine Learning (ML)
  - Acoustic lens
  - Ultrasonic testing (UT)
  - Non-destructive testing (NDT)
---

**Abstract:**

Acoustic lenses have been recently employed during ultrasonic pipe inspection to increase the phased-array transducer coverage area. However, the lens also introduces geometrical artefacts, which affect the flaw detection process. Classic flaw detection methodologies commonly rely on thresholding, which becomes problematic when geometrical artifacts closely match the desired signal amplitude. We propose an adaptive method for flaw detection from ultrasonic inspections of tubes with acoustic lenses based on anomaly detection techniques. A  machine-learning model was trained on data from flawless pipe specimens using an acoustic lens. During training, the model captures patterns associated with the flawless pipe and lens. Then, during testing, it analyzes newly observed data and classifies it either as a flaw (anomaly) or a normal response (as in the training set). Our model, based on the Local Outlier Factor, achieved an area under the receiver operating characteristic curve of 0.96, a global accuracy of 0.95, a recall of 0.91, and an F2-score of 0.84. These results, achieved across a wide range of flaw geometries, suggest that our model could be part of an automated flaw detection system for pipeline inspections.