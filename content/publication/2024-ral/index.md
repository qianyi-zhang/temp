---
title: "STC-TEB: Spatial-Temporally Complete Trajectory Generation Based on Incremental Optimization"
authors:
- Zeqing Zhu
- admin
- Yinuo Song
- Yifan Yang
- Jingtai Liu
author_notes:
- "Equal contribution"
- "Equal contribution"


date: "2024-12-01T00:00:00Z"
doi: "10.1109/LRA.2024.3519883"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-05T16:23:51.355309Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Robotics and Automation Letters*(RAL)"
publication_short: ""

abstract: Exploring topologically distinctive trajectories provides more options for robot motion planning. Since computing time grows greatly with environment complexity, improving exploration efficiency and picking the optimal trajectory in complex environments are critical issues. To this end, this paper proposes a Graphic- and Timed-Elastic-Band-based approach (GraphicTEB) with spatial completeness and high computing efficiency. The environment is analyzed utilizing computer graphics, where obstacles are extracted as nodes and their relationships are built as edges. Three contributions are presented. 1) By assembling directed detours formed by nodes and segmented paths formed by edges, a generalized path consisting of nodes and edges derives various normal paths efficiently. 2) By multiplying two vectors starting from the obstacle point closest to the waypoint and the boundary point farthest from the waypoint, an novel obstacle gradient is introduced to guide safer optimization. 3) By assigning edges with asymmetric Gaussian model, a trajectory evaluation strategy is designed to reflect the motion tendency and motion uncertainty of dynamic obstacles. Qualitative and quantitative simulations demonstrate that the proposed GraphicTEB achieves spatial completeness, higher scene pass rate, and fastest computing efficiency. Experiments are implemented in long corridor and broad room scenarios, where the robot goes through gaps safely, finds trajectories quickly, and passes pedestrians politely.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/10806849
url_code: 'https://github.com/Chris-Arvin/GraphicTEB-series'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
