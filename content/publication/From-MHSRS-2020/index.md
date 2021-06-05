---
title: "From the DESK (Dexterous Surgical Skill) to the Battlefield - A Robotics Exploratory Study"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.

# do not use dot at the end of author name (confirm?)
authors:
- Glebys Gonzalez
- Upinder Kaur
- admin
- Vishnunandan Venkatesh
- Natalia Sanchez-Tamayo
- Gregory Hager
- Yexiang Xue
- Richard Voyles
- Juan Wachs

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Military Health System Research Symposium Journal (Military Medicine) 
publication_short: MHSRS Journal (Military Medicine) 2020

abstract:  Short response time is critical for future military medical operations in austere settings or remote areas. Such effective patient care at the point of injury can greatly benefit from the integration of semi-autonomous robotic systems. To achieve autonomy, robots would require massive libraries of maneuvers. While this is possible in controlled settings, obtaining surgical data in austere settings can be difficult. Hence, in this paper, we present the Dexterous Surgical Skill (DESK) database for knowledge transfer between robots. The peg transfer task was selected as it is one of 6 main tasks of laparoscopic training. Also, we provide a ML framework to evaluate novel transfer learning methodologies on this database. The collected DESK dataset comprises a set of surgical robotic skills using the four robotic platforms- Taurus II, simulated Taurus II, YuMi, and the da Vinci Research Kit. Then, we explored two different learning scenarios- no-transfer and domain-transfer. In the no-transfer scenario, the training and testing data were obtained from the same domain; whereas in the domain-transfer scenario, the training data is a blend of simulated and real robot data that is tested on a real robot. Using simulation data enhances the performance of the real robot where limited or no real data is available. The transfer model showed an accuracy of 81% for the YuMi robot when the ratio of real-to-simulated data was 22%-78%. For Taurus II and da Vinci robots, the model showed an accuracy of 97.5% and 93% respectively, training only with simulation data. Results indicate that simulation can be used to augment training data to enhance the performance of models in real scenarios. This shows the potential for future use of surgical data from the operating room in deployable surgical robots in remote areas.

# Summary. An optional shortened abstract.
summary: Teleoperated Robotic Surgery; Surgical activity recognition; Surgical vision and perception

tags: [Surgical Robotics]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2011.15100.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'DESERTS framework.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Robotic Surgery

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
