---
title: 'Jerk Control of Floating Base Systems With Contact-Stable Parameterized Force Feedback'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ahmad Gazar
  - admin
  - Francisco Javier Andrade Chavez
  - Daniele Pucci

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:   IEEE Transactions on Robotics
# publication_short: In *ICRA*

abstract: > 
  Nonlinear controllers for floating base systems in contact with the environment are often framed as quadratic programming (QP) optimization problems. Common drawbacks of such QP-based controllers   are: the control input often experiences discontinuities; no force feedback from force/torque (FT) sensors installed on the robot is taken into account. This article attempts to address these limitations using jerk-based control architectures. The proposed controllers assume the rate-of-change of the joint torques as control input, and exploit the system position, velocity, accelerations, and contact wrenches as measurable quantities. The key ingredient of the presented approach is a one-to-one correspondence between free variables and an inner approximation of the manifold defined by the contact stability constraints. More precisely, the proposed correspondence covers completely the contact stability manifold except for the socalled friction cone, for which there exists a unique correspondence for more than 90% of its elements. The correspondence allows us to transform the underlying constrained optimization problem into one that is unconstrained. Then, we propose a jerk control framework that exploits the proposed correspondence and uses FT measurements in the control loop. Furthermore, we present Lyapunov stable controllers for the system momentum in the jerk control framework. The approach is validated with simulations and experiments using the iCub humanoid robot.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9237133'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://ieeexplore.ieee.org/document/9237133/media#media'

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
