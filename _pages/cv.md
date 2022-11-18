---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, CGPA: 4.0  
  Florida International University, Miami, Florida, USA, April 2013 (expected)
* M.S. in Computer Engineering CGPA: 3.8  
  Western Michingan University, Kalamazoo, Michigan, USA, 2018
* B.S. in Electrical Engineering  
  University of Engineering & Technology, Lahore, Punjab, Pakistan, 2014

Work experience
======
* **Meta**, Menlo Park, CA, USA  
  Software Engineer Intern (Machine Learning)  May 2022 - Aug 2022
  * Supervisor: Yang Xu
  * Improved Ad revenue by 5.5% by designing deep learning architectures for Ads Comments Ranking.
  * Proposed and implemented Sparse Neural Network and Transfer Learning based solutions.
  * Implemented point-wise, pairwise, and slate ranking algorithms and provided an initial evaluation
  * Increased post-click Ad conversion by 11.96% by integrating text features into the ranking platform.
  * Collaborated with multiple cross-functional teams and served as the main point of contact.

* **Florida International University**, Miami, FL, USA  
  Graduate Research Assistant  Aug 2018 - May 2023 (Expected)
  - Supervisor: Dr. Fahad Saeed
  - Created Self-Supervised Masked Language Model for Learning Protein Representation.
    - Trained the language model on a distributed cluster environment using 1 Billion protein segments.
    - Pretext protein language model using BERT improves the performance of downstream models.
  - SpeCollate: Deep Learning Network for Cross-Modal Retrieval. https://pcdslab.github.io/SpeCollate/
    - Improved protein sequencing accuracy to 95% compared to existing tools with < 70%. (Python, PyTorch)
    - Formulated SNAP-Loss: Customized quadruplet-based loss function for training SpeCollate.
    - Implemented distributed multi-GPU training of SpeCollate on SDSC Expanse supercomputer V100 GPU nodes.
    - Helped write the successful proposal for the project’s US$1 million National Institute of Health grant.
    - Awarded US$100 thousand worth of resources on XSEDE SDSC Expanse supercomputer cluster.
  - Multitask Attention Network for Predicting Peptide Properties. https://github.com/Usman095/DeepAtles
    - Designed novel deep learning attention-based architecture for learning mass spectra embeddings.
    - Reduced search space size by 90% for cross-modal retrieval using Multitask Learning. (Python, PyTorch)
  - Mentored overall 20 Undergraduate, master’s, and Ph.D. students in their research projects and career prospects

* **Western Michigan University**, Kalamazoo, MI, USA  
  Graduate Teaching Assistant  Aug 2016 - July 2018
  - Supervisor: Dr. Fahad Saeed
  - Formulated a 1.5x faster parallel network sampling algorithm using OpenCL for FPGAs. (C/C++, Big Data)
  - Created custom data structure (COPRA) for parallel removal of nodes and edges from the network.

* **Xavor**, Lahore, Pakistan  
  Software Engineer  July 2014 - July 2016
  - Supervisor: Muhammad Athar Shafiq
  - Implement HR Management Portal for Guitar Center using SharePoint. (C#, .NET)
  - Designed and implemented database merger workflow of Guitar Center and Music & Arts. (Agile Methodology)

Projects
======
* **[Winner ShellHacks 2021 Hackathon for CloudVision](https://devpost.com/software/cloudvision):** A social distancing app for the visually imparied.
  * Best use of Google Cloud API award. First Prize.
  * Best Health Access and Delivery App by MITRE. Second Prize.

* TogetherAI: AI-based dating app.
  * Suggests matches based on AI-based profile images and description analysis using ResNet and GPT2.
  * Improves engagement between matches by suggesting ice-breakers based on mutual likenesses.
  
Skills
======
* **Core Skills**: Algorithm Design and Analysis, Deep Learning, Machine Learning, Computer Vision, Decision Trees, LSTMs, Attention Networks, Convolutional Neural Networks, Representation Learning, Two-Tower Networks (Dual Encoder Networks), Parallel Computing
* **Frameworks**: PyTorch, Keras, TensorFlow, SciKit-Learn, NumPy, Pandas, Jupyter Notebook
* **Programming Languages**: Python, C++, C, C\#, Java, Cuda, OpenCL, MPI, OpenMP

Patents
======
  <ul>
    {% for post in site.patents %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
  
Publications
======
  <ul>
    {% assign sorted = site.publications | sort: 'order' %}
    {% for post in sorted %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
  
Awards and Talks
======
* Winner ShellHacks 2021 Hackathon for CloudVision. https://devpost.com/software/cloudvision
* Winner 3MT Poster Presentation on SpeCollate at SCIS FIU Research Day Event 2019.
* Awarded Rising Star of the Year 2015 as a Software Engineer at Xavor Corporation
* Guest Speaker “Supercomputing and Machine Learning for Big Biomedical Data” at the Department of Electrical Engineering, University of Engineering and Technology, Lahore, Pakistan. 2021 https://www.youtube.com/watch?v=dUvaxjDeBmM
* Presented “Parallel Sampling-Pipeline for Indefinite Stream of Heterogeneous Graphs using OpenCL for FPGAs.” at 2018 International Conference on Big Data.
* Presented “Power-efficient and highly scalable parallel graph sampling using FPGAs.” at 2017 International Conference on ReConFigureable Computing and FPGAs.
* Presented “Predictive activation for localization using minimal data-fusion in MANETs.” at 2013 International Conference on Information and Communication Technologies.

Leadership and Extra-Curricular Activities
======
* Tech Lead, AI/ML Community with more than 230 active members as part of Google Developer Student Club.
* Leader of Deep Learning paper reading club with 10 active researchers.
* Reviewer for IEEE Access, PLOS, and Distributed Ledger Technologies.
* Volunteer coordinator at Midscale Experimental Research Infrastructure Forum (MERIF 2020).
* Volunteered organizer at International Multi-Topic Conference 2013.
* Member Upsilon Pi Epsilon (UPE), UPE Leap, UPE SparkDev, and UPE Code student organizations.
* Designed IEEE UET Web Portal as a member of the IEEE Student Chapter during my bachelor’s degree.
* Organized several events and workshops (Programming Competitions, LaTeX, MATLAB Workshops) as a member of
the IEEE Student Chapter during my bachelor’s degree.
