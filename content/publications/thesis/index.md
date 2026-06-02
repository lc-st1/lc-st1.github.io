---
title: "Thrust Regulation Through Wing Linkage Modulation on the Aerobat Platform: Piezoelectric Slip-Stick Actuated Regulator Development"
authors:
- me
date: "2026-05-28T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Aerobat is a bat-inspired flapping-wing robot with a wing gait generate by the computational structure, a planar linkage of carbon fiber links driven by a single motor. This design minimizes weight but couples both wings to a shared input motor, eliminating independent thrust control and preventing asymmetric maneuvers. This thesis investigates thrust regulation by modifying the effective length of the first radius link R1 in the computational structure. Static experiments using FDM-printed R1 links at three lengths (28.58, 29.33, and 30.08 mm) across 3,4, and 5 Hz flapping frequencies demonstrated that a 1.5 mm length increase produced a 37% increase in peak lift force and shifted peak force timing within the downstroke. An additional experiment using a string-actuated regulator mechanism was performed. Further actuation methods were evaluated sub-gram micro-servo and piezoelectric slip-stick. After both the string-tension and micro-servo actuation methods failed due to structural member compliance and motor fragility respectively, a TULA-50 piezoelectric slip-stick actuator was selected. Multiple force-amplifying mechanisms were prototyped, resulting in a direct-drive variable-length mechanism. This final mechanism was demonstrated in a preliminary bench-top test, though insufficient force output prevented dynamic testing during flapping. This work establishes linkage-length modulation via embedded slip-stick actuation as a viable approach to independent wing thrust control.

tags:
- Mechanical Engineering
- Acutator
- Piezoelectric
- UAV
- Flapping Wing
- Aerial
- Robot

featured: true

links:
- type: preprint
  provider: arxiv
  id: 2604.18900

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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