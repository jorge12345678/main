---
title: Using a Marine Surface Vehicle (USV) and a Drone for water body characterization in the Amazon.

summary: This project, developed by the Peruvian company Tumi Robotics, seeks to combat pollution in the Amazon caused by illegal mining activities using a robotic solution composed of a surface aquatic robot and a drone. Using specialized sensors, it is sought to diagnose contaminated water bodies so that local institutions can propose solution alternatives.

tags:
  - Aquatic robots
  - Characterization
  - 3D reconstruction

date: '2022-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Mobile robot and a 3D model of a pipe
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: 'https://youtu.be/eXIlXzeYDLQ?si=Qb6eC_gk7kwMZbcp'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---
Tunnels and pipelines are considered critical infrastructure since they are essential for the development of countries. Among these, the sewerage system and the waste distribution system hold significant importance. Due to their importance, the inspection and frequent diagnoses are necessary.

For this reason, a mobile inspection robot was implemented. The robot is teleoperated from the entrance to the pipeline and transmits video in real time. During its movement within the pipes, information is collected to later carry out the 3D reconstruction of the interior of the pipe. A software interface was implemented on a field laptop and a Logitech gamepad was used for control as shown in  Figure 1.

<figure>
  <img src= control.jpg width= 280 height= 280 >
  <figcaption>Fig.1 - Software interface and control gamepad </figcaption>
</figure>

The project was validated with the support of the Peruvian company SEDAPAL (https://sedapalteinforma.com.pe/) who allowed access to its infrastructure as shown in Figure 2. A 3D model of the interior of the pipes was obtained in addition to information such as its inclination, actual diameter of the pipes, etc.

<figure>
  <img src= entrance.jpg width= 280 height= 280 >
  <figcaption>Fig.2 - Validation of the inspection robot</figcaption>
</figure>

This project was developed thanks to the support of the Technological Innovation Group of the the Pontifical Catholic University of Peru (GIT-PUCP) and financing by the National Program for Scientific Research and Advanced Studies (PROCIENCIA) of the Peruvian government.
