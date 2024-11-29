---
title: 'Direct Force Feedback Control and Online Multi-Task Optimization for Aerial Manipulators'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Quentin Sablé
  - Marco Tognon
  - Daniele Pucci
  - Antonio Franchi

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  IEEE Robotics and Automation Letters
# publication_short: In *ICRA*

abstract: > 
  In this letter we present an optimization-based method for controlling aerial manipulators in physical contact with the environment. The multi-task control problem, which includes hybrid force-motion tasks, energetic tasks, and position/postural tasks, is recast as a quadratic programming problem with equality and inequality constraints, which is solved online. Thanks to this method, the aerial platform can be exploited at its best to perform the multi-objective tasks, with tunable priorities, while hard constraints such as contact maintenance, friction cones, joint limits, maximum and minimum propeller speeds are all respected. An on-board force/torque sensor mounted at the end effector is used in the feedback loop in order to cope with model inaccuracies and reject external disturbances. Real experiments with a multi-rotor platform and a multi-DoF lightweight manipulator demonstrate the applicability and effectiveness of the proposed approach in the real world.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/8928943'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://ieeexplore.ieee.org/document/8928943/media#media'

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
