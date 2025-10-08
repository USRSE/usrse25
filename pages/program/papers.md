---
layout: page
title: Papers
description:
menubar: program
permalink: program/papers/
menubar_toc: true
set_last_modified: true
---

Authors of papers are expected to upload their paper to the Zenodo site for 
[USRSE'25 Conference Proceedings](https://zenodo.org/communities/usrse25/records?q=&l=list&p=1&s=10&sort=newest) 
**before** the conference begins.

<a name="p-spel"></a>
## SPEL - Software Package for E3SM Land Model: Code Understanding and Functional Unit Testing

_Peter Schwartz, Dali Wang, Peter Thornton, and Mungshu Shen_

The Software Package for E3SM Land Model (SPEL) is a
versatile tool that automates the creation and validation
of unit tests for user-selected subroutines within the ELM
code. SPEL explores variable usage and control flow based
on given macros and namelist configurations, and stores
this analysis in a database. SPEL analyzes ELM's Fortran
codebase to reveal code context, dependencies, and call
tree structures, addressing the challenges of understanding
large, complex scientific codes. SPEL also automates the
creation of standalone unit test programs for user-selected
modules, including dependency analysis, code generation,
and verification using bit-for-bit comparison. By
streamlining testing, debugging, and code analysis, SPEL
serves as a valuable asset for ELM development and
maintenance.

---

<a name="p-container"></a>
## Empirical Evaluation of Container Security and Reproducibility in Research Software Engineering

_Akshay Mittal and Vivek Venkatesan_

Containers have become a cornerstone of research software
engineering (RSE), offering portable and reproducible
environments for scientific computing and data-intensive
applications. However, recent studies have revealed that
container images used in research often carry hundreds of
security vulnerabilities, posing a significant threat to
both reproducibility and system integrity. In this paper,
we conduct an empirical study of container security across
a diverse corpus of publicly available research-oriented
container images—including images from domains such as
neuroscience, financial modeling, and high-performance
computing (HPC). We leverage multiple static vulnerability
scanners (Trivy, Anchore, and Clair) to identify Common
Vulnerabilities and Exposures (CVEs), quantify their
severity, and evaluate the efficacy of automated
remediation strategies including package updates, base
image optimization, and dependency pruning. Furthermore, we
apply DevSecOps principles by benchmarking image-hardening
techniques and analyzing reproducibility impacts after
updates. Our results show that a majority of
vulnerabilities stem from outdated system packages and
language-level dependencies, and that simple remediation
steps can eliminate over 60% of high-severity CVEs without
breaking reproducibility. We conclude with a set of best
practices for secure and reproducible container creation
tailored for RSE teams. This work bridges the gap between
security and reproducibility in containerized research
software, aligning with US-RSE’s focus on sustainable
software practices and secure coding for reproducible
science.

---

<a name="p-pop"></a>
## Producing High-fidelity Synthetic Population Ensembles at Scale

_James Gaboardi, Joseph Tuccillo, Jacob Isber, and Joshua
Dunkley_

Used within social simulations, synthetic population
ensembles enable uncertainty quantification (UQ) methods
for obtaining more robust model inference and prediction. A
synthetic population ensemble is a series of plausible
virtual reconstructions of an area's population at the
granularity of people and residences, generated
stochastically to preserve privacy of the source population
survey's respondents. In this paper, we demonstrate the
production of large synthetic population ensembles for the
US via Oak Ridge National Laboratory's UrbanPop framework
to support modeling of high spatial resolution energy
affordability metrics from nationwide social surveys in
collaboration with the FusionACS project. Our initial task
involves creating ensembles for 17 US metropolitan areas,
each consisting of 41 population instances (a base
realization and 40 replicates). To accomplish this task at
scale, we configured an integrated system comprised of a
research cloud, virtual containerization, GPU-enhanced
functionality, and a dual API/CLI to interact with
UrbanPop's maturing Likeness Python ecosystem. We observe a
reduction in theoretical execution time while maintaining
high-fidelity approximations of residential totals by
metropolitan area and the demographic characteristics of
neighborhoods. We discuss expansion of our approach to
produce synthetic population ensembles for the entire US,
particularly plans to establish automated workflows for job
orchestration to increase computational efficiency, as well
as provide outlook for broadening applications of the
ensembles.

---

<a name="p-lammps"></a>
## LAMMPS: A Case Study For Applying Modern Software Engineering to an Established Research Software Package

_Axel Kohlmeyer and Richard Berger_

We review various changes made in recent years to the
software development process of the LAMMPS simulation software
package and the software itself. We discuss how those
changes have impacted the effort and workflow required to
develop and maintain a software package that has been in
existence for more than 30 years and where a significant
part of the code base is contributed by external developers. We
also look into how those changes have affected the code quality
and ease of modifying and extending the software while at the
same time its audience has changed from a cohort with a generally
strong software development background to a group containing
many researchers with limited software development skills.
We explore how this contributes to LAMMPS’ significant growth
in popularity in that time. We close with an outlook on future
steps.

---

<a name="p-atr"></a>
## Integrating ATR Software with University HPC Infrastructure: balancing diverse compute needs

_Christine Roughan and Rebecca Koeser_

There is increasing interest in automated text recognition
(ATR) tools from faculty and students in the humanities and
social sciences, as well as from university library
professionals. Further, there is interest in the ability to
train or fine-tune such machine learning models because
out-of-the-box tools often return subpar results for
historical or otherwise low-resource languages. In this
paper, we report on our contributions to the implementation
of an open-source ATR platform (eScriptorium) on university
hardware and in a Slurm-managed high-performance computing
(HPC) environment. We comment on modifications required for
deployment, authentication, and HPC integration, as well as
on decisions made regarding code modularity and strategies
to handle the diverse runtime and compute requirements of
user-submitted model training tasks.

---

<a name="p-aquillm"></a>
## AquiLLM: a RAG Tool for Capturing Tacit Knowledge in Research Groups

_Chandler Campbell, Bernie Boscoe, and Tuan Do_

Research groups face persistent challenges in capturing,
storing, and retrieving knowledge that is distributed
across team members. Although structured data intended for
analysis and publication is often well managed, much of a
group's collective knowledge remains informal, fragmented,
or undocumented—often passed down orally through meetings,
mentoring, and day-to-day collaboration. This includes
private resources such as emails, meeting notes, training
materials, and ad hoc documentation. Together, these
reflect the group's tacit knowledge—the informal,
experience-based expertise that underlies much of their
work. Accessing this knowledge can be difficult, requiring
significant time and insider understanding.
Retrieval-augmented generation (RAG) systems offer
promising solutions by enabling users to query and generate
responses grounded in relevant source material. However,
most current RAG-LLM systems are oriented toward public
documents and overlook the privacy concerns of internal
research materials. We introduce AquiLLM (pronounced
ah-quill-em), a lightweight, modular RAG system designed to
meet the needs of research groups. AquiLLM supports varied
document types and configurable privacy settings, enabling
more effective access to both formal and informal knowledge
within scholarly groups.

---

<a name="p-mit"></a>
## MIT Lincoln Laboratory: A Case Study on Improving Software Support for Research Projects

_Daniel Strassler, Gabe Elkin, Curran Schiefelbein, Daniel
Herring, Ian Jessen, David Johnson, Santiago Paredes, Tod
Shannon, and Jim Flavin_

Software plays an ever-increasing role in complex system
development and prototyping, and in recent years, MIT
Lincoln Laboratory has sought to improve both the
effectiveness and culture surrounding software engineering
in execution of its mission. The Homeland Protection and Air Traffic Control
Division conducted an internal study to examine challenges
to effective and efficient research software development,
and to identify ways to strengthen both the culture and
execution for greater impact on our mission. Key findings of this study
fell into three main categories: 1 - project attributes
that influence how software development activities must be
conducted and managed, 2 - potential efficiencies from
centralization, 3 – opportunities to improve staffing and
culture with respect to software practitioners. The study
delivered actionable recommendations, including
centralizing and standardizing software support tooling,
developing a common database to help match the right
software talent and needs to projects, and creating a
software stakeholder panel to assist with continued improvement.

---

<a name="p-nextflow"></a>
## Optimizing Nextflow-based Software on Shared HPC Resources: A Case Study with make_lastz_chains

_Nil Tianchen Mu, William Dizon, Glen Otero, and Torey
Battelle_

Nextflow is a widely adopted workflow manager in the
bioinformatics community, known for its scalability,
portability, and reproducibility. However, on shared HPC
clusters that use the Slurm job scheduler and the Fairshare
score to record historical resource usage and determine
current job queuing positions, individual Nextflow job
submissions negatively impact user Fairshare scores and
lead to extended queue wait times. In this paper, we share
practical observations from supporting researchers running
the Hiller Lab make_lastz_chains pipeline, which uses
Nextflow to orchestrate genome alignment with LASTZ and
related UCSC tools, on the Arizona State University
supercomputers. We identify key challenges and solutions
regarding scheduling, Fairshare impact, and capturing Slurm
errors. We would like to share these observations and
practical considerations with researchers, RSEs, and HPC
system administrators in order to improve management of
Nextflow workflows on shared HPC resources, foster more
efficient resource utilization, and a smoother user
experience.

---

<a name="p-github"></a>
## An Empirical Survey of GitHub Repositories at U.S. R2 and Doctoral/Professional Universities

_Samuel Schwartz and Anthony Dario_

Understanding the landscape of Research Software
Engineering (RSE) projects, and basic information about RSE
repositories such as how many are out there to begin with,
is an area of discovery ripe for scholarship.
We position this five page short paper, which focuses on US
universities with "R2" or "Doctoral/Professional" Carnegie
classifications, as a modest intermediary step in a
multi-paper arc examining RSE repositories in a variety of
research contexts; an arc which has previously examined RSE
repositories in the US National Laboratory system and R1
universities.

In this work we report to the community our findings on
these research questions: What are all the GitHub
repositories related to US R2 and Doctoral/Professional
universities? Of those, which are RSE projects? Which of
these RSE projects have communities larger than just the
core authors? How healthy are they? And how do all of the
above questions compare to the R1 university context?
We find there are both fewer GitHub repositories and fewer
RSE repositories at R2 than at R1 institutions, and fewer
at doctoral universities than at R2s. Of these fewer RSE
projects at R2s and doctoral universities, more of them had
a community than RSE projects at R1 universities. While R1
and doctoral universities have similar profiles of
healthy/dying/dead repositories, R2 RSE repositories are
less likely to be active and more likely to be dead.
We also include the number of RSE repositories associated
with each R2 and Doctoral/Professional university as a five
page appendix.

---

<a name="p-trail"></a>
## TRAIL: Audit Trails for Enhanced Reproducibility and Observability of Research Computing

_Jake Rosenberg, Richard Cardone, Gilbert Curbelo, Vanessa
Gonzalez, Steve Black, Sal Tijerina, Mayal Dahan, and Dan
Stanzione_

As research projects grow more complex and re-
searchers use a mix of tools - command-line scripts, science
gateways, and Jupyter notebooks - it becomes increasingly
difficult to track exactly how a final result was produced.
Each tool often keeps its own logs, making it hard to
reconstruct thefull sequence of computational steps. This lack of
end-to-end visibility poses a serious challenge for scientific
reproducibility. Yet advanced computing remains a critical part of nearly
every field of academic research, and researchers continue to
rely on a wide range of interfaces to run their scientific
software. To address this challenge, the Advanced Computing Interfaces
group at the Texas Advanced Computing Center (TACC) created a
system that collates logs from multiple sources - science
gateways, Jupyter notebooks, and the Tapis platform - into one unified
“audit trail.” The TACC Research Audit and Integration of
Logs (TRAIL) system allows researchers and staff to follow
the complete path a dataset or file took: from the moment it was
first uploaded to TACC, through every step of computation,
to the final result. This kind of tracking helps ensure scientific
results can be reproduced and gives advanced computing services
better insight into how data and resources are being used.

---

<a name="p-fortran"></a>
## Idiomatic Correctness-Checking via Julienne in Fortran 2023

_Damian Rouson, Dan Bonachea, and Katherine Rasmussen_

This paper presents a unified approach to unit testing and
runtime assertion-checking using Fortran 2023.  The paper
describes the support for the approach in the Julienne
framework.  Julienne leverages recent Fortran standards to
implement object-oriented design patterns, support testing
parallel programs, and implement functional programming
patterns in order to craft idioms inspired by
natural-language expressions. The presented idioms employ
novel user-defined operators to write expressions that
evaluate to a test-diagnosis or assertion-diagnosis object
encapsulating two components: (1) the test outcome or
assertion outcome and (2) an automatically generated
diagnostic string.  Two other novel aspects of the approach
include (1) the ability to enforce assertions inside pure
procedures and (2) the ability to output rich diagnostic
information inside pure procedures during error termination
when assertions fail.  The latter capability mitigates
against a reason that Fortran programmers commonly cite for
not writing pure procedures: difficulty obtaining useful
program output inside pure procedures when debugging code. 
This paper demonstrates how the adoption of the proposed
idioms leads naturally to a unifying theme across two
otherwise disparate technologies: unit testing and runtime
assertion-checking.  Finally, this paper presents progress
on integrating these technologies into the Matcha
high-performance computing application and the Fiats deep
learning library.

---

<a name="p-toolsybio"></a>
## ToolsyBio: A retrieval-augmented generation system for navigating the bioinformatics software landscape

_Van Truong and Marylyn Ritchie_

Researchers increasingly rely on free and open-source
software (FOSS) for computational analysis across the life
sciences. However, the growing volume and diversity of
available tools make it difficult to discover, understand,
and select appropriate software for specific tasks. We
present ToolsyBio, a modular system that uses
retrieval-augmented generation (RAG) to assist researchers
in exploring the bioinformatics software landscape via
natural language queries. ToolsyBio is built on structured
metadata from the bio.tools registry and semantically
enriched with concepts from EDAM, a controlled vocabulary
for bioscientific data analysis and data management. The
system retrieves relevant tool descriptions using a vector
store (ChromaDB) and generates grounded responses using a
locally served large language model (LLM) via Ollama. We
describe the system’s architecture, implementation, and
potential for improving the findability and usability of
bioinformatics tools through a conversational interface.

---

<a name="p-syncflow"></a>
## SyncFlow: A Scalable Platform for Multimodal Learning Analytics

_Umesh Timalsina, Eduardo Davalos, Nihar Purshottam Sanda,
Yike Zhang, Joyce Horn Fonteles, Ashwin T S, and Gautam
Biswas_

The new wave of educational technologies (EdTech) is
revolutionizing digital education but faces challenges with
the complexities of multimodal human interactions in
computer-based learning environments (CBLEs). Researchers
are investigating multimodal learning analytics (MMLA) as a
comprehensive approach to analyzing and supporting
students. However, the integration of MMLA into scalable
and automated learning environments is difficult because of
the absence of standardized solutions for reliable
multimodal data collection and analysis. Current MMLA
systems are limited in their compatibility with modern web
technologies and infrastructure for browser and
Internet-of-Things (IoT) integration. To address these
challenges, we introduce SyncFlow, an open-source platform
offering scalable, robust cloud infrastructure for
automated MMLA deployments. This paper presents an
end-to-end application of SyncFlow, demonstrating its 
integration with AI-powered CBLEs and illustrating its 
capabilities. SyncFlow bridges critical gaps in MMLA data 
collection and processing, supporting scalable and impactful 
CBLEs in real-world settings.

---
