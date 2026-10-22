---
title: "Modeling and Removal of Electronic Crosstalk Effects in Ultrasound Signals via Deconvolution"

authors:
  - Fábio Z. Y. Wang
  - Tatiana de A. Prado
  - me
  - Gustavo P. Pires
  - Glauber Brante
  - Daniel R. Pipa
  - Thiago A. R. Passarin

date: "2026-06-15T00:00:00Z"
publishDate: "2026-10-22T00:00:00Z"

publication_types: ["paper-conference"]
publication: "Proceedings of the 14th European Conference on Non-Destructive Testing (ECNDT 2026)"
publication_short: "ECNDT 2026"

abstract: "The performance of an ultrasound array transducer is typically impaired by element-to-element interference, also known as crosstalk. The various approaches for reducing crosstalk generally involve modifying the transducer design or controlling the excitation waveforms. In this paper, we propose a method for modeling and removing electronic reception crosstalk in post-processing, which can serve as an alternative, or even a complement, to existing approaches. The modeling consists of estimating N(N-1) Finite Impulse Responses (FIRs) that represent the effect that each (N-1)-th channel of the Phased Array (PA) has on the other channels. To obtain this modeling, we have performed controlled acquisitions that capture supposedly ideal signals (free from crosstalk) on one channel at a time, physically blocking the remaining channels. As a consequence, blocked channels will only capture electronic crosstalk. After the modeling stage, crosstalk removal from arbitrary datasets acquired with the modeled PA is performed via a Tikhonov-regularized inverse problem using the estimated FIRs. Experimental results show that the proposed method is able to improve the Signal-to-Interference-plus-Noise Ratio (SINR) by up to 13.4 dB"
summary: ""

tags:
  - Ultrasonic Testing (UT)
  - Signal processing
  - Electronic crosstalk
  - Deconvolution

featured: true

hugoblox:
  ids:
    doi: 10.58286/33474

links:
  - type: pdf
    url: ECNDT2026_ID_765.pdf

  - type: slides
    url: ECNDT2026_PRESENTATION_765.pdf

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---