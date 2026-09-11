---
title: Robust tube-based economic model predictive control of nonlinear systems using
  linear parameter varying approach

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Heithem Boufrioua
- Boubekeur Boukhezzar
- Vicenç Puig

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-09-11T15:31:12.770225Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of the Franklin Institute*'
publication_short: ''

doi: https://doi.org/10.1016/j.jfranklin.2026.108409

abstract: Model Predictive Control (MPC) has become a powerful framework for optimizing
  system performance under constraints. However, when applied to nonlinear systems
  subject to unknown but bounded uncertainties (UBB), conventional MPC approaches
  face significant challenges related to computational complexity and robustness.
  This paper proposes a robust tube-based economic model predictive control (REMPC)
  method using a linear parameter-varying (LPV) approach for nonlinear systems with
  unknown but bounded uncertainty, based on nominal predictions. Using a nonlinear
  embedding approach, the nonlinear model is transformed into an LPV model. The optimal
  states and inputs found from solving the previous optimization problem are used
  to estimate the scheduling variables along the prediction horizon while executing
  the receding horizon strategy. This approach converts the nonlinear optimization
  problem into a quadratic optimization problem, effectively reducing computational
  time by leveraging the efficiency inherent in the LPV formulation. Recursive feasibility
  and input-to-state stability are guaranteed. Recursive feasibility is ensured by
  tighter constraints, which are computed online using a zonotopic approach based
  on the disturbance reachable sets. A gain-scheduling H∞ controller is employed as
  the local controller to further tighten these constraints. The stability of the
  proposed approach is ensured by forcing the terminal state to converge towards the
  optimal equilibrium or working point of the system. Moreover, the terminal constraint
  is relaxed by using a constraint set around the terminal state instead of a constraint
  value and adding a penalty on the terminal state in the cost function. Additionally,
  strict dissipativity is established as a sufficient condition to prove stability.
  Finally, the effectiveness of the LPV-based REMPC strategy is demonstrated by controlling
  an isothermal Continuous Stirred Tank Reactor (CSTR), and an REMPC-LPV-based planning
  approach for a 1/10 scale autonomous remote-controlled (RC) electric car is also
  tested through simulations.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Input-to-state stability
- Recursive feasibility
- Robust economic model predictive control
- Zonotopes
- Gain scheduling
- Linear parameter-varying approach

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0016003226000098
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
