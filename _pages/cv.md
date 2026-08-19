---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
  /* ===== 대제목 (섹션) ===== */
  .page__content h2 {
    font-size: 1.6em;
    font-weight: 700;
    border-bottom: 2px solid #e0e0e0;
    padding-bottom: 0.25em;
    margin: 1.5em 0 0.7em 0;
  }
  /* ===== 중제목 (항목) : 왼쪽 제목 + 오른쪽 기간 ===== */
  .page__content h3 {
    display: flex;
    flex-wrap: wrap;
    align-items: baseline;
    gap: 0 0.75em;
    font-size: 1.05em;
    margin: 1.2em 0 0.2em 0;
  }
  .page__content h2 + h3 { margin-top: 0.5em; }
  .page__content .cv-date {
    margin-left: auto;
    font-weight: 400;
    font-style: italic;
    font-size: 0.82em;
    color: #767676;
    white-space: nowrap;
  }
  /* ===== 기관/소속 메타 줄 ===== */
  .page__content .cv-meta {
    font-size: 0.85em;
    font-style: italic;
    color: #767676;
    line-height: 1.45;
    margin: 0 0 0.2em 0;
  }
  /* ===== 랩 하위 항목 들여쓰기 (Research Experience) ===== */
  .page__content .cv-sub {
    margin: 0.3em 0 0 0.3em;
    padding-left: 1.1em;
    border-left: 2px solid #ececec;
  }
  .page__content .cv-role {
    display: flex;
    flex-wrap: wrap;
    align-items: baseline;
    gap: 0 0.75em;
    margin: 0.55em 0 0.1em 0;
  }
  .page__content .cv-sub > p:first-child { margin-top: 0; }
  /* ===== 항목 내부 줄간격 축소 ===== */
  .page__content p { margin: 0 0 0.4em 0; }
  .page__content ul,
  .page__content ol {
    margin-top: 0.15em;
    margin-bottom: 0.8em;
  }
  .page__content li {
    margin-bottom: 0.12em;
    line-height: 1.55;
  }
  .page__content ol > li { margin-bottom: 0.45em; }
  .page__content li p { margin: 0; }
  .cv-sub ul { margin-bottom: 0.6em; }
</style>

## Research Interests

Learning-Based Network Management and Optimization, Multi-access Edge Computing, Machine Learning for Wireless Networks, Reinforcement Learning and Transformer-Based Models, 6G Non-Terrestrial Networks (NTN)

## Education

### M.S. in Electrical and Electronic Engineering <span class="cv-date">Mar. 2025 – Feb. 2027 (Expected)</span>

Yonsei University, Seoul, Republic of Korea
{: .cv-meta}

- Advisor: Prof. Jong-Moon Chung, Communications & Networking Laboratory (CNL)

### B.S. in Electrical and Electronic Engineering <span class="cv-date">Mar. 2019 – Feb. 2025</span>

Yonsei University, Seoul, Republic of Korea
{: .cv-meta}

- Includes 1.5 years of mandatory military service (Oct. 2020 – Apr. 2022)

## Publications

### Journal Articles

