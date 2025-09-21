---
title: Vision- and Tactile-Based Continuous Multimodal Intention and Attention Recognition
  for Safer Physical Human-Robot Interaction

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Christopher Yee Wong
- Lucas Vergez
- Wael Suleiman

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-21T16:12:40.710204Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Automation Science and Engineering*'
publication_short: ''

doi: 10.1109/TASE.2023.3276856

abstract: 'Employing skin-like tactile sensors on robots enhances both the safety and usability of collaborative robots by adding the capability to detect human contact. Unfortunately, simple binary tactile sensors alone cannot determine the context of the human contact—whether it is a deliberate interaction or an unintended collision that requires safety manoeuvres. Many published methods classify discrete interactions using more advanced tactile sensors or by analysing joint torques. Instead, we propose to augment the intention recognition capabilities of simple binary tactile sensors by adding a robot-mounted camera for human posture analysis. Different interaction characteristics, including touch location, human pose, and gaze direction, are used to train a supervised machine learning algorithm to classify whether a touch is intentional or not with an F1-score of 86%. We demonstrate that multimodal intention recognition is significantly more accurate than monomodal analyses with the collaborative robot Baxter. Furthermore, our method can also continuously monitor interactions that fluidly change between intentional or unintentional by gauging the user’s attention through gaze. If a user stops paying attention mid-task, the proposed intention and attention recognition algorithm can activate safety features to prevent unsafe interactions. We also employ a feature reduction technique that reduces the number of inputs to five to achieve a more generalized low-dimensional classifier. This simplification both reduces the amount of training data required and improves real-world classification accuracy. It also renders the method potentially agnostic to the robot and touch sensor architectures while achieving a high degree of task adaptability.'

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
  url: https://ieeexplore.ieee.org/document/10144527/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
