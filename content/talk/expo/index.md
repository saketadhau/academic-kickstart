---
title: MATLAB EXPO 2019
event: Matlab Expo 2019
event_url:  https://www.matlabexpo.com/in/2019/proceedings.confirmation.html?s_v1=27285&elqem=2655105_EM4_IN_LEV_19-04_MATLAB-EXPO_POST_PUNE   
location: JW Marriott Hotel, Senapati Bapat Road, Pune Maharashtra, India
summary: Effective Classroom Teaching of Model Predictive Control Using MATLAB as Academic Coursework
abstract: "Matlab and Simulink, MPC toolbox and live script are being used for effective academic coursework teaching and experimental setup for showcasing the ease of implementation of MPC for DC Motor using Simulink coder. Later the students were assessed using Matlab Grader."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-05-02T08:30:00Z"
date_end: "2019-05-02T18:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Saket Adhau, Sayli Patil]
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
#url_pdf: "https://www.matlabexpo.com/content/dam/mathworks/mathworks-dot-com/images/events/matlabexpo/in/2019/effective-classroom-teaching.pdf"
url_slides: "https://www.matlabexpo.com/content/dam/mathworks/mathworks-dot-com/images/events/matlabexpo/in/2019/effective-classroom-teaching.pdf"
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

The prevalent use of model based predictive control in control tasks has been well established in industrial use and thus it has also gained academic research importance. It has been included in many academic coursework as a part of advanced control strategies. Here, in embedded lab, Department of Instrumentation and Control, we have a similar coursework dedicated for MPC. Recently we had organized winter school in which MPC was taught with hands on session. Teaching a class of 30-50 students is cumbersome and usage of Matlab in teaching made the learning process quick and effective. The students were thought with basics of MPC controller, effectiveness over classical controllers and then formulating the MPC controller on MATLAB command line using live script. The students were given test problems and assessed using Matlab grader. To showcase the importance and performance improvement of MPC, a real time demo was made on DC motor model using Simulink. DC motor is used in many real-world applications because it is suitable for both high and low power drives, for fixed and variable speed electric drives, it has a simple construction, it's easy to design and maintenance, and it also has a high starting torque. We demonstrate here the need of DC motor advanced control in infusion pump which is used for drug delivery. The control action here, needs to be very precise as a little amount of under dose or overdose of drug may threaten the life of a patient. Using Matlab and Simulink along with the other packages from Matlab helps us to deploy Model predictive controller quickly on target hardware. The generated MPC is simulated and tested for the DC motor model under various operating conditions. The MPC was also compared with existing classical PID controller. This generated MPC controller is further deployed on actual hardware for real time control applications. The results show the ease of using Matlab and Simulink for designing, deploying and testing the model-based controller in real time. The code can also be used as a standalone code.