1. **J. Kim**, M. Choi, and J.-M. Chung, “GT-PAR: Graph Transformer-Aided Traffic Prediction and Adaptive Routing for Dynamic LEO Satellite Networks,” *IEEE Wireless Communications Letters*, vol. 15, pp. 4290–4294, Jul. 2026. [DOI](https://doi.org/10.1109/LWC.2026.3717034)
2. M. Choi, M. Park, **J. Kim**, and J.-M. Chung, “Intelligent Handover Scheme for Improved 6G NTN LEO Satellite Network Performance,” *IEEE Transactions on Mobile Computing*, vol. 25, no. 5, pp. 6863–6880, May 2026. [DOI](https://doi.org/10.1109/TMC.2025.3642278)

### Conference Papers

1. **J. Kim** and J.-M. Chung, “Object Detection Robustness of UAV-MEC YOLO Split Computing under Signal Quality Degradation,” in *Proc. 2026 Spring Conf. of the Korea Institute of Electronic Communication Sciences (KIECS)*, Daejeon, Republic of Korea, Jun. 2026. **(Outstanding Paper Award)**

## Honors and Scholarships

- **Outstanding Oral Presentation Award**, 8th Industry–Academia Project Showcase of the MOTIE/KIAT Future Vehicle Core Technology Workforce Consortium, Jul. 2026
- **Outstanding Paper Award**, 2026 Spring Conference of the Korea Institute of Electronic Communication Sciences (KIECS), Jun. 2026
- **Teaching Assistant Scholarship**, Yonsei University, Fall 2025 and Spring 2026

## Research Experience

### Communications & Networking Laboratory (CNL), Yonsei University <span class="cv-date">Jul. 2024 – Present</span>

Learning-based optimization for 6G NTN/LEO satellite networks and UAV–MEC systems
{: .cv-meta}

<div class="cv-sub" markdown="1">

<span>**Graduate Research Assistant** (Advisor: Prof. Jong-Moon Chung)</span> <span class="cv-date">Mar. 2025 – Present</span>
{: .cv-role}

- Developed GT-PAR, a graph-transformer framework for joint inter-satellite traffic prediction and adaptive routing in dynamic LEO networks.
- Contributed to a multi-agent reinforcement learning-based handover management study for LEO satellite networks, building the network simulator and conducting large-scale performance evaluation.

<span>**Undergraduate Research Intern**</span> <span class="cv-date">Jul. 2024 – Feb. 2025</span>
{: .cv-role}

- Implemented and benchmarked handover and routing schemes for satellite and UAV networks through network simulation.

</div>

### Robotic & Mobile Networks Laboratory (RAMO), Yonsei University <span class="cv-date">Jan. 2024 – Jun. 2024</span>

Collaborative computing for URLLC in remote robot control over a private 5G system
{: .cv-meta}

<div class="cv-sub" markdown="1">

<span>**Undergraduate Research Intern, B.S. Thesis** (Advisor: Prof. Seong-Lyun Kim)</span>
{: .cv-role}

- Built a multi-access edge computing (MEC) testbed offloading robot vision inference to an edge/core server over a private 5G network for ultra-reliable low-latency communication (URLLC) in remote robot control.
- Deployed object detection and monocular depth estimation on the edge server with a real-time safety stop that halts the robot when an object enters its safety zone.

</div>

## Selected Projects

### Adaptive UAV–MEC Collaborative Inference for Urban Traffic Monitoring <span class="cv-date">Mar. 2026 – Jul. 2026</span>

Connected Mobility Research Project (Graduate Course), Yonsei University
{: .cv-meta}

- Built a UAV–MEC split-computing pipeline for real-time object detection in traffic monitoring, robust under poor wireless channels.
- Published the results as a first-author conference paper.
- **Outstanding Paper Award**, 2026 Spring Conference of the Korea Institute of Electronic Communication Sciences (KIECS), Jun. 2026
- **Outstanding Oral Presentation Award**, 8th Industry–Academia Project Showcase of the MOTIE/KIAT Future Vehicle Core Technology Workforce Consortium, Jul. 2026

### UAV Aerial Imagery-Based Road Object Detection for Dynamic Thematic Map Generation <span class="cv-date">Jan. 2025 – Present</span>

Research Assistant, Yonsei University — national R&D project “Development of Fixed/Moving Platform Based Dynamic Thematic Map Generation Technology for Next Generation Digital Land Information Construction,” funded by the Korea Agency for Infrastructure Technology Advancement (KAIA) under the Ministry of Land, Infrastructure and Transport (MOLIT)
{: .cv-meta}

- Built a deep learning-based detection system for real-time recognition of road objects from UAV aerial imagery.
- Improved detection of small, occluded, and low-light objects via tiling-based augmentation and misalignment-tolerant EO/IR sensor fusion, meeting accuracy and latency targets in official certification testing.

## Teaching Experience

### Teaching Assistant, Introduction to Electrical and Computer Engineering <span class="cv-date">Mar. 2026 – Jun. 2026</span>

Yonsei University, School of Electrical and Electronic Engineering
{: .cv-meta}

- Assisted a 370-student introductory course on emerging AI, networking, and security technologies; handled grading, office hours, exam logistics, and student communication.

### Teaching Assistant, Experiments on Communication Networks <span class="cv-date">Sep. 2025 – Dec. 2025</span>

Yonsei University, School of Electrical and Electronic Engineering
{: .cv-meta}

- Led hands-on labs for 20 undergraduates on packet analysis (Wireshark), spectrum sensing with CNN detection (USRP/LabVIEW), SDN routing (Mininet), and LTE/V2X simulation (OMNeT++); graded lab reports with individual feedback.

## Leadership and Service

### Mandatory Military Service: Training Assistant <span class="cv-date">Oct. 2020 – Apr. 2022</span>

Republic of Korea Army Signal School
{: .cv-meta}

- Assisted communications training for enlisted trainees, supporting hands-on instruction on military communication systems and course operations.

## Technical Skills and Certifications

- **Programming**: Python, C/C++, MATLAB, Verilog
- **ML & Simulation**: PyTorch; OMNeT++, SimuLTE, Veins/SUMO, Mininet
- **Experiments**: USRP, LabVIEW, Wireshark
- **Certification**: Class III Unmanned Multirotor Pilot Certificate, Republic of Korea
- **Languages**: Korean (native); English (proficient)