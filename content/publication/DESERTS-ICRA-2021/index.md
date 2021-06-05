---
title: "DESERTS: Delay-Tolerant Semi-Autonomous Robot Teleoperation for Surgery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.

# do not use dot at the end of author name (confirm?)
authors:
- Glebys Gonzalez
- Mridul Agarwal
- Mythra Varun Balakuntala Srinivasa Mur
- admin
- Richard Voyles
- Vaneet Aggarwal
- Yexiang Xue
- Juan Wachs

# Author notes (optional)
author_notes:

date: "2021-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of
the 2021 IEEE International Conference on Robotics and Automation 
publication_short: ICRA 2021

abstract:  Telesurgery can be hindered by high-latency and low-bandwidth communication networks, often found in austere settings. Even delays of less than one second are known to negatively impact surgeries. To tackle the effects of connectivity associated with telerobotic surgeries, we propose the DESERTS framework. DESERTS provides a novel simulator interface where the surgeon can operate directly on a virtualized reality simulation and the activities are mirrored in a remote robot, almost simultaneously. Thus, the surgeon can perform the surgery uninterrupted, while high-level commands are extracted from his motions and are sent to a remote robotic agent. The simulated setup mirrors the remote environment, including an alphablended view of the remote scene. The framework abstracts the actions into atomic surgical maneuvers (surgemes) which eliminate the need to transmit compressed video information. This system uses a deep learning based architecture to perform live recognition of the surgemes executed by the operator. The robot then executes the received surgemes, thereby achieving semiautonomy. The framework’s performance was tested on a peg transfer task. We evaluated the accuracy of the recognition and execution module independently as well as during live execution. Furthermore, we assessed the framework’s performance in the presence of increasing delays. Notably, the system maintained a task success rate of 87% from no-delays to 5 seconds of delay.

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
