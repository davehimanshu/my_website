---
title: Modulation of turbulent structures using inertial particles to achieve drag reduction
summary: We embed inertial particles within a turbulent channel flow and show the ability to destroy vortical structures and augment the mass flow rate within the channel and achieve drag reduction.
tags:
- particle-laden flows
- Turbulent structures
- Drag reduction
date: "2023-01-14T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

A vast majority of woth worlds energy resources (Crude oil and natural gas) are transported through pipelines spanning thousands of miles. Pumping fluids through these pipelines for thousands of miles proves to be a significant challenge requiring pumping stations every 50 miles on average. Advances in efficient fluid transport can bring a transformative impact in the Petroleum and natural gas industry.  

The largest inefficiency within pipelines arises from pressure-losses stemming from the shear stress produced at the walls acting on the fluid. In this project we show that inertial particles introduced within a turbulent channel flow even at semi-dilute volume fractions can significant alter the skin-friction drag at the walls by modifying the coherent flow structures. 

{{< figure src="dr_1.png" caption="A paticle-laden turbulent channel flow at $\mathrm{Re}_\tau = 180$ showing contours of particle volume fraction. Majority of the particles reside in low-speed regions of the flow." numbered="true" >}}

A two-way modulation is observed that is based on particle inertia. Low inertial particles at ($\mathrm{St}^+ = 6$) actually produce a drag increase and reduce the mass flow rate whereas high inertial particles ($\mathrm{St}^+ = 30$) produce drag reduction and increase the mass flow rate. The magnitude of change observed is amplified as the mass loading is increased.  

{{< figure src="dr_2.jpg" caption="Visually looking at the flow shows an increase in mass flow rate compared to the particle-free channel flow with laden with higher inertial particles. Lower inertial particles tend the reduce the mass flow rate compared to the particle-free channel flow" numbered="true" >}}

{{< figure src="dr_3.png" caption="Average streamwise velocity as a function of the wall normal distance for (a) $\mathrm{St}^+ = 6$ and (b) $\mathrm{St}^+ = 30$ at various mass loadings. The solid black line represents the particle-free channel. Darker symbols correspond to larger mass loadings which vary from 0.2-1.0." numbered="true" >}}

Particles modulate the flow structures due to two underlying mechanisms:

1. **Preferential concentration**: The migration of inertial particles from vortical regions to straining regions of the flow.
2. **Turbophoresis**: The migration of inertial particles to lower turbulence regions near the walls. 

In the present research we witness a major distinction between how lower inertial particles segregate themselves within the flow compared to higher inertial particles and how that affects if drag is reduced or augmented. This strongly affects how the low-speed regions of flow are observed. Higher inertial particles which produce a reduction in drag (i.e. increase in mass flow rate) tend to form long ropes near the wall with a relative volume fraction of $\phi/\phi_0 = 3$ or higher. These long ropes reside in the low-speed regions of the flow and help increase the spacing between them in the spanwise direction. This tends to increase the mass flow rate by reducing the number of bursting events from coherent structures. The ropes tend to make the coherent structures more stable around them, overall reducing the amount of wall-shear stress produced. 

{{< figure src="dr_4.png" caption="The formation of stable particles ropes help keep the coherent structures (quasi-streamwise vortices) around them stable for long periods of time. The pink contour shows the particle ropes existing between two counter-rotating vortices." numbered="true" >}}

A remarkable obersvation is how these ropes tend to remain stable for long periods of time. In comparison lower inertial particles are more spread apart into smaller clusters and dont show the same characteristics as higher inertial particles, hence producing an increase in drag.    

- Top-down view of pseudocolor of Particle volume fraction near the wall for $\mathrm{St}^+ = 30$. We observe long streaks of particles (i.e. "ropes") near the wall which remain stable for long periods of time. 
{{< video src="Vfp.mp4" controls="yes" >}}

- Top-down view of pseudocolor of fluid velocity overlayed by particle volume fraction near the wall for particles at $\mathrm{St}^+ = 30$. We observe the long ropes coinciding with the low-speed regions of the flow. 
{{< video src="lss.mp4" controls="yes" >}}

**Related Publications**

- Dave, H. & Kasbaoui, M. H., Mechanisms of drag reduction by semi-dilute inertial particles in turbulent channel flow, Physical Review Fluids, 8, 084305 (08/21/2023).
