---
title: 'A Control Architecture with Online Predictive Planning for Position and Torque Controlled Walking of Humanoid Robots'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Stefano Dafarra
  - admin
  - Marie Charbonneau
  - Nuno Guedelha
  - Francisco Andrade
  - Silvio Traversaro
  - Luca Fiorio
  - Francesco Romano
  - Francesco Nori
  - Giorgio Metta
  - Daniele Pucci

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2018'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
# publication_short: In *ICRA*

abstract: > 
  A common approach to the generation of walking patterns for humanoid robots consists in adopting a layered control architecture. This paper proposes an architecture composed of three nested control loops. The outer loop exploits a robot kinematic model to plan the footstep positions. In the mid layer, a predictive controller generates a Center of Mass trajectory according to the well-known table-cart model. Through a whole-body inverse kinematics algorithm, we can define joint references for position controlled walking. The outcomes of these two loops are then interpreted as inputs of a stack-of-task QP-based torque controller, which represents the inner loop of the presented control architecture. This resulting architecture allows the robot to walk also in torque control, guaranteeing higher level of compliance. Real world experiments have been carried on the humanoid robot iCub.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/8594277'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://ieeexplore.ieee.org/document/8594277/media#media'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
