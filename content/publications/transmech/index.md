---
title: "Actuation of Dynamic Morphing Wing"
authors:
- Bibek Gupta
- me
- Eric Sihite
- Alireza Ramezani
date: "2025-12-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ASME Transactions on Mechatronics (Under Review)"
publication_short: ""

abstract: Bat-inspired morphing wings offer promising pathways for agile flight in micro aerial vehicles, yet their implementation remains challenging due to morphological complexity and power constraints. This paper presents a morphing wing platform with embedded string-actuated regulators that enable aerodynamic force modulation through minimal mechanical actuation. We develop a mathematical framework coupling rigidbody dynamics with unsteady aerodynamics using lifting-line theory and Wagner’s function to capture circulation development and vortex wake evolution. The regulator mechanism adjusts effective linkage length to modify wing kinematics during flapping. Experimental validation using a tethered two-segment wing at 5 Hz flapping frequency demonstrates that regulator displacements of only 1.5 mm produce 26.3% increases in peak vertical force while shifting peak force timing from 35% to 47% of downstroke duration. Simulations reveal that these force modulations result from alterations in spanwise circulation distribution, with 15–29% circulation enhancement concentrated in outer wing regions where moment arms are maximized. Although simulations underestimate absolute force magnitudes due to idealized modeling assumptions, they correctly predict qualitative trends and circulation redistribution. The results validate that strategic placement of low-power actuators within compliant morphing structures can yield substantial aerodynamic control authority, demonstrating the feasibility of morphology-centered flight control strategies for resource-constrained micro aerial vehicles

tags:
- Mechanical Engineering
- Acutator
- Aerodynamics
- Piezoelectric
- UAV
- Flapping Wing
- Aerial
- Robot

featured: true


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