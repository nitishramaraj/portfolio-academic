---
title: Common Slot Finder
summary:
tags:
  - ALL
  - AI
  - DEV
date: "2023-05-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Sample Timetable of VIT Students
  focal_point: Nitish

links:
  - icon: github
    icon_pack: fab
    name: Github
    url: https://github.com/nitishramaraj/VIT-Common-Slot-Finder
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

The VIT Common Slot Finder is a project that employs computer vision to analyze complex student timetables and identify available free slots. Designed for internal VIT student teams, it facilitates meeting scheduling by analyzing the timetables of approximately 100 students to find common free slots. By uploading their timetables, the tool returns the common free slots for the respective day, ensuring efficient team coordination.

The sample timetable uses red marks to indicate students' class times. Our model analyzed all timetables, creating a JSON file of all empty slots. This data was then compared across students to identify common free slots. If there were any clashes, the model provided insights into other potential meeting times, indicating which students had classes during those slots. If a common free slot was available, it was displayed; otherwise, the next best time with the fewest students in class was shown.
