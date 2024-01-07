---
title: Mobile robot with intelligent pipeline fault sensing system
summary: Implementation of a mobile robot for inspection of water main pipes. The robot has an intelligent sensing module to recognize different types of failures and reconstruct the interior of the inspected pipe.
tags:
  - Ground robot
  - Inspection robot
  - 3D reconstruction
date: '2022-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Mobile robot and a 3D model of a pipe
  focal_point: Smart

links:
  - icon: linkedin
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/jorgeramirezchavez/
url_code: ''
url_pdf: ''
url_slides: ''
url_video: 'https://youtu.be/WdRnoIKK7LM?si=aSwYeAezE37dVWzf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---
Tunnels and pipelines are considered critical infrastructure since they are essential for the development of countries. Among these, the sewerage system and the waste distribution system hold significant importance. Due to their importance, the inspection and frequent diagnoses are necessary. For this reason, a mobile inspection robot was implemented. My role in the project was Research Assistant, and my responsibilities included the design, implementation, and validation of the intelligent sensing system. Additionally, I worked on developing a master's thesis related to the project.

The robot is teleoperated from the entrance to the pipeline and transmits video in real time. During its movement within the pipes, information is collected to later carry out the 3D reconstruction of the interior of the pipe. A software interface was implemented on a field laptop and a Logitech gamepad was used for control. The following video shows the development of an initial version of the inspection robot.

<div style="text-align:center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/WdRnoIKK7LM?si=Cmy9IJY2TnFOHFXb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div >

For 3D reconstruction, techniques were analyzed using depth cameras, laser scanners and IMUs. The following video shows a reconstruction test using the ElasticFusion algorithm.

<div style="text-align:center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/GthN1tUs7IU?si=IHmSgerjuwGiQ3Aa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div >

The project was validated with the support of the Peruvian company SEDAPAL (https://sedapalteinforma.com.pe/) who allowed access to its infrastructure as shown in Figure 2. A 3D model of the interior of the pipes was obtained in addition to information such as its inclination, actual diameter of the pipes, etc.

<figure>
  <img src= entrance.jpg width= 280 height= 280 >
  <figcaption>Fig.2 - Validation of the inspection robot</figcaption>
</figure>

This project was developed thanks to the support of the Technological Innovation Group of the the Pontifical Catholic University of Peru (GIT-PUCP) and financing by the National Program for Scientific Research and Advanced Studies (PROCIENCIA) of the Peruvian government.

