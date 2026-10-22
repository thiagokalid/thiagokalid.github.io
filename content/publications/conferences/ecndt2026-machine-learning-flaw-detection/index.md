---
title: "Machine learning-driven flaw detection for ultrasonic pipe inspections with acoustic lens"

authors:
  - me
  - André E. Lazzaretti
  - Tatiana de A. Prado
  - Gustavo P. Pires
  - Daniel R. Pipa
  - Thiago A. R. Passarin

date: "2026-06-15T00:00:00Z"
publishDate: "2026-10-22T00:00:00Z"

publication_types: ["article-journal"]
publication: "Proceedings of the 14th European Conference on Non-Destructive Testing (ECNDT 2026)"
publication_short: "ECNDT 2026"

abstract: Acoustic lenses have been recently employed during ultrasonic pipe inspection to increase the phased-array transducer coverage area. However, the lens also introduces geometrical artefacts, which affect the flaw detection process. Classic flaw detection methodologies commonly rely on thresholding, which becomes problematic when geometrical artifacts closely match the desired signal amplitude. We propose an adaptive method for flaw detection from ultrasonic inspections of tubes with acoustic lenses based on anomaly detection techniques. A machine-learning model was trained on data from flawless pipe specimens using an acoustic lens. During training, the model captures patterns associated with the flawless pipe and lens. Then, during testing, it analyzes newly observed data and classifies it either as a flaw (anomaly) or a normal response (as in the training set). Our model, based on the Local Outlier Factor, achieved an area under the receiver operating characteristic curve of 0.96, a global accuracy of 0.95, a recall of 0.91, and an F2-score of 0.84. These results, achieved across a wide range of flaw geometries, suggest that our model could be part of an automated flaw detection system for pipeline inspections.

summary: ""

tags:
  - Non-destructive testing
  - Acoustic lens
  - Ultrasonic testing
  - Machine learning
  - Automated defect detection

featured: true

hugoblox:
  ids:
    doi: 10.58286/33475

links:
  - type: pdf
    url: "ECNDT2026_ID_768.pdf"

  - type: slides
    url: ECNDT2026_PRESENTATION_768.pdf

  - type: custom
    label: Code & Dataset
    url: https://zenodo.org/records/19410833
image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---