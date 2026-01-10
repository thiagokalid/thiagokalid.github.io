---
title: "Virtual encoder: a two-dimension visual odometer for NDT"
authors:

- me
- Everton Trento Jr.
- Tatiana A. Prado
- Gustavo P. Pires
- Giovanni A. Guarneri
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

abstract: Odometer information is an important feature of NDT systems for inspection procedures that involve mechanical scanning. Knowledge of transducer position during the inspection allows for the localization of flaws and the fusion (stitching) of several images into more sophisticated representations of the inspected object. Commercial encoders provide NDT systems with accurate realtime displacement information that can be integrated to obtain odometry. However, this information is typically limited to a single axis. Although composite schemes with more than one encoder can be built to provide 2-D or 3-D spatial information, they are mechanically intricate and lack flexibility and ease of use. We propose a 2-D position-tracking solution that is based on image processing. A miniature camera continuously captures images of the external surface of the inspected object, which are fed to an algorithm that detects and stores 2-D displacement between each pair of consecutive images. Additionally, the orientation quaternions provided by an Inertial Measurement Unit are stored, allowing for posterior 3-D path reconstruction over objects of known geometries, such as oil pipes. Besides logging position and orientation histories, the device also provides real-time displacement information to the NDT system, where it is perceived as a set of single-axis encoders, thus termed “the virtual encoder”. We demonstrate the applicability of the device to both contact and immersion ultrasonic inspections. The results show that the concept is promising, despite being based on simple principles and relatively easy to implement. The source code is provided as additional material in https://github.com/thiagokalid/VirtualEncoder-ECNDT-2023.
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Non-Destructive Testing (NDT)
- Motion Estimation
- Visual-odometry
- Downward-facing camera
featured: true

hugoblox:
  ids:
    doi: 10.58286/28119

links:
  - type: pdf
    url: ECNDT2023_PAPER_264.pdf

  - type: code
    url: https://github.com/thiagokalid/Virtual-Encoder-ECNDT-2023

  - type: video
    url: https://www.youtube.com/watch?v=36NNLRFJXkg

  - type: slides
    url: ECNDT2023_PRESENTATION_264.pdf

  - type: poster
    url: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Kalid et al. 2023**](https://www.ndt.net/search/docs.php3?id=28119)'
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
