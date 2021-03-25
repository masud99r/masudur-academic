---
title: "SARTRES: A Semi-Autonomous Robot TeleopeRation Environment for Surgery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Mythra V. B. S. Mur
- Mridul Agarwal
- Upinder Kaur
- Vishnunandan L. Venkatesh
- Glebys Gonzalez
- Natalia Sanchez Tamayo
- Yexiang Xue
- Richard Voyles
- Vaneet Aggarwal
- Juan Wachs

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Biomechanics and Biomedical Engineering - Imaging & Visualization (Presented at AE-CAI | CARE | OR 2.0 Joint MICCAI Workshop)
publication_short: TCIV 2020

abstract: Teleoperated surgical robots can provide immediate medical assistance in austere and hostile environments. However, such scenarios are time-sensitive and thus, require highbandwidth and low-latency communication links which might be unavailable. Systems with a higher degree of autonomy can address these issues as they can operate even with intermittent feedback from the surgeon. The system presented in this paper has a standard surgical teleoperation interface, which provides surgeons with an environment on which they are trained. In our semi-autonomous robotic framework, high level instructions are inferred from the surgeon's actions and then executed semi-autonomously on the robot. The framework consists of two main modules - (i) Recognition Module - which recognizes atomic sub-tasks (i.e., surgemes) performed at the operator end, and (ii) Execution Module - which executes the identified surgemes at the robot end using task contextual information. The peg transfer task was selected for this paper due to its importance in laparoscopic surgical training. The experiments were performed on the DESK surgical dataset to show the effectiveness of our framework using two metrics - user intervention, measured in terms of degree of autonomy, and success rateof surgeme execution. We achieved an average accuracy of 91.5% for surgeme recognition and a success rate of 86% during surgeme execution. Furthermore, we obtained an average success rate of 53.9% for the overall task, using a model-based approach with a degree of autonomy of 99.33%.

# Summary. An optional shortened abstract.
summary: Teleoperated Robotic Surgery; Surgical activity recognition; Surgical vision and perception

tags: [Surgical Robotics]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
