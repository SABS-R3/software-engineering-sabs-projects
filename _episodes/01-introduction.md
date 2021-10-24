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
- "You will meet the supervisors for the projects on the Monday 25th October, who will 
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

There are four different projects for 2020/2021, each described under the headings below. 
Each student will already be pre-assigned to a project via canvas.

## Project 1 - Automated Data Extraction to Future-Proof Therapeutic and Natural Antibody Databases

**Company**: Seb Kelm (UCB), James Snowden (UCB), Anna Vangone (Roche), Iain Moal (GSK)

**Supervisors**: Professor Charlotte Deane, Claire Marks and Fergus Boyles

**Project description**:  

Databases play a central role in antibody informatics, pooling together previously 
dispersed sets of relevant amino acid/nucleotide sequences and solved structures into a 
consistent format with metadata to facilitate powerful statistical analyses. Since 2018, 
the Oxford Protein Informatics Group have created three new field-leading databases: the 
Observed Antibody Space (OAS) database — one of the largest repository of natural B-cell 
receptor repertoire sequencing data, Thera-SAbDab — the largest repository of sequence & 
structural information of all WHO-recognised therapeutic antibodies and nanobodies, and 
most recently CoV-AbDab — the only repository of sequence & structural information on 
coronavirus binding/neutralising antibodies. These databases were all manually curated 
and, though some have associated scripts to accelerate data formatting, none can harvest 
knowledge directly from the primary literature/other sources in an automated fashion.
These tools are used extensively across academia and industry in the development of 
novel antibody therapeutics and increasing their usability and accelerating their 
updating systems will make them an even more powerful in these realms. 

Throughout the year, your project will be to create frameworks that automate as much of 
the updating process as possible for each database. Thera-SAbDab is most likely to be 
completely automatable as its data sources are narrow and relatively consistent in 
format. Sources/input formats for OAS and CoV-AbDab, however, could prove too 
heterogenous for entirely automated data extraction. These subprojects may therefore 
also lead to Natural Language Processing assistants that draw papers/patents likely to 
contain relevant data to the attention of the curator. Throughout this project you can 
develop key skills in data science, including ‘scraping’ data from websites, database 
management, confidently interconverting between different data formats (including 
handling image inputs), and developing machine learning bots useful for targeted 
literature mining.

## Project 2 - The Drug Discovery Game

**Company**: Roche

**Supervisors**: Dr Torsten Schindler (Roche), Dr Rosa-Maria Rodriguez-Sarmiento 
(Roche), Professor Garrett Morris, Fergus Boyles

**Project description**: 

Drug discovery is a multi-parameter optimization problem where many properties must 
simultaneously be met for a new compound to fulfill the desired target compound profile 
(TCP) according to indication and target. The TCP compiles the physicochemical, 
pharmacological and metabolic properties the molecules must achieve in order to be of 
clinical interest.

Building upon the prototype developed by SABS 2020 Drug Discovery Game students, and 
ideas behind The Drug Discovery Game [1] by Brian McGuiness and Robert Merrit (a 
Velcro-based game), we will develop an improved computer game that aims to mimic the 
initial workflow of a medicinal chemist on achieving a desired TCP and it will be based 
on drug discovery cases published in literature.

The game covers several phases of the drug discovery process. Provided only with data 
from a high throughput screening (HTS), or by using an information driven approach 
starting with competitor compounds, the initial focus will be a hit expansion or a hit 
to lead identification phase. More complex processes of lead optimization and clinical 
candidate discovery will be added to the game in later stages.

On one hand, the game will serve as a tool that stimulates the player’s interest in AI 
guidance and medicinal chemistry. It will also reinforce knowledge and instill in the 
user the benefits to use a systematic approach rather than random selections.

On the other hand, it will allow the training of artificial agents which can be used to 
assist learning medicinal chemists in making strategic decisions at different stages of 
drug discovery similar to an augmented intelligence system for medicinal chemists.

