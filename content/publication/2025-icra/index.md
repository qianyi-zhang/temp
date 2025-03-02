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


date: '2025-04-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-05T16:23:51.355309Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2025 International Conference on Robotics and Automation (ICRA2025)*
publication_short: In *ICW*

abstract: In crowd navigation, the local goal plays a crucial role in trajectory initialization, optimization, and evaluation. Recognizing that when the global goal is distant, the robot's primary objective is avoiding collisions, making it less critical to pass through the exact local goal point, this work introduces the concept of goal lines, which extend the traditional local goal from a single point to multiple candidate lines. Coupled with a topological map construction strategy that groups obstacles to be as convex as possible, a goal-adaptive navigation framework is proposed to efficiently plan multiple candidate trajectories. Simulations and experiments demonstrate that the proposed GA-TEB framework effectively prevents deadlock situations, where the robot becomes frozen due to a lack of feasible trajectories in crowded environments. Additionally, the framework greatly increases planning frequency in scenarios with numerous non-convex obstacles, enhancing both robustness and safety.


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2409.10009'
url_code: 'https://github.com/Chris-Arvin/GraphicTEB-series'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ga-teb.github.io/'
url_video: 'https://www.youtube.com/watch?v=1K7Klxig8CU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false