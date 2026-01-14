---
title: "Ultrasonic sectorial inspection in the presence of temperature gradients"
authors:

- Mateus Y. Müller
- Tatiana A. Prado
- me
- Thiago A. R. Passarin
- Daniel R. Pipa

date: "2023-08-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Research and Review Journal of Nondestructive Testing*"
publication_short: ""

abstract: Ultrasonic nondestructive testing is a precise tool for equipment inspections. Among the usual methods, sectorial scanning stands out within contact-based techniques, as it provides broad angular sweeps without the need to physically steer the transducer, and the configuration of the beams hinges on the geometry of the tested objects. However, in high-temperature scenarios (e.g., oil treatment vessels), thermal gradients along the propagation path result in inaccurate sizing of discontinuities, given that the presence of such gradients is responsible for variations in the velocities and distortions of the ultrasonic beams. This paper proposes a method to compensate for these distortions during the sectorial inspection. Optimal linear approximation parameters are determined offline from a controlled Full Matrix Capture (FMC) test, in which the setup consists of a phased array transducer, a high-temperature resistant wedge and an aluminium test block with flaws at known positions. The positions of the flaws are measured on the Total Focusing Method (TFM) reconstructions, and the parametric velocity models for specific instants of heating time are estimated through the minimization of a cost function. Then, focal laws are calculated from the parameters using the ray tracing technique and stored in a text file to be interpreted by the instruments as a native focal law. An online test is proposed for validating the method at the controlled temperature of 70oC. The results show that the positions of the flaws, and the distance between them in the S-scan image, present improved accuracy (with errors reduced by approximately 64%) when the proposed correction is applied.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Non-Destructive Testing (NDT)
- Ultrasound imaging
- Weld bead inspection
- Temperature induced distortion

featured: true

hugoblox:
  ids:
    doi: 10.58286/28122

links:
  - type: pdf
    url: ECNDT2023_PAPER_269.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Mueller et al. 2023**](https://www.ndt.net/search/docs.php3?id=28119)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
