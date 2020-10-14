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
- "You will meet the supervisors for the projects on the Monday 26th October, who will 
  give presentations on each project, and this whole week will be spent getting up to 
  speed on your project" 
- "Generally, you will work on the projects every wednesday (not during Cells and 
  Systems), with the opportunity for doing this at the DTC building if you wish."
---


## Project 1 - Automated Data Extraction to Future-Proof Therapeutic and Natural 
Antibody Databases

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
simultaneously be met in order for a new compound to fulfill the desired target compound 
profile (TCP) according to indication and target. The TCP compiles the characteristics 
the molecules must achieve in order to be of clinical interest.

Building upon the ideas behind The Drug Discovery Game [1] by Brian McGuiness and Robert 
Merrit, a Velcro-based game, we want to create an improved computer game that aims to 
mimic the initial workflow of a medicinal chemist on achieving a desired TCP and it will 
be based on drug discovery cases published in literature.

The game should cover several phases of the drug discovery process. Provided only with 
data from a high throughput screening (HTS), or by using an information driven approach 
starting with competitor compounds, the initial focus will be a hit expansion or a hit 
to lead identification phase. More complex processes of lead optimization and clinical 
candidate discovery will be added to the game in later stages.

On one hand, the game will serve as a tool that stimulates the player’s interest in AI 
guidance and medicinal chemistry. It will also reinforce knowledge and instill in the 
user the benefits to use a systematic approach rather than random selections.

On the other hand, it will allow the training of artificial agents which can be used to 
assist learning medicinal chemists in making strategic decisions at different stages of 
drug discovery similar to an augmented intelligence system for medicinal chemists.

[1] McGuinness, Brian F.  and Merritt, J. Robert: “Illustrating Medicinal Chemistry Through an Interactive Demo: The Drug Discovery Game”, Poster presented at the 2016 Fall American Chemical Society Meeting. https://youtu.be/uH4DioPcbog

## Project 3 - Development of Open Source Epidemiology Modelling Software 

**Company**: Dr Annabelle Lemenuel-Diot (Roche)
**Supervisors**: David Gavaghan, Ben Lambert, Martin Robinson and Robin Thompson 

**Project description**:  

The current Covid-19 pandemic has highlighted the crucial role that mathematical and 
computational modelling can play in understanding the spread of infectious diseases, and 
in assessing the possible impact of any mitigation strategies that are put in place to 
control that spread. However, in shining a spotlight on this area of research, attention 
has inevitably turned to the manner in which the mathematical models and numerical 
algorithms have been instantiated in software. In common with almost all current 
academic codes, most of the software for modelling epidemic spread that was in existence 
at the start of the pandemic was developed principally to underpin the publication of 
academic papers. Code development therefore followed the standard norms in place within 
the discipline so that much of the subsequent criticism from professional research 
software engineers was perhaps unfair. A more valid criticism might be to argue that 
there is a very pressing need to develop robust open source modelling software that can 
be used in the future. 

The goal of the proposed software project is to develop just such a robust software 
platform for the modelling of the transmission of infectious diseases. Software will be 
developed initially with the aim of providing a pedagogical tool for use in universities 
(and secondary schools) and in industrial settings in teaching both the modelling of 
epidemic spread and the importance of using robust software engineering principles. We 
will use the current Covid-19 pandemic as the key example due to the ready availability 
of extensive data. We will start with the simplest discrete and continuous models that 
simply look at the evolution in time of disease spread, and will extend this to 
consideration of spatial variation as the project develops. Particular attention will be 
paid to the key issues of the sensitivity of model outputs and predictions to model 
parameters, and to the inverse problem of estimating key parameters from data. Extensive 
tutorial examples (as Jupyter Notebooks) will be developed. Our ultimate goal will be to 
reproduce robust and sustainable versions of some of the key current codes that are 
being used to model the current pandemic. 

To allow the platform to be used as a teaching tool, a subsidiary project will also 
develop a web app that allows interactive use of the models. Particular attention will 
be paid to the visualisation of outputs so that the material is accessible to secondary 
school students.  

Much of the underpinning mathematical modelling, numerical algorithms, and statistical 
inference techniques will be common with the PKPD modelling project that was undertaken 
in collaboration with Roche in the last academic year (and that is still ongoing). This 
existing software will allow much more rapid progress to be made on this epidemiology 
modelling project.

The longer-term goal is to implement the Covid-19 transmission model currently being 
developed by Roche within the web-app. This model is an SEIR ODE-model with compartments 
for groups with differing infectivity. The app could be used to forward simulate 
epidemics across different countries and also be used for inference when given a data 
source.

## Project 4 - Extensible Clinical Imaging QC Tool

**Company**: GE Healthcare
**Supervisors**: Chris Page, Zak Catherall, Vicente Grau, Martin Robinson

**Project description**:  

Imaging in clinical trials typically involves collecting data from multiple sites 
centrally for analysis.  Data quality can vary considerably due to differences in 
technology and local procedures.  Ingestion requires robust deidentification (to meet 
privacy and GCP regulations) and quality checks (to ensure adherence to the trial 
protocol) , both of which can be painstakingly manual.  Initiatives providing data to 
researchers, such as UK Biobank or CSDR, perform further recoding on egress.  These 
processes benefit from automatic checks and updates on image (meta)data according to 
user-defined rules.

Existing tools are typically proprietary or focussed on a specific modality or 
therapeutic area.  We believe data quality is fundamental and such tools are 
precompetitive: a standardised, open, extensible approach benefits the research 
community.

We envision an in-stream device that receives DICOM data, accepts or rejects based on 
configurable criteria (specific to the trial, site, anatomy and/or modality), performs 
corrections or redactions, and finally exports to a repository.

The focus will be on checking, updating and tracking metadata according to a defined 
schema (real-world examples will be provided).  The software shall have a plugin 
architecture, allowing e.g. image QC modules to be added in future

GE will provide domain expertise, documented user requirements and regular feedback.  We 
also propose “day-in-the-life” sessions, giving a flavour of our roles in software 
engineering and pharmaceutical R&D. Beyond a grounding in software engineering, students 
will gain expertise with the DICOM medical imaging standard (data format and validation, 
networking) and best practice in the pharma industry (software validation, regulation, 
data integrity).


## Hand-in

Your should hand-in your URL for the GitHub repository for each group, and the URL to 
where your web application is deployed. Please email these, along with the names of 
those in your group, to 
[martin.robinson@cs.ox.ac.uk](mailto:martin.robinson@cs.ox.ac.uk) by 5:30pm on Friday 
30th Oct.

{% include links.md %}

