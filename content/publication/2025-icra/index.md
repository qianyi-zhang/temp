---
title: 'GA-TEB: Goal-Adaptive Framework for Efficient Navigation Based on Goal Lines'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wentao Luo
  - Ziyang Zhang
  - Yaoyuan Wang
  - Jingtai Liu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2025 International Conference on Robotics and Automation*
publication_short: In *ICRA2025*

abstract: In crowd navigation, the local goal plays a crucial role in trajectory initialization, optimization, and evaluation. Recognizing that when the global goal is distant, the robot's primary objective is avoiding collisions, making it less critical to pass through the exact local goal point, this work introduces the concept of goal lines, which extend the traditional local goal from a single point to multiple candidate lines. Coupled with a topological map construction strategy that groups obstacles to be as convex as possible, a goal-adaptive navigation framework is proposed to efficiently plan multiple candidate trajectories. Simulations and experiments demonstrate that the proposed GA-TEB framework effectively prevents deadlock situations, where the robot becomes frozen due to a lack of feasible trajectories in crowded environments. Additionally, the framework greatly increases planning frequency in scenarios with numerous non-convex obstacles, enhancing both robustness and safety.

# Summary. An optional shortened abstract.
summary: In crowd navigation, the local goal plays a crucial role in trajectory initialization, optimization, and evaluation. Recognizing that when the global goal is distant, the robot's primary objective is avoiding collisions, making it less critical to pass through the exact local goal point, this work introduces the concept of goal lines, which extend the traditional local goal from a single point to multiple candidate lines. Coupled with a topological map construction strategy that groups obstacles to be as convex as possible, a goal-adaptive navigation framework is proposed to efficiently plan multiple candidate trajectories. Simulations and experiments demonstrate that the proposed GA-TEB framework effectively prevents deadlock situations, where the robot becomes frozen due to a lack of feasible trajectories in crowded environments. Additionally, the framework greatly increases planning frequency in scenarios with numerous non-convex obstacles, enhancing both robustness and safety.

tags:
  - Navigation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2409.10009
url_code: 'https://github.com/Chris-Arvin/GraphicTEB-series'
url_dataset: ''
url_poster: 'https://ga-teb.github.io/'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=1K7Klxig8CU'

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
slides: example
---