---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Ladoke Akintola University of Technology (LAUTECH)**  
B.Tech. Electronic and Electrical Engineering  
Expected graduation: 2026 
CGPA: 4.20/5.00 | Second Class Upper Division

## Research Interests

- Computer Vision  
- Robotics and Inteligient Systems

## Research Experience

**Final-Year Research Project — LAUTECH**  
*March 2026 – Present*

Project: *Development of an Artificial Intelligence Powered Internet of Things for a Smart Waste Segregation Sysytem*
Supervisor: Dr F. K Ojo

- Designed an end-to-end computer vision pipeline utilizing YOLOv8 and OpenCV to enable waste classification and sorting real time.
- Built and labelled a custom dataset on Roboflow with1,400 images and trained a YOLOv8 object detection model, achieving approximately 0.89 mAP@50 and 0.78 mAP@50–95.
- Overcame limited GPU resources by moving model training to Kaggle, reducing training time by approximately 2× faster and then integrated the trained model with an ESP32 controlled servo mechanism and demonstrated real time waste detection and physical sorting.

**Summer Undergraduate Researcher, University Of Chicago, United States of America**  
*July – September 2026*

Project: *A Molecular Study On Programmable Protic Ionic Liquids Metal Organic Framework (PILMOF) Moieties For Critical Elements Extraction*
Supervisor: Prof. Ezinne C Achinivu, Dr Alex Accquah | Remote Research Placement

- Investigated molecular behaviour of protic ionic liquids under varied conditions relevant to critical mineral extraction, building and running MD simulations across pure, water-containing, and Nd³⁺-doped systems in LAMMPS.
- Rapidly mastered linux - based computational workflos(LAMMPS, OVITO) within 9 weeks demonstrating strong adaptability to unfamiliar scientific domains
- Presented research findings on molecular behaviour and extraction effieciency in a formal academic presentation,highlighting key insights into ionic liquid stability


## Selected Projects

**Autonomous Agricultural Robot Simulation**
- Explored autonomous navigation in a simulated agricultural environment using ROS 2, Gazebo, LiDAR, and Nav2.

**Cattle Intrusion Detection and Prevention System**
- Contributed to an AI-powered IoT system using YOLOv8n-based cattle detection, audible deterrence, SMS alerts, and image uploads for farmland monitoring.
- The system achieved 89% detection accuracy during field evaluation on a maize farm in Ogbomoso, Nigeria.
- Related paper available on SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5683383

## Publications and Research Outputs

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Conference Posters and Presentations

- **Accepted Poster**, Women in Machine Learning (WiML) Workshop at NeurIPS 2026.  
  *An IoT Enabled Deep Learning Framework for Real Time Multi-Class Waste Detection and Automated Sorting.*  
  Accepted for poster presentation.

## Leadership and Service

**WAAW Foundation, LAUTECH Chapter — Chapter Lead**  
*2024 – Present*

- Led an 11-member team delivering STEM outreach to more than 500 girls across 20 secondary schools in Ogbomoso.
- Coordinated activities promoting girls' participation in science, technology, engineering, and mathematics.
- Received the Chapter Special Recognition — Beyond the Classroom Spotlight in May 2026.

**APWEN Collegiate, LAUTECH — General Secretary**

- Supported chapter administration, coordination, and student engagement.

**IEEE LAUTECH Student Branch — Financial Secretary**

- Supported financial administration and student-branch activities.

## Awards and Recognition

-1st place Winner, 234 AI Hackathon Games 2024, University of Ibadan, Oyo State with ₦200,000 prize. 
-1st place Winner, Hack4Livestock Agro-Alliance Challenge, Nigeria with ₦5,000,000 team prize with invitation to
exhibit in Florida
-1st Runner-Up, UNILAG Energy Challenge 2024, University of Lagos, Lagos State ₦1,500,000 team prize. 
-1st Runner-Up, OORC Innovation/Entrepreneurship Competition Ogbomoso, Nigeria with ₦500,000 team prize.I
led team Cyfe
-1st Runner-Up, Nigerian Genius 2025, Clintonel Innovation Centre, Nigeria represented LAUTECH as part of the
competition team. 
-Top 15 in Africa, Newton AI/STEM Club Innovation Competition participated as a member of Team Newton AI
STEM Club and subsequently participated in programme activities at the University of Lagos.

## Technical Skills

- **Programming & Machine Learning**: Python, C++, YOLOv8, OpenCV
- **Robotics & Simulation**: ROS 2, Gazebo, RViz, URDF, Nav2
- **Molecular Modelling & Scientific Computing**: LAMMPS, Packmol, FFTool, OVITO, Linux/Ubuntu
- **Design & Fabrication** : 3D Design, 3D Printing, Digital Manufacturing
- **Tools**: Git, Roboflow, Google Colab, Kaggle
- **Soft Skills**: Leadership, problem solving, technical communication, creativity, team coordination, and teaching

## Research Goals

Interested in graduate research at the intersection of computer vision, robotics, and intelligent autonomous systems.
