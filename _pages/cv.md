---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a style="line-height: 1.5;" href="https://github.com/BrightTux/brighttux.github.io/raw/master/files/cv.pdf"><span style="color: #333333;"><span id="printThis" style="font-size: medium;">Also available in PDF format.</span></span></a>

<h1 class="western" align="center"><b>Clarence Cheong</b></h1>
<p style="line-height: 1.5;" align="center"><span style="font-size: medium;"><b>Systems Architect | AI Solutions Engineer | Computer Vision</b> </span> <br>
Kuala Lumpur, Malaysia | clarence_han[at]hotmail[dot]com | <a href="https://github.com/BrightTux">https://github.com/BrightTux</a> <br>

<img align="center" alt="Python" width="22px" src="https://raw.githubusercontent.com/BrightTux/brighttux/master/icons/python-logo-generic.svg"/>
<img align="center" alt="Bash" width="22px" src="https://raw.githubusercontent.com/odb/official-bash-logo/master/assets/Logos/Icons/PNG/24x24.png"/>
<img align="center" alt="OpenCV" width="22px" src="https://raw.githubusercontent.com/BrightTux/brighttux/master/icons/487px-OpenCV_Logo_with_text_svg_version.svg.png"/>
<img align="center" alt="Tensorflow" width="22px" src="https://raw.githubusercontent.com/BrightTux/brighttux/master/icons/Tensorflow_logo.svg"/>
<img align="center" alt="Git" width="22px" src="https://raw.githubusercontent.com/BrightTux/brighttux/master/icons/512px-Git-logo.svg.png"/>
<img align="center" alt="Docker" width="22px" src="https://raw.githubusercontent.com/BrightTux/brighttux/master/icons/free-docker-logo_svgstack_com_50121780321196.svg"/>

</p>

<script>
console.log("Use printcv() to set certain elements to hidden");

function printcv()
{
  console.log("function printcv called");
  
  document.getElementById("printThis").style.visibility = "hidden"; 
  document.getElementsByClassName("page__title")[0].style.visibility = "hidden";
  document.getElementsByClassName("btn btn--inverse")[0].style.visibility = "hidden";
  document.getElementById("publicationslist").style.visibility = "hidden";
  document.getElementsByClassName("author__avatar")[0].style.visibility ="hidden";
  document.getElementsByClassName("author__name")[0].style.visibility ="hidden";
  document.getElementsByClassName("author__bio")[0].style.visibility ="hidden";
  
  document.getElementById("printThis").style.display= "none";
  document.getElementsByClassName("page__title")[0].style.display= "none";
  document.getElementsByClassName("btn btn--inverse")[0].style.display= "none";
  document.getElementById("publicationslist").style.display= "none";
  document.getElementsByClassName("author__avatar")[0].style.display= "none";
  document.getElementsByClassName("author__name")[0].style.display= "none";
  document.getElementsByClassName("author__bio")[0].style.display= "none";
  document.getElementsByClassName("page__footer")[0].style.display= "none";

  
  console.log("Remember to change the scale to 72% before printing - use Chrome/Linux");

}

</script>

<h2>Professional Summary</h2>

Versatile and systems-driven Solutions Engineer and AI Architect with over a decade of multi-disciplinary experience spanning Computer Vision (CV), Enterprise Software, Cloud Infrastructure, and Legacy Mainframe integration. Proven track record of bridging the gap between deep tech research and production-grade, distributed deployments. Expert in designing end-to-end AI pipelines—ranging from custom LLM RAG frameworks on GCP to large-scale video analytics engines for Smart Cities—while orchestrating containerized environments and edge-AI runtimes.

<h2>Core Competencies</h2>

* Architectures: End-to-End AI/ML Pipelines, RAG Frameworks, Distributed Systems, Microservices, Edge AI
* Computer Vision & Deep Learning: Object Detection/Tracking, Person Re-Identification, OCR (Synthetic Data Gen), OpenVINO, TensorFlow, Keras
* DevOps & Cloud Infrastructure: Docker, Ansible, AWS (EC2/S3), GCP, CI/CD, Shell Scripting, Linux System Admin
* Enterprise Integration: Enterprise APIs, Relational & NoSQL Databases (SQL, MongoDB), Mainframe (COBOL, JCL, z/OS), ITIL Incident & Crisis Management
* Full-Stack & Automation: Python, C++, Flask, JavaScript, PHP, Visual Basic, Automations, PyQt GUI Development

<h2>Professional Experience</h2>

