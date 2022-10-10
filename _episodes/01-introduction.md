---
title: "SABS:R3 Open Source Software Projects"
teaching: 30
exercises: 0
questions:
- "For SABS students, What is the year-long software project you will be working on?"
objectives:
- "Provide descriptions of each of the four projects."
- "Explain how the software engineering projects will work."
keypoints:
- "You will have already been sorted into your projects groups via canvas." 
- "You will meet the supervisors for the projects on the Monday 24th October, who will 
  give presentations on each project, and this whole week will be spent getting up to 
  speed on your project" 
- "Generally, you will work on the projects every wednesday (not during Cells and 
  Systems), with the opportunity for doing this at the DTC building if you wish."
---

Students in the SABS:R3 CDT will undertake a year-long software engineering project as 
part of their first year. These projects are developed jointly by our academic and 
industrial partners, and selected through an open competition judged by members of the 
SABS R3 External Advisory Board. The project teams are mentored throughout the year by 
SABS staff and the groups putting forward the projects, with regular coding sessions 
built into the programme. All project outputs will be released to the research community 
under a 3-Clause BSD license, together if possible with a joint publication written by 
the students and the academic and industrial researchers involved. At the end of the 
first year, these projects will be demonstrated to the industrial partners and the new 
cohort of first-year students. Each team will continue to support these open source 
projects over the four years of their programme, allowing the development of a practical 
understanding of how software is sustained.

There are three different projects for 2022/2023, each described under the headings 
below. Each student will already be pre-assigned to a project via canvas.

## Project 1 - The Drug Discovery Game

**Company**: Roche

**Supervisors**: Dr Torsten Schindler (Roche), Dr Rosa-Maria Rodriguez-Sarmiento 
(Roche), Professor Garrett Morris, Fergus Boyles

**Project description**: 

Drug discovery is a multi-parameter optimization problem where many (sometimes 
competing) objectives must simultaneously be met for a new compound to fulfill the 
desired set of molecular properties, or Target Compound Profile (TCP) according to 
indication and target. The TCP compiles the physicochemical, pharmacological, and 
metabolic properties the molecules must achieve to be of clinical interest.

Building upon the prototype developed by SABS 2020 and 2021 Drug Discovery Game 
students, and ideas behind The Drug Discovery Game [1] by Brian McGuiness and Robert 
Merrit (a Velcro-based game), we are developing an improved computer game that aims to 
mimic the initial workflow of a medicinal chemist on achieving a desired TCP and is 
based on drug discovery cases published in literature.

The game covers several phases of the drug discovery process. Provided with only data 
from a high throughput screening (HTS), or by using an information driven approach 
starting with competitor compounds, the initial focus will be a hit expansion or a hit 
to lead identification phase. More complex processes of lead optimization and clinical 
candidate discovery will be added to the game in later stages.

On one hand, the game will serve as a tool that stimulates the player’s interest in AI 
guidance and medicinal chemistry. It will also reinforce knowledge and instill in the 
user the benefits of using a systematic approach rather than random selections. On the 
other hand, it will allow the training of artificial agents which can be used to assist 
learning medicinal chemists in making strategic decisions at different stages of drug 
discovery similar to an augmented intelligence system for medicinal chemists.

The current version uses a web front end and supports multiple users, and offers two 
kinds of game play: (i) choosing from a prescribed set of R1 and R2 groups on a fixed 
scaffold; and (ii) sketching a compound from scratch. In the first case, the binding 
data comes from published experiments, while their pharmacological and metabolic 
properties come from commercial predictive models. In the second case, ML models have 
been developed to predict all of these properties for whatever molecule is sketched.

In this phase of the project, we will explore (i) structure-based drug design through 
the introduction of protein-ligand docking; (ii) develop AI-based tools that use 
reinforcement learning to design new compounds using a new multi-objective reward 
function; (iii) expand the game to other targets, beyond the current target, matrix 
metalloprotease-12, MMP-12.

[1] McGuinness, Brian F.  and Merritt, J. Robert: “Illustrating Medicinal Chemistry 
    Through an Interactive Demo: The Drug Discovery Game”, Poster presented at the 2016 
    Fall American Chemical Society Meeting. https://youtu.be/uH4DioPcbog


