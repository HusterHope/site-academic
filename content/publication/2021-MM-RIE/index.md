---
title: "Improving Robustness and Accuracy via Relative Information
Encoding in 3D Human Pose Estimation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Wenkang Shan
- admin
- Shanshe Wang
- Xinfeng Zhang
- Wen Gao

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-08-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 29th ACM International Conference on Multimedia
publication_short: In *ACM MM 2021* (Poster)

abstract: Most of the existing 3D human pose estimation approaches mainly focus on predicting 3D positional relationships between the root joint and other human joints (local motion) instead of the overall trajectory of the human body (global motion). Despite the great progress achieved by these approaches, they are not robust to global motion, and lack the ability to accurately predict local motion with a small movement range. To alleviate these two problems, we propose a relative information encoding method that yields positional and temporal enhanced representations. Firstly, we encode positional in- formation by utilizing relative coordinates of 2D poses to enhance the consistency between the input and output distribution. The same posture with different absolute 2D positions can be mapped to a common representation. It is beneficial to resist the interfer- ence of global motion on the prediction results. Second, we encode temporal information by establishing the connection between the current pose and other poses of the same person within a period of time. More attention will be paid to the movement changes before and after the current pose, resulting in better prediction performance on local motion with a small movement range. The ablation studies validate the effectiveness of the proposed relative information encoding method. Besides, we introduce a multi-stage optimization method to the whole framework to further exploit the positional and temporal enhanced representations. Our method outperforms state-of-the-art methods on two public datasets. Code is available at https://github.com/paTRICK-swk/Pose3D-RIE.

# Summary. An optional shortened abstract.
summary: A relative information encoding method that yields positional and temporal enhanced representations.
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2107.13994.pdf'
url_code: 'https://github.com/paTRICK-swk/Pose3D-RIE'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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


