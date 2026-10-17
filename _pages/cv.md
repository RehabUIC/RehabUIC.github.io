---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my full CV (PDF)]({{ base_path }}/files/Rehab_Uddin_Shawon_CV.pdf)

Education
======
* **Ph.D. Student**, Electronic Visualization Laboratory (EVL), University of Illinois Chicago, Aug 2026 – Present
  * Advisor: Dr. Saeed Boorboor
  * Research focus: immersive visualization, 3D displays, and AR/VR
* **M.S. in Computer Science** (Data Science Certification), Missouri State University, Jan 2025 – Jul 2026
  * CGPA 4.00/4.00
  * Thesis: "Heterogeneous Robots Cooperation via Multi-Agent Reinforcement Learning" (committee chair: Dr. Siming Liu)
  * Coursework: Explainable AI, Natural Language Processing, Generative AI
* **M.S. in Computer Science**, Jahangirnagar University, Dhaka, Bangladesh, Sep 2019 – Aug 2020
  * CGPA 3.83/4.00
* **B.Sc. in Naval Architecture**, Bangladesh University of Engineering and Technology (BUET), Dhaka, Bangladesh, May 2012 – Mar 2017

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research experience
======
* **Graduate Research Assistant**, Missouri State University, Jan 2025 – Jul 2026 (Advisor: Dr. Siming Liu)
  * Designed a shared-policy MARL framework for heterogeneous robot teams using a priority-aware grid sensor; scales to up to 10 robot and task types.
  * Evaluated across heterogeneous, sequential, and collaborative tasks in Unity (126 training runs); at 10 types the method reached rewards of 445.1, 366.1, and 273.5 while the Unity ML-Agents baseline stayed near zero.
  * Developed formulations for sequential tasks of arbitrary length and order and for collaborative tasks with dynamic robot requirements; policies generalized without retraining.
  * Developed PEIM (Policy Explanation in MARL), a model-agnostic explainability framework tested on SMACv2 (IEEE ICTAI 2025).
  * Created a Meta-Ensemble Explainable AI framework for image data that combines LIME, SHAP, Grad-CAM, LRP, and SmoothGrad into more reliable instance-level explanations.
* **Research Project Assistant**, Jahangirnagar University, Sep 2019 – Aug 2020 (Advisor: Dr. Mushfique Anwar)
  * Developed image editing software in Unity and C# using digital image processing techniques.

Outreach and teaching
======
* **NSF-funded ROSE Project** (Award No. 2302060), Missouri State University
  * Co-taught and trained high school teachers in machine learning with Dr. Siming Liu.
  * Co-authored the resulting journal paper with participating teachers (IJMERR 2026).
* **Graduate Teaching Assistant**, Missouri State University, Jan 2025 – Jul 2026
  * Led lab sessions in data structures and algorithms for 60+ students.
  * Provided 6 hours of tutoring per week and graded 100+ assignments per semester.

Industry experience
======
* **Senior Game Programmer**, Kolpoverse Studios, Dhaka, Nov 2022 – Nov 2024
  * Engineered high-performance Unity (C#) systems: rendering, physics, and memory optimization; IK, cloth, custom physics joints, and mesh manipulation.
* **Game Programmer**, Alpha Potato Games, Dhaka, Sep 2019 – Oct 2022
  * Built core gameplay for 30+ Unity prototypes and 4 globally released titles with 80M+ downloads; integrated analytics SDKs and Android/iOS build pipelines.
* **Game Programmer**, Mindfisher Games, Dhaka, Jun 2017 – Aug 2019
  * Built 20+ Unity prototypes and shipped internal and soft-launch projects using Git and Agile.
* **3D Animator**, Portbliss Games, Dhaka, Apr 2015 – May 2017
  * Built animation pipelines and Unity animation controllers for Heroes of 71 (1M+ downloads).

Skills
======
* **Languages:** Python, C#, C++, Java
* **ML and data:** PyTorch, TensorFlow, Unity ML-Agents, Scikit-learn, Pandas, NumPy, Apache Spark; explainability tools (LIME, SHAP, Grad-CAM, LRP, SmoothGrad)
* **Environments and tools:** Unity, Unreal Engine, SMACv2, PyGame, Git/GitHub, MySQL, Firebase, Power BI, Tableau
