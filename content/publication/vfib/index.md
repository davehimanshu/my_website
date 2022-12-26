---
title: "The volume-filtering immersed boundary method"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Marcus Herrmann
- M. Houssem Kasbaoui

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2022-10-01T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2210.00148"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Submitted to Journal of Computational Physics for review
publication_short: In *ArXiv* (Submitted to *Journal of Computational Physics*)

abstract: We present a novel framework to deal with static and moving immersed boundaries (IB) based on volume-filtering. In this strategy, called Volume-Filtering Immersed Boundary (VFIB) method, transport equations are derived by filtering the Navier-Stokes equations and accounting for stresses at the solid-fluid interface. The result is that boundary conditions that normally apply on the solid-fluid interface are transformed into bodyforces that apply on the right-hand side of the filtered transport equations. In this method, the filter width acts as a parameter that controls the level of resolution. The IB is considered well-resolved if the filter width is much smaller than the characteristic corrugation scale of the interface. There are several innovations in this IB method. First, it sheds light on the role of the internal flow which arises when the transport equations are solved inside the IB. We show that, it is essential to separate stresses due to the external and internal fluids in order to get accurate forces, and provide a method to do so. Second, we show that the volumes associated with Lagrangian forcing points on the boundary depend on the local topology of the surface. We provide a straightforward way to compute these volumes using a triangle tessellation of the interface and the surface density function. Third, we provide an efficient procedure to compute the solid volume fraction, thus, enabling tagging interior/exterior cells. This volume fraction is also involved in the procedure to separate stresses due to the external fluid from the total stresses. Fourth, we show a path forward to extend the VFIB method to Large Eddy Simulations involving IBs. Lastly, we apply the VFIB in several numerical tests involving two- and three- dimensional static and moving IBs. We show greatly improved results compared to prior IB methods. Further, we test several filter kernels and show that, for well-resolved IBs, the choice of the kernel plays little role. 

# Summary. An optional shortened abstract.
summary: A novel approach to the immersed boundaries method based on volume filtering in order to properly formalize the forcing term at the interface and as a consequence obtaining higher accuracy of values computed at the interface. 

tags: []

# Display this page in the Featured widget?
featured: true

# Cover image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Otherwise, specify the `filename` option to load an image from your `assets/media/` folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "The filter is applied to each point in space and it computes the filtered quantity by taking all points within the filter width in account."
  focal_point: ""
  preview_only: false
  alt_text: ""
  # filename: my-image.jpg  # Uncomment to load an image from `assets/media/` instead.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


