---
title: 'Nonlinear In-situ Calibration of Strain-Gauge Force/Torque Sensors for Humanoid Robots'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hosameldin Awadalla Omer Mohamed
  - admin
  - Punith Reddy Vanteddu
  - Francesco Braghin
  - Daniele Pucci
  
# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  2023 IEEE-RAS International Conference on Humanoid Robotics (Humanoids)
# publication_short: In *ICRA*

abstract: > 
  High force/torque (F/T) sensor calibration accuracy is crucial to achieving successful force estimation/control tasks with humanoid robots. State-of-the-art affine calibration models do not always approximate correctly the physical phenomenon of the sensor/transducer, resulting in inaccurate F/T measurements for specific applications such as thrust estimation of a jet-powered humanoid robot. This paper proposes and validates nonlinear polynomial models for F/T calibration, increasing the number of model coefficients to minimize the estimation residuals. The analysis of several models, based on the data collected from experiments with the iCub3 robot, shows a significant improvement in minimizing the force/torque estimation error when using higher-degree polynomials. In particular, when using a 4th-degree polynomial model, the Root Mean Square error (RMSE) decreased to 2.28N from the 4.58N obtained with an affine model, and the absolute error in the forces remained under 6N while it was reaching up to 16N with the affine model.
  
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10375227'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://ieeexplore.ieee.org/document/10375227/media#media'

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
