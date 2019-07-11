+++
title = "Redundant Perception and State Estimation for Reliable Autonomous Racing"
date = "2019-06-03"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["**Nikhil Gosala**", "Andreas Bühler", "Manish Prajapat", "Claas Ehmke", "Mehak Gupta", "Ramya Sivanesan", "Abel Gawel", "Mark Pfeiffer", "Mathias Bürki", "Inkyu Sa", "Renaud Dubé", "Roland Siegwart"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "International Conference on Robotics and Automation 2019, Montréal, Canada."
publication_short = "ICRA 2019"

# Abstract and optional shortened version.

abstract = "In autonomous racing, vehicles operate close to the limits of handling and a sensor failure can have critical consequences. To limit the impact of such failures, this paper presents the redundant perception and state estimation approaches developed for an autonomous race car. Redundancy in perception is achieved by estimating the color and position of the track delimiting objects using two sensor modalities independently. Specifically, learning-based approaches are used to generate color and pose estimates, from LiDAR and camera data respectively. The redundant perception inputs are fused by a particle filter based SLAM algorithm that operates in real-time. Velocity is estimated using slip dynamics, with reliability being ensured through a probabilistic failure detection algorithm. The sub-modules are extensively evaluated in real-world racing conditions using the autonomous race car &quot;gotthard driverless&quot;, achieving lateral accelerations up to 1.7G and a top speed of 90km/h."

# Featured image thumbnail (optional)
#image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://arxiv.org/abs/1809.10099"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=ir_uqEYuT84"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#[[url_custom]]
#name = "Journal"
#url = "https://link.springer.com/article/10.1007/s10584-014-1174-4"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "ftl.png"
#caption = "My caption :smile:"

+++