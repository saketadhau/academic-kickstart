---
title: INDIAN CONTROL CONFERENCE, 2019
event: Fifth Indian Control Conference - ICC'19
event_url:  https://icc.org.in/2019/ 
location: Indian Institute of Technology, New Delhi, India
summary: My paper presentation at Indian Control Conference, IIT Delhi.
abstract: "It is well-known that the real-time implementation of MPC is cumbersome because of the huge burden of solving QP problem on-line at each sample time. Due to this, traditionally MPC has been mainly restricted to processes with rather slow dynamics, such as the ones encountered in the oil and gas refineries. However, recent algorithmic advances (such as the explicit MPC) allowed the application of MPC to problems arising in the automotive or power electronics industry where the time scales are in the milli- to microsecond range. This paper focuses on the FPGA implementation of offset-free explicit MPC and its detailed analysis for the position control of PMDC motor. We show the analysis of controller computational complexity in terms of memory, resource utilization, clock and power consumption. Effect of various tuning parameters on the number of regions is also presented with respect to the changing prediction horizon length. Finally, the performance of implemented offset-free explicit MPC is compared with the standard explicit MPC and PI controller for reference-tracking, constraints handling, and disturbance rejection. Results indicate that the performance of offset-free explicit MPC is superior but at the cost of increased memory footprint."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-01-09T08:30:00Z"
date_end: "2019-01-11T18:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Saket Adhau]
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: top

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/saketadhau29
url_code: ""
url_pdf: "https://saketadhau.netlify.com/publication/icc/icc.pdf"
url_slides: "https://saketadhau.netlify.com/publication/icc/icc-ppt.pdf"
url_video: ""


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- mpc

# Enable math on this page?
math: true
---


