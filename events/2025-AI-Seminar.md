---
layout: default
title: ORNL's AI Seminar Series <br/> 
description: Organized by  AI Initiative <br/>
             11am - noon ET <br/> 
             Every Other Thursday, January-December, 2025 <br/> 
             Hybrid (Onsite & Virtual) <br/>
             
permalink: /events/ai-initiative-seminar-2025/
tags: events
---

# About

The ORNL AI Seminar Series (Biweekly/Hybrid), organized by the [AI Initiative](https://www.ornl.gov/ai-initiative), serves as a platform for researchers and engineers from diverse scientific, engineering, and national security backgrounds spanning ORNL, universities, and industry.
Our main objective is to encourage collaboration with the goal of driving transformative advancements in safe, trustworthy, and energy-efficient AI research and its applications.

The seminar will be held every other Thursday from 11 am to 12 pm ET.
Please reach out to the organizers if you would like to recommend a spearker or give a talk.

<a href="#top"> &#10558; Back to top</a>

# Next Presentation

**Learned Tensor-Offloading: GPU Memory-Efficient Execution Paradigm for Large Deep-Learning Models**

<br>Location: Virtual on MS Teams
<br> Time: 11:00 a.m. - 12 p.m. ET, Thursday, 02/27/2025
<br>Speaker: [Dong Li](https://faculty.ucmerced.edu/dong-li/)

|         |
| ------- |
| <img src="https://eecs.ucmerced.edu/sites/eecs.ucmerced.edu/files/li_dong_150223-3_0.jpg" /> |
| Dong Li <br>Associate Professor <br>Department of Electrical Engineering and Computer Science (EECS), University of California, Merced |

**Abstract**

Training and deploying large deep-learning (DL) models face a memory capacity problem because of increasing model size or limited GPU memory capacity. Tiered memory architectures based on heterogeneous GPU/CPU memories provide a cost-effective solution to enable large DL models on GPU with limited memory. However, using tiered memory faces challenges on tensor management because of the dynamic structure of DL models and irregular memory accesses patterns in the DL workloads. In this talk, we introduce a learned approach (using a neural network or NN) to increase predictability of tensor accesses and facilitate memory management on tiered memory. To make the learned approach feasible, we address a series of challenges for NN feature representation to capture DL memory access patterns, and NN overhead control without sacrificing the effectiveness of NN guidance. Using the learned approach, we largely outperform UVM and tensor materialization (two approaches to enable large DL models on GPU) by 3× and 2.1× respectively in terms of maximum batch size. In the scenarios of industrial-scale deep-learning recommendation model (DLRM), our approach effectively reduces end-to-end DLRM inference time by up to 43%, compared to LRU caching in production.

**Bio**

Dong Li is an associate professor at EECS, University of California, Merced. Previously, he was a research scientist at the Oak Ridge National Laboratory (ORNL), studying computer architecture and programming models for next generation supercomputer systems. Dong earned his PhD in computer science from Virginia Tech. His research focuses on high performance computing (HPC), and maintains a strong relevance to computer systems. The core theme of his research is to study how to enable scalable and efficient execution of enterprise and scientific applications on increasingly complex large-scale parallel systems. Dong received an ORNL/CSMD Distinguished Contributor Award in 2013, a CAREER Award from the National Science Foundation in 2016, Facebook faculty research award in 2021, Oracle Research Award in 2022, Western Digital Research Award in 2022. His paper in SC'14 was in the best paper final list. His paper in ASPLOS'21 won the distinguished artifact award. He was also the lead PI for the NVIDIA CUDA Research Center at UC Merced. He is an associate editor for IEEE Transactions on Parallel and Distributed Systems (TPDS).

<a href="#top"> &#10558; Back to top</a>

---

# Schedule

<!---
The table should be update routein to reflect the upcoming events, and the past events should be at the bottom of the table.
-->

Please reach out if you are interested in presenting at a future event

|      Date      |    Location    |        Name            |          Affilication           |      Talk      |
| :------------: | :------------: | :--------------------: | :-----------------------------: | :------------: |
| 01-09-2025 | Virtual | Fernanda Foertter | ORNL | Problems with preparing data for AI workloads |
| 01-23-2025 | On Site | Bowen Jing | Massachusetts Institute of Technology | Denoising Generative Modeling for Molecular Structures and Dynamics |
| 02-27-2025 | Virtual | Dong Li | University of California, Merced | TBD |
| TBD | On Site | Ayush Chopra | Massachusetts Institute of Technology | TBD |
| TBD | Virtual | Xiaolei Huang| University of Memphis | Towards Trustworthy Natural Language Processing for Sciences |

<a href="#top"> &#10558; Back to top</a>

---

# Past Presentations

**Denoising Generative Modeling for Molecular Structures and Dynamics**

<br>Location: Building 5700, room F234
<br> Time: 11:00 a.m. - 12 p.m. ET, Thursday, 01/23/2025
<br>Speaker: [Bowen Jing](https://people.csail.mit.edu/bjing/), Electrical Engineering and Computer Science, MIT

**Abstract**

The three-dimensional structure and dynamics of molecules yields crucial insights into their chemical properties and biological functions. In this talk, we will discuss how denoising generative modeling has provided a novel and powerful paradigm for the prediction and sampling of molecular structures and dynamics.  Our work is often guided by considerations of physical symmetry and constrained degrees of freedom, requiring extensions of well-known methods to non-Euclidean spaces which best describe molecular flexibility. We will first show how diffusion over torsional coordinates lays the groundwork for modeling small, druglike molecules. Second, we combine this framework with rigid body motions to learn molecular docking to protein structures. Third, we address conformational sampling of proteins and successfully emulate ensembles from molecular dynamics at reduced computational cost. Finally, we discuss video-like modeling of whole molecular dynamics trajectories, enabling multipurpose generative models trained on simulated data.

**Bio**

Bio: Bowen Jing is a 4th year Ph.D. candidate in Electrical Engineering and Computer Science at MIT, co-advised by Tommi Jaakkola and Bonnie Berger. He works on deep learning for structural biology and drug discovery, with a focus on generative models and molecular simulation. He is also a DOE Computational Science Graduate Fellow and completed a practicum in the X Computational Physics Division at at Los Alamos National Laboratory. 

---

**Problems with preparing data for AI workloads**

<br>Location: virtual (MS Teams)
<br> Time: 11:00 a.m. - 12 p.m. ET, Thursday, 01/09/2025
<br>Speaker: [Fernanda Foertter](https://impact.ornl.gov/en/persons/fernanda-foertter)

|         |
| ------- |
| <img src="https://foertter.com/wp-content/uploads/2023/01/22-1116oraclenvidia42921-edited.jpg" width="300" /> |
| Fernanda Foertter <br>Senior HPC Engineer <br>Computational Sciences and Engineering Division, ORNL |

**Abstract**

Preparing data for AI workloads is to put it mildly, awful. Foundational models are best with huge amounts of data but depending on the domain this task can very dramatically in difficulty. This talk will explore the complexities of data preparation for AI and will discuss common tools and methods used from several people surveyed and interviewed for this talk. This talk will also include a mini-workshop where all attendees can share preferred methods and tools with the goal of building community at ORNL.

**Bio**

Fernanda has been in the intersection of scientific computing data wraggling for 15 years. She has a background in physics and molecular dynamics but later transitioned into genomics and healthcare data. Fernanda was at ORNL previously and worked on CORAL and ECP projects and led the training efforts to migrate applications from CPU to GPU on Titan and Summit. After 6 years in industry Fernanda recently returned to ORNL to continue contributing to the mission of the lab and is currently a member of the Scalable Biomedical Simulation group working on MOSSAIC. She has a penchant for building communities of practice and hopes to build one that helps improve how we do data engineering.


<a href="#top"> &#10558; Back to top</a>

---

# Organization

For questions, please contact us.
<style>
td, th {
   border: none!important;
}
</style>

|                |                |                |                |
| -------------- | -------------- | -------------- | -------------- |
| [![Yan Liu](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2019-04/liuy8.png?h=5114cd9b&itok=5Nt4keCd)](https://www.ornl.gov/staff-profile/yan-liu) | [![Jong Youl Choi](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2021-02/jychoi2_0.png?h=273942d0&itok=wF9lLEZU)](https://www.ornl.gov/staff-profile/jong-youl-choi) | [![Chen Zhang](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2020-10/profile_0.png?h=c49a1206&itok=ntQg6NeU)](https://www.ornl.gov/staff-profile/chen-zhang) | [![Prasanna Balaprakash](https://www.ornl.gov/sites/default/files/styles/staff_profile_image_style/public/2023-03/BalaprakashProfile_0.jpg?h=17644140&itok=AYUSlKCG)](https://www.ornl.gov/staff-profile/prasanna-balaprakash) |
| Yan Liu <br> Computational Scientist <br> Computational Sciences & Engineering Division <br> ORNL | Jong Youl Choi <br> HPC Data Research Scientist <br> Computer Science and Mathematics Division <br> ORNL | Chen Zhang <br> Computational Scientist <br> Computer Science and Mathematics Division <br> ORNL | Prasanna Balaprakash<br> Director of AI Programs <br> Distinguished R&D Staff Scientist<br> Computing and Computational Sciences Directorate, ORNL |

<a href="#top"> &#10558; Back to top</a>