## Project 2 - Mathematical and computational modelling in epidemiology

**Company**: Roche

**Supervisors**: Ben Lambert, David Gavaghan, Dr Annabelle Lemenuel-Diot  (Roche), 
Richard Creswell, Ioana Bouros, Kit Gallagher

**Project description**:  

This project would build on the infrastructure of SABS students in 2021-22 who worked to 
produce a web-based application for simulating epidemics using transmission dynamics 
models. In particular, the group developed Epiabm, which is a fully tested, open-source 
software package for epidemiological agent-based modelling that re-implements the 
well-known CovidSim model from the MRC Centre for Global Infectious Disease Analysis at 
Imperial College London. The model builds an age-stratified, spatially heterogeneous 
population and offers a modular approach to configure and run epidemic scenarios, 
allowing for a broad scope of investigative and comparative studies. Two simulation 
backends are provided: a pedagogical Python backend (with full functionality) and a high 
performance C++ backend for use with larger population simulations. Both are highly 
modular, with comprehensive testing and documentation for ease of understanding and 
extensibility. The Epiabm software is publicly available through GitHub at 
\https://github.com/SABS-R3-Epidemiology/epiabm.

The next stage in the development of Epiabm will involve the implementation of both 
non-pharmaceutical interventions that aim to curtail the spread of the disease 
(lockdowns, mask-wearing, hand-washing etc), and pharmaceutical and medical 
interventions such as vaccination and administration of anti-viral drugs. Should time 
allow, the project may involve extension of the Epiabm software to other diseases of 
interest to our industrial collaborators (Roche) such as seasonal influenza epidemics.


## Project 3 - Computer Vision-based Clinical Image Quality Control

**Company**: GE Healthcare

**Supervisors**: Chris Page (GE), Vicente Grau, Martin Robinson, Emmanuel Oladokun, 
Julia Krol, Ian McFarlane

**Project description**: 

Imaging in clinical trials typically involves collecting data from multiple sites 
centrally for analysis. Data quality can vary considerably due to differences in 
technology and local procedures. Ingestion requires quality checks (to ensure adherence 
to the trial protocol) and robust deidentification (to meet privacy and GCP 
regulations), which can be painstakingly manual.

A 2020-22 SABS:R3 project developed a standardised, open, extensible framework to check 
and update image metadata according to user-defined rules, and a Tesseract-based 
annotation detection and masking tool for automatically masking identifiable 
information. It functions as an in-stream device, with accepted data being exported to a 
repository, and rejected data routed for follow-up.

The aim of this project is to develop new plug-ins to extend QC to the pixel data, using 
computer vision techniques to characterise the images. The existing plug-in for 
annotation removal will be enhanced by allowing user-provided whitelists. Other possible 
QC plugin extensions to be developed include anatomical region/completeness (e.g. to 
label the images as head, chest, abdomen, or pelvis; or label organs) or detecting use 
of contrast or modality-specific artefacts (particularly for MRI).

GE will provide domain expertise, documented user requirements and regular feedback. We 
also propose “day-in-the-life” sessions, giving a flavour of our roles in software 
engineering and pharmaceutical R&D.
Beyond a grounding in software engineering, students will gain expertise with medical 
image processing, computer vision techniques and libraries (e.g. OpenCV) and best 
practice in the pharma industry (software validation, regulation, data integrity).

## Schedule

The projects will begin in the week of the 24th October. Each group will be contacted by 
the supervisors for their project for an introductory meeting and/or a timetable for the 
week. The full week of the 24-28th October will be devoted to the projects, with the 
exact schedule determined on an individual project basis.

After this week, you will be able to work on the projects every Wednesday (except during 
the Cells and Systems module), with space being available at the DTC to work in person 
with your group. It will not be necessary to be at the DTC in person if you do not wish, 
and we will ensure that you are able to dial in remotely if necessary. You will also 
have the full week of the 12-17th Dec, and three weeks in early 2023, to work on the 
projects.


{% include links.md %}

