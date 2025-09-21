---
title: Sensor Observability Analysis for Maximizing Task-Space Observability of Articulated Robots

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Christopher Yee Wong
- Wael Suleiman

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-21T16:12:40.694612Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Robotics*'
publication_short: 'T-RO'

doi: 10.1109/TRO.2024.3443696

abstract: We propose a novel performance metric for articulated robots with distributed
  directional sensors called the sensor observability analysis (SOA). These robot-mounted
  distributed directional sensors (e.g., joint torque sensors) change their individual
  sensing directions as the joints move. SOA transforms individual sensor axes in
  joint space to provide the cumulative sensing quality of these sensors to observe
  each task-space axis, akin to forward kinematics for sensors. For example, certain
  joint configurations may align joint torque sensors in such a way that they are
  unable to observe interaction forces in one or more task-space (e.g., Cartesian)
  axes. The resultant sensor observability performance metrics can then be used in
  optimization and in null-space control to avoid sensor observability in singular
  configurations or to maximize sensor observability in particular directions. We
  use the specific case of force sensing in serial robot manipulators to showcase
  the analysis. Parallels are drawn between sensor observability and traditional kinematic
  manipulability; SOA is shown to be more generalizable in terms of analyzing non-joint-mounted
  sensors and can potentially be applied to sensor types other than for force sensing.
  Simulations and experiments using a custom 3-degree of freedom robot and the Baxter
  robot demonstrate the utility and importance of sensor observability in physical
  interactions.

# Summary. An optional shortened abstract.
summary: ''

tags: []

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
  url: https://ieeexplore.ieee.org/document/10637753/
---