<h4>Almex System Technology Asia (Almex-STA) | MY (Remote with Tokyo HQ)</h4>
<b></b>Senior AI Solutions Engineer</b> | May 2019-Present
  
  * <b>Architected & Deployed Enterprise RAG Infrastructure</b>: Co-designed and built an end-to-end Retrieval-Augmented Generation (RAG) Chatbot ecosystem hosted on GCP. Developed secure, scalable API endpoints for dynamic Knowledge Base updates and engineered an automated evaluation framework to audit pipeline relevance, faithfulness, and mitigation of hallucinations.
  * <b>Designed CV Pipelines from POC to Production</b>: Formulated technical proposals, researched architectures, and developed Proof of Concepts (POCs) for mission-critical CV products, including an Invoice OCR document classification engine and a Person Re-Identification system demonstrated at international trade fairs.
  * <b>Optimized Edge AI Deployment & System Integration</b>: Co-authored high-performance API integrations for FLIR AX8 Thermal Cameras featuring real-time face detection and blackbody-calibrated thermal corrections. Optimized deep learning models utilizing Intel's OpenVINO toolkit for deployment at the edge.
  * <b>Automated Cross-Workstation Orchestration</b>: Overhauled an internal image-labeling application by implementing a MongoDB data layer and integrating automated text-detection algorithms. Streamlined installation friction across multiple distributed workstations via Ansible configuration management.
  * <b>Engineered Complex ML Data Synthesis Systems</b>: Built custom ML data tools, including a synthetic Japanese character OCR training system utilizing font glyph checking and canvas-overflow validation, an enhanced SynthText background-generation engine manipulating depth and segmentation maps, and an FCOS-styled tfrecord translation pipeline.

Tools used: Python, Docker, OpenVINO, GCP, Ansible, TensorFlow, OpenCV, Flask, MongoDB, Bash, PyQt.
      

<h4>Multimedia University | MY</h4>
<b>Computer Vision Research Scholar</b> | Oct 2016 - Apr 2019

* <b>Engineered Video Analytics Frameworks</b>: Directed semantic extraction and data preprocessing workflows for project SHERLOCK, a large-scale, multi-camera video analytics initiative optimized for smart city long-term surveillance.
* IP Creation & Research Leadership: Successfully obtained intellectual property copyright for the developed core vehicle semantic retrieval engine. Published 2 peer-reviewed IEEE/Springer international conference papers and presented findings to industry stakeholders.

Tools used: C++, OpenCV, Python, JavaScript, Linux.
  
<h4>Freelance & International Research Consultant | MY / TW</h4>
<b>AI Solutions Consultant</b> | Jun 2018 – Feb 2019

* <b>Retail Store Analytics Solution (Freelance)</b>: Designed and deployed an edge-to-cloud customer analytics pipeline using Raspberry Pi nodes and custom deep learning models. Streamlined gender and behavioral inference processing on the edge before structured JSON data payloads were shipped to AWS cloud buckets for client business-intelligence consumption.
* <b>Vehicle Trajectory Analytics (Research Intern - National Chung Cheng University, TW)</b>: Researched and prototyped deep CNN architectures to handle automated vehicle trajectory classification under the supervision of Professor Wen-Nung Lie.

Tools used: AWS (EC2/S3), Docker, Raspberry Pi, Keras, TensorFlow, OpenCV, Python.
  
<h4>Hewlett Packard Enterprise (HPE) | MY</h4>
<b>Application Management & Service Delivery Engineer</b> | Sept 2012 – Sept 2016

* <b>High-Availability Production Systems Support</b>: Provided Tier-3 24/7 technical incident and crisis management for CIMB Bank's core payment channels (including IBG, Autopay, Remittance, and Direct Debit), ensuring zero-downtime operations for critical financial traffic.
* <b>Cross-Platform Systems Engineering</b>: Interfaced directly with client stakeholders and IT operations teams to implement data extraction applications for the enterprise-wide "CIMB 1 Platform" banking migration project.

Tools used: Mainframe z/OS, COBOL, JCL, CA-7, Unix Shell Scripting, SQL, Visual Basic.

<h4>Multimedia University | MY</h4>
<b>Research Assistant & Web Systems Developer</b> | Aug 2010 – Jan 2012

* Designed, implemented, and managed a centralized Content Management System (CMS) utilized by university staff to audit and track R&D progress. Successfully launched the software into active production, sustaining a 5-year operational lifecycle until retirement.

Tools used: PHP, SQL, HTML/CSS, WAMP Server.

<h4>Education</h4>

* <b>M.S. in Information Technology</b> | Multimedia University, 2021
    * Thesis Topic: Extraction and Retrieval of Object Semantics for Long-Term Car Park Surveillance Videos
* <b>B.Eng. in Electronics Majoring in Multimedia</b> | Multimedia University, 2012
    * Thesis Topic: Speaker Voice Recognition
* <b>Diploma in Technology, Mechatronics</b> | Tunku Abdul Rahman College, 2008


<h4>Selected Publications, Patents & Awards</h4>

* Copyright Owner: Core Retrieval Engine for Smart City Analytics.
* Primary Author: "Efficient Semantic-Based Vehicle Retrieval in Long-term Car Park Videos," IEEE ICMEW, 2019.
* Co-Author: "Vehicle Semantics Extraction and Retrieval for Long-Term Carpark Video Surveillance," Springer MMM, 2018.
* Co-Author: "On vehicle state tracking for long-term carpark video surveillance," IEEE ICSIPA, 2017.
* Silver Medalist: ITEX Malaysia (ICT & Multimedia Category), 2018.
* Bronze Medalist: Malaysia Technology Expo (Invention & Innovation Category), 2018.
* 2nd Runner Up: National A.I. Hackathon for Good, 2018.