[1] McGuinness, Brian F.  and Merritt, J. Robert: “Illustrating Medicinal Chemistry 
    Through an Interactive Demo: The Drug Discovery Game”, Poster presented at the 2016 
    Fall American Chemical Society Meeting. https://youtu.be/uH4DioPcbog


## Project 3 - Cost effectiveness of HPV vaccination in the Asia-Pacific Region

**Company**: Roche

**Supervisors**: Ben Lambert, David Gavaghan, Dr Annabelle Lemenuel-Diot (Roche)

**Project description**:  

This project would build on the infrastructure of SABS students in 2020-21 who worked to 
produce a web-based application for simulating epidemics using transmission dynamics 
models. This project aims to create an professionally engineered open-source codebase 
for dynamic age-stratified epidemiological-economic modelling for HPV in Laos (currently 
coded in Berkeley-Madonna). This would result in software which allows a user to select 
a set of inputs specific to the disease, then run the model for a range of scenarios. 
The software would then display metrics representing a cost effectiveness analysis and 
visualise the model outputs. The software would ideally include a graphical user 
interface to allow interactive exploration of the models aimed at public health 
policymakers. It may also allow users to upload epidemiological data and fit their 
models to them using either optimisation or Bayesian approaches. The tool would also 
allow automatic generation of a written report using the model results in a language and 
style appropriate for a health policymaker.

The resulting code from the project would contribute to a larger research project led by 
Shwe sin and Phetsavanh to model the cost-effectiveness of HPV vaccination in the 
Asia-Pacific region.


## Project 4 - Computer Vision-based Clinical Image Quality Control

**Company**: GE Healthcare

**Supervisors**: Chris Page (GE), Zak Catherall (GE), , Vicente Grau, Martin 
Robinson

**Project description**: 

Imaging in clinical trials typically involves collecting data from multiple sites 
centrally for analysis.  Data quality can vary considerably due to differences in 
technology and local procedures.  Ingestion requires quality checks (to ensure adherence 
to the trial protocol) and robust deidentification (to meet privacy and GCP 
regulations), which can be painstakingly manual.

A 2020-21 SABS:R3 project developed a standardised, open, extensible framework to check 
and update image metadata according to user-defined rules.  It functions as an in-stream 
device, with accepted data being exported to a repository, and rejected data routed for 
follow-up.

The aim of this project is to develop a plug-in to extend QC to the pixel data, using 
computer vision techniques to characterise the images.  Specific QC tasks may include 
checking for “burned-in” annotation (that often contains personally-identifiable 
information) and anatomical region/completeness (e.g. to label the images as head, 
chest, abdomen, or pelvis; or label organs).  Possible extensions include automatically 
masking identifiable information and extending QC checks e.g. to detecting use of 
contrast or modality-specific artefacts (particularly for MRI).

GE will provide domain expertise, documented user requirements and regular feedback.  We 
also propose “day-in-the-life” sessions, giving a flavour of our roles in software 
engineering and pharmaceutical R&D.

Beyond a grounding in software engineering, students will gain expertise with medical 
image processing, computer vision techniques and libraries (e.g. OpenCV) and best 
practice in the pharma industry (software validation, regulation, data integrity).


## Schedule

The projects will begin in the week of the 25th October. Each group will be contacted by 
the supervisors for their project for an introductory meeting and/or a timetable for the 
week. The full week of the 25-29th October will be devoted to the projects, with the 
exact schedule determined on an individual project basis.

After this week, you will be able to work on the projects every Wednesday (except during 
the Cells and Systems module), with space being available at the DTC to work in person 
with your group. It will not be necessary to be at the DTC in person if you do not wish, 
and we will ensure that you are able to dial in remotely if necessary. You will also 
have the full week of the 13-17th Dec, and 1st-5th March 2021, to work on the projects.


{% include links.md %}

