---
layout: page
title: Talks
description:
menubar: program
permalink: program/talks/
menubar_toc: true
set_last_modified: true
---

Speakers are asked to upload their slides to the Zenodo site for 
[USRSE'25 Conference Proceedings](https://zenodo.org/communities/usrse25/records?q=&l=list&p=1&s=10&sort=newest) 
as soon as possible, which may be before, during, or shortly after the conference.

<div id="accordion">

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading1">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse1"
aria-expanded="false" aria-controls="collapse1">
surveydown: An Open-Source, Markdown-Based Platform for
Programmable and Reproducible Surveys<br> John Helveston, Pingfan Hu, and Bogdan Bunea
</button>
</h5>
</div>

<div id="collapse1" class="collapse" aria-labelledby="heading1" data-parent="#accordion">
<div class="card-body">
<p> This talk introduces the surveydown R package1 and survey
platform. With surveydown, researchers can create
reproducible, programmable surveys using markdown and R
code chunks, leveraging the Quarto publication system and R
Shiny web application framework. While most survey
platforms rely on graphical interfaces or spreadsheets to
define survey content, surveydown uses plain text, enabling
version control and collaboration via tools like GitHub.
The package renders surveys as interactive Shiny web
applications, allowing for complex features like
conditional skip logic, dynamic question display, and
complex randomization. The package supports a diverse set
of question types and formatting options, and users can
leverage Shiny’s powerful reactive programming model to
create a wide variety of customized interactive features.
As an open-source platform, surveydown provides researchers
full control over their survey implementation, including
the survey application as well as where and how the
resulting response data are stored. Workflows are entirely
reproducible and integrate seamlessly with existing
workflows for data collection and analysis in R. At this
talk, you’ll not only learn how to build and deploy your
own interactive surveys using surveydown, but also how you
can join the growing community of contributors to the
project. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading2">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse2"
aria-expanded="false" aria-controls="collapse2">
Heterogeneous Distributed Data Management in Academia<br> Josh Borrow
</button>
</h5>
</div>

<div id="collapse2" class="collapse" aria-labelledby="heading2" data-parent="#accordion">
<div class="card-body">
<p> Comprehensive data management - access control, storage,
and replication - is a challenge even when dealing with a
single-site on premises architecture. For medium-to-large
academic projects, distributed across many institutes and
computing systems, this challenge is significantly
heightened. With such a heterogeneous computing setup -
from hardware, to networking, and policy - custom software
is necessitated. At the same time, academics are loath to
give up their POSIX file systems and ‘offline’ access to
data. In this talk, I will describe the Simons
Observatory’s data management framework that provides
access for our 1 PB/year data rates to 500 users across
three continents and four core computing nodes (national
labs and university clusters). I will specifically note the
significant architectural decisions that were necessary
given our academic infrastructure: from containerisation to
the use of trusted networks like Globus to power data
transfers, and the need for significant caching to empower
traditional academic workflows. The Advanced Simons
Observatory software suite is fully open source, and I will
signpost to our solutions throughout. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading3">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse3"
aria-expanded="false" aria-controls="collapse3">
Sustaining Growth of Scientific Software with the Software
Gardening Almanack<br> Dave Bunten and Gregory Way
</button>
</h5>
</div>

<div id="collapse3" class="collapse" aria-labelledby="heading3" data-parent="#accordion">
<div class="card-body">
<p> Scientific software doesn’t flourish by accident—it
requires thoughtful care, long-term commitment, and a
willingness to adapt. Just as gardeners consult almanacs to
navigate the seasons, scientific software developers
benefit from shared wisdom to help them nurture projects
through cycles of growth, stagnation, and renewal. The
Software Gardening Almanack is a community-driven
collection of insights, heuristics, and research-based
practices designed to help developers and maintainers grow
reproducible software that endures. The project offers both
a book to explore these ideas and a Python package to help
apply them in practice.

We’ll dig into patterns from scientific software projects
(for example, Pandas and Jupyter-based Python work) and
discuss how to plant good practices early, prune code when
needed, and prepare for inevitable droughts of attention or
funding. You'll leave with tools (including the Almanack
itself!) and metaphors for thinking about sustainability,
reproducibility, team health, and the evolving life of your
codebase. Whether you're cultivating a new project or
tending to legacy software, the Almanack offers a fresh,
grounded perspective on what it means to grow scientific
software for the long haul. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading4">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse4"
aria-expanded="false" aria-controls="collapse4">
Increasing the Accessibility of Quarto-Based NOAA Fisheries
Reports<br> Sophie Breitbart
</button>
</h5>
</div>

<div id="collapse4" class="collapse" aria-labelledby="heading4" data-parent="#accordion">
<div class="card-body">
<p> More than one in four American adults has a disability (1).
Individuals with certain disabilities may have difficulty
accessing information in documents created without
accessibility features. While many government documents are
required to meet the accessibility standards outlined in
Section 508 (2), manually adding accessibility features to
documents can be challenging and time-consuming. National
Oceanic and Atmospheric Administration (NOAA) Fisheries
scientists are expected to produce high-quality reports
that meet several criteria, including compliance with
Section 508. However, there are multiple bottlenecks that
prevent the report production process from being timely and
efficient, including the absence of a standardized,
reproducible workflow suitable across a variety of species
and fishery management regions. We are developing two R
packages (asar (3) and stockplotr (4)) that enable a
semi-automated, reproducible, and transparent process for
writing stock assessment reports with Quarto. A key
component of this workflow is the integration of features
that automatically increase the accessibility of the final
reports and require relatively little manual work by the
fisheries scientist. In this talk, I will share our
progress implementing PDF tagging, alternative text, and
acronym definitions in a Quarto-based workflow, as well as
lessons learned throughout the process. Adding
accessibility features to reproducible workflows based on
open source tools is a key way to increase access to
stakeholders with diverse abilities and roles within
fisheries management.
</p>
<p>
References

1. Okoro, C., Hollis, N., Cyrus, A., Griffin-Blake, S.
(2018). Prevalence of disabilities and health care access
by disability status and type among adults—United States,
2016. Centers for Disease Control and Prevention.
https://www.cdc.gov/mmwr/volumes/67/wr/mm6732a3.htm 
 
2. Section 508 of the Rehabilitation Act, as amended. Pub.
L. No. 29 U.S.C. §794d, 1973.

3. Schiano S, Breitbart S, Saul S (2025). asar: Build NOAA
Stock Assessment Report. R package version 1.2.0,
https://github.com/nmfs-ost/asar.

4. Schiano S, Breitbart S, Saul S (2025). stockplotr:
Tables and Figures for Stock   Assessments. R package
version 0.1.0, https://github.com/nmfs-ost/stockplotr. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading5">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse5"
aria-expanded="false" aria-controls="collapse5">
Efficient Documentation: Best Practices, Tools, and
Opportunities<br> Peter Williams
</button>
</h5>
</div>

<div id="collapse5" class="collapse" aria-labelledby="heading5" data-parent="#accordion">
<div class="card-body">
<p> Are you satisfied with your project’s documentation? Is
anyone? In many research projects, documentation is at best
an afterthought; in other cases, the aspirations are
loftier but the final product ends up feeling disorganized,
incomplete, or just plain ugly.

In this talk I will present a work-in-progress resource
dedicated to helping RSEs and others create better
documentation, more easily: documentation about
documentation. What are the best practices for designing,
writing, and publishing software documentation? What are
the best tools for implementing these best practices? While
these questions might occur to any kind of developer, the
resource especially focuses on the unique challenges
encountered in scientific software, such as: integrating
documentation with the research literature; linking code
with mathematical formalisms, graphics, and data; enabling
RSEs and researchers to write documentation
collaboratively; and getting professional credit for all of
the work that goes into accomplishing the above.

The philosophy of the resource is pragmatic. The vision is
efficient documentation: we want to empower RSEs and
researchers to create materials that are as good as they
can be given the inevitably limited time and resources that
can be spent on their creation. The emphasis therefore lies
on easy-to-use templates and recipes.

That being said, it is also valuable to think about
ambitious documentation: what kind of materials would we
create if we were given unlimited resources to do so? I
will conclude by arguing that, from this perspective, there
is a tremendous opportunity to build better documentation
tools that have the potential to transform not just how we
explain individual software projects, but how we
communicate all kinds of complex technical information in
the 21st century. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading6">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse6"
aria-expanded="false" aria-controls="collapse6">
Everything, All at Once, Yesterday: Creating Research
Software with Humanities Faculty<br> Jeri Wieringa and Mary Naydan
</button>
</h5>
</div>

<div id="collapse6" class="collapse" aria-labelledby="heading6" data-parent="#accordion">
<div class="card-body">
<p> A humanities faculty member comes to you with a grand idea
for a digital research project. As a scholar of literature,
they want to trace how the depictions of extraterrestrial
beings in works of science fiction change over time.
Because they want to look at historical changes in the
genre at scale, they intuit that computers are needed for
this task, but have no knowledge of programming, software
engineering, or data. Where are the texts you want to look
at? you ask. Luckily, the researcher replies, most of the
texts already have digital versions available in the
university library catalog! Taking a different tack, you
inquire, what is your research question? The researcher
replies that they are interested in how the science fiction
genre encodes the history of colonialism on Earth; however,
they are most interested in creating a beautifully-designed
public-facing tool – with an interactive timeline, map, and
search bar – that scholars in their field will use to
answer many possible research questions.

For Research Software Engineers in the humanities, this
scenario is commonplace. Unlike our peers in the sciences
and social sciences, humanities scholars by and large
approach scholarship as a solitary endeavor, the
exploration of a topic or idea through the materials of the
archives and theoretical frameworks of the field. By
contrast, digital and computational scholarship in the
humanities is collaborative by necessity; few humanities
scholars are able to do computational work on their own,
and most acknowledge that the most interesting and
innovative work happens in collaboration with partners
skilled in software engineering.

At the Center for Digital Humanities at Princeton, we focus
on transitioning humanities faculty from individual
scholars to co-PIs on digital scholarly projects. One of
the only Humanities RSE teams in the United States, we work
with Princeton faculty on short-term (6-12 month)
development projects, as well as provide project design
training and data development support. Our primary focus is
on projects where the humanities research questions require
innovation in software or computational methods.

In this talk, we will highlight our chartering process,
whereby we guide the expansive and often
not-operationalized research questions of our faculty
collaborators into a defined research and development plan.
These processes build on foundational theoretical work by
early digital humanists like Simon Appleford, Jennifer
Guiliano and others, and have evolved alongside the RSE
role [1]. The charters are written collaboratively, guided
by our project manager and shaped by the faculty member and
our research software engineers over the course of a month.
The process of chartering is a key part of our work in
transitioning humanities faculty from their traditional
modes of research and scholarly exploration into the space
of digital and computational research, teaching them to
understand their sources as data, transforming their ideas
into research questions that are modular and
operationalizable, and shifting their process from
individual to collaborative. Using our most recent project
charter as a case study, we will showcase the central role
that project management plays in facilitating what Jason
Boyd calls “scholarly exchange” [2, 3]. Ultimately, our
talk will show how doing software engineering work in a
humanities context poses particular challenges, but also
provides the unique opportunity for the RSE to shape the
faculty PI’s research questions and approach. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading7">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse7"
aria-expanded="false" aria-controls="collapse7">
Multilingual Research Software Translation using AI:
Breaking the Communication Barriers<br> Pengyin Shan
</button>
</h5>
</div>

<div id="collapse7" class="collapse" aria-labelledby="heading7" data-parent="#accordion">
<div class="card-body">
<p> Research software engineers can face unique challenges when
translating their tools into different human languages. The
specialized nature of scientific terminology, contextual
nuances in technical explanations, and resource limitations
often restrict valuable research applications to
single-language availability (predominantly English)
[1][2][3]. This creates a fundamental tension between
development priorities and accessibility goals that
particularly impacts non-English-speaking research
communities [4]. This talk will explore how recent advances
in AI translation technologies are transforming this
landscape, making comprehensive software translation
feasible even for resource-constrained research projects
[5].

The talk will begin by examining the challenges of research
software translation, including the precision requirements
for scientific terminology, context-dependency of interface
elements, and financial budget & workforce limitations.
Traditional approaches to these challenges required
specialized domain translators and significant ongoing
maintenance investments that were often unsustainable for
research software teams, resulting in predominantly
English-only tools that limit global scientific
participation.

The presenter will then analyze how recent developments in
large language models have specifically addressed these
translation barriers through contextual understanding,
domain adaptation capabilities, and integration with a
continuous development workflow. Then, a practical
implementation framework that balances automation with
necessary human oversight will be presented, providing
research software engineers with concrete strategies for
integrating AI translation into their development workflows.

Lastly, through a quick demonstration in video,
screenshots, or live, the presenter will showcase an
example to translate a research software interface.
Attendees will gain practical knowledge of research
software translation that they can immediately apply to
make their software more accessible to
international/multilingual scientific communities. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading8">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse8"
aria-expanded="false" aria-controls="collapse8">
Notebooks as the Published Paper, How Ready are Scientific
Communities?<br> Kenton McHenry and Christine Kirkpatrick
</button>
</h5>
</div>

<div id="collapse8" class="collapse" aria-labelledby="heading8" data-parent="#accordion">
<div class="card-body">
<p> Science today increasingly relies on software to conduct,
analyze, and share research. However, the primary artifacts
of scientific work, such as papers and PDFs, fail to
adequately capture the dynamic and interactive nature of
software-driven exploration. Over the past decade, several
initiatives have emerged to bridge this gap. One notable
example is EarthCube [1-5], which in its final three years
called for geoscience submissions in the form of
computational notebooks for its annual meeting. This
experiment not only showcased the existence of a scientific
community embracing the idea of a more interactive and
reproducible format for scientific sharing but also led to
further exploration: AGU, with support from the Sloan
Foundation, launched an effort to prototype a complete
pipeline for soliciting, reviewing, and accepting notebooks
as primary publications.

This shift parallels the broader historical transition from
physical papers to digital PDFs and XML-based publications.
However, a critical question remains: Are research
communities ready for this evolution? While geoscientists
embraced the notebook format during EarthCube's final
years, other disciplines have been more hesitant to move
away from traditional static documents. The impediments
include a range of technical gaps, lack of resources, as
well as socio technical blockers. At the same time, many
scientific communities express a desire for additional
methods of scholarship, and are motivated to take part if
others can lead the way.

To better understand the community's readiness, the NSF
CSSI DeCODER project, an initiative that continues some of
EarthCube's data and notebook-driven activities, conducted
a survey targeting scientists across various fields. This
talk will present the findings of that survey, offering
insights into the scientific community's perspectives on
notebook-driven publication and exploring potential next
steps to foster broader adoption. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading9">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse9"
aria-expanded="false" aria-controls="collapse9">
Developing a Machine Learning-Augmented Solver for the
Hydrologic Model ParFlow<br> Georgios Artavanis, Laura Condon, Andrew Bennett, and Reed
Maxwell
</button>
</h5>
</div>

<div id="collapse9" class="collapse" aria-labelledby="heading9" data-parent="#accordion">
<div class="card-body">
<p> PDEs play a critical role in modelling the dynamics of
complex processes, including financial, biological and
geophysical systems. However, iterative solvers based on
finite difference and finite volume methods, which are
often used for the numerical solution of PDE systems, are
computationally expensive. A promising new approach is to
use machine learning-augmented solvers to speed up
traditional numerical solvers. In ML-augmented solvers, a
pre-trained ML model is used to kickstart the iterative
solver at each step of the solution by providing an
improved “first guess” for the unknown quantity compared to
the state-agnostic first guess of the pure numerical
solver. This can accelerate the solver by reducing the
number of iterations that it
takes the solver to converge.

In this talk, we will present the development of a
ML-augmented solver for the hydrologic model ParFlow.
ParFlow simulates saturated and variably saturated
subsurface flow in heterogeneous porous media in three
spatial dimensions using a multigrid-preconditioned
conjugate gradient solver and a Newton-Krylov nonlinear
solver. Most of the compute time in a ParFlow simulation is
spent in the solver, hence, accelerating the solver enables
running simulations over larger geographical domains and
making hydrologic projections in real time feasible. This
work is part of a NAIRR Pilot project, which aims to create
a digital twin of the
hydrology of the Continental United States.

The structure of the talk will be as follows: We will first
describe the ParFlow iterative solver at a high level, the
ParFlow EDSL (Embedded Domain-Specific Language), and the
steps taken to develop a common ParFlow interface for
Torch-based models. This interface allows researchers to
create and train ML models in Python with PyTorch, compile
them with TorchScript and effortlessly hook them up to
ParFlow, which is written mostly in C. Within the ParFlow
solver, the ML model accepts as inputs hydrometeorological
variables that describe the current state of
ParFlow and outputs a best guess for the pressure variable
at the next timestep of the simulation. We will then
present preliminary results using trained models to
accelerate the ParFlow solver over large geographical
domains. Interestingly, the ML models used to accelerate
the ParFlow solver have been themselves trained on existing
ParFlow simulation data and real-world hydrological
observations, creating a feedback loop between solver
acceleration and model improvement. We will conclude the
talk with general considerations for integrating ML models
into physics-based solvers and an overview of the NAIRR
initiative from an RSE perspective. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading10">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse10"
aria-expanded="false" aria-controls="collapse10">
Knowledge Graphs as Infrastructure: Enabling Generative AI
Integration Across Research Software<br> Fan Li
</button>
</h5>
</div>

<div id="collapse10" class="collapse" aria-labelledby="heading10" data-parent="#accordion">
<div class="card-body">
<p> As AI tools powered by large language models (LLMs) gain
traction in research, one major challenge for RSEs is
meaningful integration: How can we connect LLMs to the
research software stack—scripts, workflows, datasets, and
documentation—to make them context-aware, trustworthy, and
useful in real scientific environments?

This talk proposes treating knowledge graphs as
infrastructure to orchestrate research software ecosystems
for generative AI integration. By representing tools,
workflows, domain concepts, and research artifacts as a
semantic layer, RSEs can unlock new capabilities:

- Enable retrieval-augmented generation (RAG) grounded in
scientific domain knowledge
- Extend AI agents with on-demand invocation of research
software components and workflow logic
- Improve documentation, reproducibility, and transparency
in AI-driven research processes

The ideas presented are informed by my 15 years of
experience in developing data and AI solutions for
industrial R&D. I will walk through the architecture of
such a system and share implementation examples. In
particular, we’ll explore a scenario where tasks are
automated by an AI agent operating on top of a knowledge
graph and chemoinformatics tools. I’ll also highlight the
collaborative role of RSEs and domain researchers in
building and sustaining these systems. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading11">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse11"
aria-expanded="false" aria-controls="collapse11">
A Reproducible and Scalable Pipeline for Processing
Administrative Health Claims Data<br> Mahima Kaur, Shreya Nalluri, James C. Kitch, Tinashe M.
Tapera, Jonathan Gilmour, Michelle Audirac, and Danielle Braun
</button>
</h5>
</div>

<div id="collapse11" class="collapse" aria-labelledby="heading11" data-parent="#accordion">
<div class="card-body">
<p> Administrative data from the Centers for Medicare and
Medicaid Services (CMS) [1] are a cornerstone of
epidemiological and health outcomes research in the United
States. These datasets support extensive analyses of
healthcare utilization, policy impacts, and disease burden
[2], covering hundreds of millions of beneficiaries.
However, the complexity, privacy protections, and
inconsistent coding across years in these datasets hinder
reproducibility and require significant preprocessing
efforts. Furthermore, the under-utilization of scalable
pipelines leads to repeated data cleaning across different
research groups, resulting in duplicated efforts and
inefficiencies.

To address these challenges, we developed a modular,
open-source, serverless, and containerized data pipeline
that streamlines the CMS Medicare data lifecycle from raw
file ingestion to analysis-ready output. The pipeline
currently focuses on two key CMS Medicare data sources: the
Master Beneficiary Summary File (MBSF), which provides
enrollment and demographic information, and the Medicare
Provider Analysis and Review (MedPAR) file, which contains
inpatient and skilled nursing facility (SNF) admissions.

The pipeline begins by processing raw Medicare data,
parsing fixed-width .dat files with .fts metadata into
columnar Parquet format [3]. In the next step,
harmonization is driven by a declarative YAML configuration
that resolves year-to-year structural inconsistencies
through field-level transformation rules. This enables
consistent handling of discrepancies in variable naming
(e.g., bene_zip vs. zip_cd), data encodings (e.g. string
vs. numeric date formats) and storage structure(e.g.,
whether monthly indicators are split across columns or
packed into strings). The harmonized datasets are then
normalized into three core datasets - beneficiaries,
enrollment, and admissions. These datasets are validated to
remove records with missing or conflicting identifiers and
resolve demographic inconsistencies such as multiple birth
dates or contradictory race codes for the same beneficiary.

The pipeline generates materialized views, which are
precomputed, query-optimized data products that integrate
enrollment, admissions, and disease-specific admissions
information. These reusable, analysis-ready datasets enable
rapid cohort construction, longitudinal follow-up, and
outcomebased analytics. Each step is implemented in a
modular, version-controlled script (e.g., via Git), with
workflow orchestration handled by Snakemake [4] (for
reproducibility and scalability), and Docker [5] (to ensure
portability across computing environments). Furthermore, we
leverage DuckDB [6] as the central execution engine in all
pipeline steps, enabling efficient in-process SQL queries
over Parquet files with support for year-wise partitioning
and batch processing, avoiding the need for a centralized
database infrastructure.

In conclusion, by enabling direct querying of materialized
datasets without repeatedly accessing raw files, the
pipeline supports efficient, large-scale, and scalable
analyses while automating key preprocessing steps and
reducing redundant data engineering. The pipeline further
promotes transparency, traceability, and reproducibility,
aligning with the FAIR (Findable, Accessible,
Interoperable, Reusable) [7] data principles, and lowers
the barrier to working with complex administrative
health data. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading12">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse12"
aria-expanded="false" aria-controls="collapse12">
Making Research Software Findable, Accessible,
Interoperable, Reusable (FAIR) with Codefair<br> Bhavesh Patel, Dorian Portillo, and Sanjay Soundarajan
</button>
</h5>
</div>

<div id="collapse12" class="collapse" aria-labelledby="heading12" data-parent="#accordion">
<div class="card-body">
<p> Making software Findable, Accessible, Interoperable, and
Reusable (FAIR) can be time-consuming and difficult,
especially since it is a continuous process throughout a
software’s lifecycle. Codefair is designed to automate the
process, letting researchers concentrate on the goals of
their software. It is developed as a free and open-source
(MIT license) platform with two components: a GitHub app
and a web app. Once the Codefair GitHub app is installed on
a software’s GitHub repository, Codefair seamlessly
integrates into the typically software development workflow
by monitoring the repository using tools like Probot,
providing feedback via a GitHub issue, allowing the user to
address them through user-friendly interfaces on the
Codefair web app, and even submitting pull requests
automatically to maintain continuous FAIR compliance. With
thorough documentation and a design focused on ease-of-use,
Codefair is accessible to all. When introduced at US-RSE’24
in an early development phase, Codefair primarily assisted
researchers in adding essential metadata elements such as
license, CITATION.cff, and codemeta.json. Since then, it
has expanded to support streamlined archival on Zenodo and
automated validation of Common Workflow Language (CWL)
files. A new web dashboard enables easy assessment and
management of FAIR compliance across your GitHub
repositories. Usage of Codefair has also increased as it is
now installed on over 400 GitHub repositories. By
alleviating the time and effort needed for FAIR compliance,
Codefair encourages biomedical researchers to embrace FAIR
and open practices. In this presentation, we will detail
our development approach, outline current features, discuss
planned features, summarize updates since US-RSE’24, and
invite the community to explore and contribute to Codefair. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading13">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse13"
aria-expanded="false" aria-controls="collapse13">
Presenting the Actionable Guidelines for FAIR Research
Software Task Force<br> Bhavesh Patel and Daniel Garijo
</button>
</h5>
</div>

<div id="collapse13" class="collapse" aria-labelledby="heading13" data-parent="#accordion">
<div class="card-body">
<p> The Research Software Alliance (ReSA) has established a
Task Force dedicated to translating the FAIR Principles for
Research Software (FAIR4RS Principles) into practical,
actionable guidelines. Existing field-specific actionable
guidelines, such as the FAIR Biomedical Research Software
(FAIR-BioRS) guidelines, lack cross-discipline community
input. The Actionable Guidelines for FAIR Research Software
Task Force, formed in December 2024, brings together a
diverse team of researchers and research software
developers to address this gap. The Task Force began by
analyzing the FAIR4RS Principles, where it identified six
key requirement categories: Identifiers, Metadata for
software publication and discovery, Standards for
inputs/outputs, Qualified references, Metadata for software
reuse, and License. To address these requirements, six
sub-groups are conducting literature reviews and community
outreach to define actionable practices for each category.
Some of the challenges include identifying suitable
identifiers, archival repositories, metadata standards, and
best practices across research domains. This presentation
provides an overview of the Task Force, presents its
current progress, and outlines opportunities for community
involvement. Given the progressive adoption of the FAIR4RS
Principles, including by funders, we expect this
presentation will provide attendees at USRSE’25 with an
understanding of the FAIR4RS Principles and how they can
make their software FAIR through actionable,
easy-to-follow, and easy-to-implement guidelines being
established by our Task Force. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading14">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse14"
aria-expanded="false" aria-controls="collapse14">
Three Foundational Ideas That Shaped Software Engineering<br> Abhishek Dutta
</button>
</h5>
</div>

<div id="collapse14" class="collapse" aria-labelledby="heading14" data-parent="#accordion">
<div class="card-body">
<p> Alfred North Whitehead once remarked, "Civilization
advances by extending the number of important operations
which we can perform without thinking about them." This
talk explores three foundational research papers in
software engineering – each more than half a century old –
that have shaped how we design, reason about, and
collaborate on large-scale software systems. These works
have enabled programmers to operate at higher levels of
abstraction, leading to scalable and intelligible software
development.

The first paper, by D. L. Parnas (1972), introduced the
principle of "information hiding" for decomposing a large
scale software project into modules which have an interface
that reveal as little as possible about its inner workings.
This approach allows for independent evolution of
components, improving both maintainability and clarity.
Inspired by this idea, B. Liskov and S. Zilles (1974) later
formalized the concept of Abstract Data Types (ADTs),
enabling programmers to reason about data structures
through well-defined operations rather than through a long
sequence of low level machine instructions to fetch, update
and store smaller units of a data structure. Together,
these ideas laid the groundwork for building complex
software systems using composable and comprehensible
modules.

The second group of papers liberated programmers from the
need to consume "spaghetti" code generated by the need to
sprinkle "go to" statements in a program code to realise
desirable control flow. Böhm and Jacopini (1966)
mathematically proved that any computable function can be
implemented using just three control structures: sequence,
selection (e.g. if … else), and repetition (e.g. for loop).
This formal result supported E. W. Dijkstra’s (1968)
influential call to abolish "go to statement" from
"everything except … plain machine code". Although
high-level constructs like loops and conditionals are still
compiled to low-level jumps (e.g., JMP), these papers
empowered developers to operate at a higher level of
abstraction where control flow of a computer program was
more intelligible.

The third set of papers were intended to address the
challenge of modelling and understanding naturally
occurring complex processes. "How complex or simple a
structure is depends critically upon the way in which we
describe it." wrote H. A. Simon (1962) to make a case for
finding the "right representation" to describe complex
systems. Simon’s key insight was to view a complex system
as a hierarchical structure composed of subsystems (or
modules) which interact more internally than externally.
Subsystems at higher levels were derived from subsystems
operating at lower levels of the hierarchy. To model
real-world processes, Dahl and Nygaard (1967) pioneered
object-oriented modeling by representing processes as a set
of interacting objects – each encapsulating state and
behavior—and organizing them hierarchically through
inheritance. These insights emphasized modularity,
hierarchy, and abstraction as essential tools for managing
complexity and continue to underpin modern programming
paradigms. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading15">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse15"
aria-expanded="false" aria-controls="collapse15">
The Hubverse: Streamlining Collaborative Infectious Disease
Modeling for Public Health Impact<br> Anna Krystalli
</button>
</h5>
</div>

<div id="collapse15" class="collapse" aria-labelledby="heading15" data-parent="#accordion">
<div class="card-body">
<p> Predictive models have become an essential tool for public
health decision-making during infectious disease outbreaks.
Yet the rapid proliferation of models, especially during
the COVID-19 pandemic, has created a fragmented landscape
marked by inconsistent metrics, overlapping or conflicting
forecasts, and limited comparability. This has posed
serious challenges for decision-makers trying to identify
reliable, policy-relevant insights.

Collaborative modeling hubs offer a promising solution by
coordinating model submissions, promoting transparency, and
facilitating ensemble modeling, where aggregated model
outputs usually outperform individual ones. Hubs also
improve communication between modeling teams and
stakeholders by aligning outputs with public health
priorities.

The hubverse (https://hubverse.io/) is a modular,
open-source software ecosystem designed to support the
setup and operation of these hubs. It introduces a set of
data standards for probabilistic model output data, as well
as utilities for setting up and administering a hub,
validation and ensembling tools, visualization templates,
and mechanisms for model evaluation and public-facing
communication. The hubverse defines five primary user
roles: hub administrators, modelers, analysts,
stakeholders, and developers, and supports each with
tailored tools.

Importantly, the hubverse is built primarily on open-source
software (R, Python, JavaScript, Arrow) and freely
available platforms like GitHub, making it accessible even
to research groups with limited resources. While hub
administration remains the most technical aspect, the
ecosystem is designed to reduce barriers across all roles.
Automation, templating, and interactive interfaces lower
the technical burden and make engaging meaningfully with
hub products easier for a wider range of users, including
public health stakeholders.

This talk introduces the hubverse through real-world
examples, including its recent adoption by the CDC’s
FluSight influenza forecasting hub. We will highlight how
this infrastructure is helping standardize infectious
disease modeling efforts and support evidence-based
decision-making at all levels of public health response. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading16">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse16"
aria-expanded="false" aria-controls="collapse16">
The True Gravity of Research Software<br> Jonathan Starr
</button>
</h5>
</div>

<div id="collapse16" class="collapse" aria-labelledby="heading16" data-parent="#accordion">
<div class="card-body">
<p> Open source research software is foundational to modern
scientific discovery, forming a complex ecosystem of tools,
publications, researchers, and institutions. Understanding
the intricate connections within this ecosystem is vital
for demonstrating software impact, fostering collaboration,
and supporting the RSE community. While traditional metrics
and explicit links (e.g., DOIs) provide a starting point, a
significant portion of software's influence, particularly
through informal mentions in academic literature, remains
challenging to systematically capture and analyze. This
"dark matter" of software usage obscures the true reach of
research software, making it difficult for RSEs to
demonstrate value, for institutions to assess their
software output, and for the community to understand the
intricate dependencies within the scientific landscape.

The challenge is twofold: first, to effectively map the
known, explicit relationships within the research software
landscape; and second, to develop methods for uncovering
and integrating the more elusive, informal acknowledgements
of software use. Addressing the latter requires
community-driven efforts to create robust techniques for
identifying software use in research. Success in this area
would significantly enrich our understanding of software's
true reach.

This talk invites the community to participate in the
significant development of the Map of Open Source Science
(MOSS) project, a knowledge graph designed to provide a
comprehensive and dynamic view of the open source science
ecosystem. MOSS integrates data from sources like GitHub,
OpenAlex, Ecosyste.ms, and others to:

Map explicit connections through repository metadata,
software-publication links via DOIs, contributor networks,
institutional affiliations, and inference.
Serve as a platform to incorporate and analyze inferred
linkages, such as those derived from community efforts to
extract informal software mentions from publications.
Enable complex queries to explore how software impact
propagates, identify key individuals or institutions, and
uncover collaborative patterns across both explicit and
inferred connections.

We will demonstrate how MOSS surfaces insights from
existing linked data, and illustrate its potential to
provide an even richer picture as new methods for
uncovering informal software use are developed and their
outputs integrated. We will also demonstrate the open
catalogue of impact analysis algorithms growing around the
MOSS system.

Our goal is to show how RSEs and institutions can leverage
MOSS to articulate their value, assess their full software
footprint, and access a rich dataset for scientometric
studies and for understanding the health and sustainability
of the research software ecosystem both within and beyond
their immediate environment. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading17">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse17"
aria-expanded="false" aria-controls="collapse17">
Beyond Specialization: Navigating the Post-Hadoop Database
World<br>Chris Stephens, Chris Pond, Mikolaj Kowalik, and Yash Wasnik
</button>
</h5>
</div>

<div id="collapse17" class="collapse" aria-labelledby="heading17" data-parent="#accordion">
<div class="card-body">
<p> The emergence of the Hadoop ecosystem in the early 2010's
established data engineering as a distinct career and put
"big data" front and center in our industry. While this
trend rightfully elevated data's importance, it led many
organizations down a path of implementing complex
distributed systems for unclear purposes—often with
disappointing ROI given their significant operational costs.

Today's database landscape has largely evolved in reaction
to those excesses. Many of these complex systems were
eventually adopted by cloud providers and offered as
managed services, shifting the operational burden from
engineering teams to vendors. However, this evolution
created a new problem: an explosion of specialized
databases that don't always play well together. Early
versions of MongoDB exemplify this trend—while they
prioritized developer experience through flexible schemas,
many teams discovered that the initial lack of ACID
guarantees and relational constraints led to data integrity
challenges as applications scaled. MongoDB has since
addressed many of these limitations, but the pattern of
specialized systems creating unexpected tradeoffs remains
common. Rather than adopting dedicated systems for every
use case, savvy engineering teams are rediscovering the
power of Postgres and its rich extension ecosystem. With
extensions like TimescaleDB for time-series data, PostGIS
for geospatial applications, and pg_vector for embeddings
storage, Postgres has absorbed many specialized
capabilities that previously required separate systems.

While Postgres and its extensions cover most database
needs, a few noteworthy tools have emerged that deserve
attention—chief among them, DuckDB. This in-process
analytical engine lets you query data directly where it
sits, whether in files or remote sources, without
infrastructure overhead. Built on decades of academic
database research, DuckDB focuses on simplicity, usability
and performance, enabling users to work with data both
locally and at scale. From exploratory analysis to data
transformation pipelines, learning DuckDB represents an
exceptional investment for engineers working on
data-centric projects. We'll explore key features and use
cases that explain its meteoric rise in popularity.

Looking forward, an emerging set of open standards is
enabling data lakehouses and a new generation of
specialized databases built as composable systems that work
well together. It's still early days, but these
developments are worth tracking as they may revolutionize
the field yet again.

This talk will equip software engineers with practical
frameworks for evaluating database technologies without
getting caught in cycles of unnecessary specialization.
Attendees will leave understanding how to identify the
highest-leverage database technologies for their specific
contexts, when to stick with proven solutions like
Postgres, and how to prepare for the composable data
systems of the future. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading18">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse18"
aria-expanded="false" aria-controls="collapse18">
HPC Carpentry and Community at NIST<br> Andrew Reid
</button>
</h5>
</div>

<div id="collapse18" class="collapse" aria-labelledby="heading18" data-parent="#accordion">
<div class="card-body">
<p> There is a great deal of overlap in interests among
computational researchers interested in Research Software
Engineering, technical education, and high-performance
computing, all of which feature a certain amount of
boundary-crossing between computational research activities
as they are narrowly understood (in terms of producing
peer-reviewed papers), and the broader understanding that
includes coding and code management, data management,
education, and operations activities. In this presentation,
some beneficial results of this overlap will be discussed
through the lens of the HPC Carpentry educational project.

HPC Carpentry[1] began several years ago as an effort to
streamline the up-skilling process for new users of
high-performance computing systems. The project has had
some turnover in its core community over the past several
years, and the current iteration is an international group,
including steering committee participation from researchers
at NIST, where the broader Carpentries effort is widely
admired and used.

Over the past couple of years, a group of researchers at
the National Institute of Standards and Technology had some
success in advocating for new high-performance computing
resources, including a new support model (including
research software engineering support), and a major focus
on building a community of users.

HPC Carpentry workshops were very successful in introducing
novice users to the computational resource, but also led to
very wide-ranging discussions on strategies for efficient
use that were very broad in scope, and helped the
institution to identify opportunities for additional
support on many fronts, including research software
engineering.

An important higher-level outcome was that, in the same way
that the RSE activity challenges the legacy categories of
investigator and support service, it also be useful to
challenge boundaries between categories of support
services, focusing instead on a dialog with users and user
needs. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading19">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse19"
aria-expanded="false" aria-controls="collapse19">
Realizing a Project-Based Resource API at the Oak Ridge
Leadership Computing Facility<br> Arthur Ruckman, Paul Bryant, Tyler Skluzacek, Suzanne
Prentice, Daniel Rosendo, Clara Nguyễn, and Eben Fluto
</button>
</h5>
</div>

<div id="collapse19" class="collapse" aria-labelledby="heading19" data-parent="#accordion">
<div class="card-body">
<p> The demand for experimental automation is rapidly
increasing across research laboratories, where seamless
integration between instruments, data, and computing is
becoming essential. Accelerator research facilities produce
unprecedented volumes of data, often requiring
near-real-time HPC for experiment steering or data
reduction. Fabrication research facilities are seeking ways
to integrate their experiments with HPC for inline process
optimization and material characterization. Emerging
self-driven autonomous laboratories require high-quality
interfaces to enable instrument integration with HPC and
data resources. And realizing the eventual goal of truly
AI-agent-driven experimentation will demand even broader
access to scientific instruments and data repositories to
enable model training and inference pipelines.

The longstanding paradigm of monolithic, manually submitted
processing jobs on static, aggregated blocks of data are
incompatible with these experimental patterns. Instead,
these workflows require highly dynamic and programmatic
access to the compute and data resources of modern HPC
facilities, coupled with infrastructure like data services
and message queues to connect them.

However, moving beyond legacy HPC interfaces—login nodes,
batch jobs, and synchronous file transfers—to support these
new capabilities introduces significant technical and
security challenges. Programmatic interfaces drastically
expand the attack surface for critical HPC infrastructure,
necessitating robust, multi-layered security models,
comprehensive usage tracking, and resource visibility
mechanisms to ensure facility integrity, user trust, and
researcher awareness of active tasks.

To meet these evolving demands without compromising
security or restricting API extensibility, the Oak Ridge
Leadership Computing Facility (OLCF) is developing a modern
resource API within a novel service mesh architecture,
built using Istio [1]. The Secure Scientific Service Mesh
(S3M) grants users project-scoped tokens with highly
specific permissions, and enforces fine-grained
authentication, authorization, and policy compliance by
validating every API interaction for identity, project
affiliation, and adherence to project resource allocations.
Istio offers powerful features for dynamically controlling
routing through the system via modular plugins, enabling
introspection and manipulation of all requests and the
instantiation of transient routes for data streaming. We
hope these capabilities will enable us to offer truly
automated access to OLCF resources, not just to researchers
inside the Oak Ridge National Laboratory, but also those in
other facilities.

Our talk would focus on our novel modular, mesh-based
approach for building a modern scientific resource API; the
obstacles faced by a system of this nature; and our
authorization and authentication solutions for meeting
those requirements without compromising API functionality
or modularity. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading20">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse20"
aria-expanded="false" aria-controls="collapse20">
dbverse: scalable scientific analytics with embedded
analytical databases<br> Edward Ruiz, Jiaji Chen, and Ruben Dries
</button>
</h5>
</div>

<div id="collapse20" class="collapse" aria-labelledby="heading20" data-parent="#accordion">
<div class="card-body">
<p> Larger-than-memory data are being generated at increasing
scale and frequency in many scientific fields today. This
trend is especially evident in the life sciences, where
there is also a plethora of file formats that are
fragmented across disparate programming languages and
libraries. The growing size and heterogeneity of such data
pose a major bottleneck to scientific progress. As
high-throughput sequencing and imaging technologies
continue to advance and even outpace Moore’s law, it is
crucial that more scalable, user-friendly, affordable, and
interoperable computational methods are developed. To
tackle this major challenge, we developed dbverse, an
ecosystem of composable packages that are built on recent
advances in embedded OLAP databases and a novel
object–relational mapping framework. Dbverse enables
scalable analysis of three general scientific data sources,
including sparse and dense matrices (dbMatrix), spatial
geometries (dbSpatial), and genomic sequence files
(dbSequence). In this talk, we discuss the architecture and
methods of dbverse libraries, showcase a real-world
application to the emerging spatial omics field through the
GiottoDB R package, and discuss our roadmap for future
development. In addition, we report extensive benchmarks
comparing how the runtime and memory usage of dbverse
methods outperform those from established in-memory and
on-disk methods. Dbverse adopts FAIR principles, is open
source, and aims to democratize larger-than-memory
scientific data analysis with databases. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading21">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse21"
aria-expanded="false" aria-controls="collapse21">
LLMaven: Large Language Model based Agentic Verification
and Exploration of Natural Inquiry<br> Cordero Core, Vani Mandava, Andrew Connolly, David Beck,
Don Setiawan, Nicolette Burggraf, Anant Mittal, Anshul Tambay, and Anuj Sinha
</button>
</h5>
</div>

<div id="collapse21" class="collapse" aria-labelledby="heading21" data-parent="#accordion">
<div class="card-body">
<p> Research teams across domains are eager to integrate large
language models (LLMs) into their workflows—but
off-the-shelf tools often fall short when it comes to
research-specific use cases, reproducibility and
accessibility. At the Scientific Software Engineering
Center (SSEC), we are building LLMaven, an open source
platform to bridge that gap: an extensible multi-agent AI
framework designed for scientific researchers who need more
than a chatbot.
 
LLMaven brings together containerized cloud-native tools,
standardized agent protocols, and plug-and-play backends to
form a secure, reproducible, and flexible system. At its
core, LLMaven utilizes the Agent-to-Agent Protocol (A2A)
and Model Context Protocol (MCP) to support structured
communication between agents and external resources. It
allows agents to reason collaboratively and dynamically
delegate tasks across domains—whether querying temporal
knowledge graphs, managing GitHub repositories, or
coordinating custom pipelines.
Built on Kubernetes with Helm for scalable deployment, the
system incorporates tools like OpenWebUI for secure
interactions, Grafana and Logfire for observability, and a
hybrid data backend (Neo4j, Postgres, MinIO). Our
architecture supports switching between local and remote
models utilizing containerized inference engines and
API-based backends without changing the application
logic—making it future-proof and vendor-flexible. With
support via an NSF and OSTP’s National AI Research Resource
award, LLMaven has peer reviewed validation and access to
compute resources.

In this talk, we’ll walk through the architectural
decisions, lessons learned from our user-centered MVP
development, and a real-world use case featuring data from
the Rubin Observatory project. We’ll also discuss our
vision for democratizing AI tooling in research and how the
LLMaven model could enable cross-domain collaboration at
scale.
 
LLMaven isn’t just a platform—it’s an evolving conversation
between code, practice, and people. And that makes it a
story worth sharing. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading22">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse22"
aria-expanded="false" aria-controls="collapse22">
Principles for developing a personal project management
workflow as a Research Software Engineer in an autonomous
or highly independent context<br> Henry Burgess
</button>
</h5>
</div>

<div id="collapse22" class="collapse" aria-labelledby="heading22" data-parent="#accordion">
<div class="card-body">
<p> Research Software Engineers (RSEs) often work in autonomous
or highly independent contexts and must develop effective
personal project management (PPM) workflows to deliver
projects successfully. It can be challenging to manage
multiple projects, not due to a lack of project management
platforms, but because these platforms rarely align with
individual working styles. Having utilized and evaluated
multiple platforms, we aim to develop a set of principles
for taking an RSE-centric approach when developing a PPM
workflow. Beginning with a set of existing projects,
individual tasks were used to populate and test three
popular PPM tools: Notion, Jira, and Trello. These tools
were used daily for at least one month each and evaluated
on criteria including usability, flexibility, and overall
utilization. Based on these evaluations, a set of
principles were created to summarize the rationale used
when discerning between personal preferences and features
offered by these platforms. These principles can be
summarized as: “Your workflow should work for you” (a PPM
workflow adapts to the RSE’s way of work); “Complexity is
the enemy of effective work” (complicated PPM workflows can
inhibit productivity); “Don’t be afraid to copy industry”
(platforms widely used in industry are not perfect, however
they can provide tested structure); and “Take advantage of
all independence afforded to you” (independence provides
the opportunity to evaluate different platforms).  These
principles return the focus of a PPM workflow to the RSE
and their way of working, rather than the features of a
platform being sold. RSEs working in autonomous or highly
independent contexts will benefit from an RSE-centric
workflow, and taking time to develop a PPM workflow with
these principles in mind will continue to nurture technical
versatility and professional development. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading23">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse23"
aria-expanded="false" aria-controls="collapse23">
Understanding Research Software Engineer (RSE) Roles and
Recruiting through the US-RSE Job Board<br> Christina Maimone and Emilio Lehoucq
</button>
</h5>
</div>

<div id="collapse23" class="collapse" aria-labelledby="heading23" data-parent="#accordion">
<div class="card-body">
<p> A job board has been part of the US Research Software
Association (US-RSE) website since 2019, early in the
organization’s history. Since then, over 660 research
software engineer (RSE) and RSE-adjacent jobs have been
posted from over 200 different organizations. We’ve
collected the text of the full job posting from the
original sources for over 260 positions (40%), including
75% of postings since 2023 and 96% of postings since 2024.

This collection of job postings provides a unique
opportunity to examine the characteristics of RSE positions
in the US, as well as better understand challenges around
the hiring and retention of RSEs, an issue frequently noted
for the RSE field in the US (Van Tuyl 2023). In this talk,
we share some high-level trends from looking at the limited
information (job title, location/organization, and posting
date) available from all job board entries, as well as more
detailed analysis for the positions for which we have the
full job posting.

Looking at entries on the job board, about a quarter list
Research Software Engineer as the job’s title, but
research, software, and engineer are the top words
appearing in job titles. Most positions do not include an
explicit level indicator, such as lead or senior, but when
one is included, senior is most common. With the full
postings, we examine how RSE positions span the technical
and research domains, while also being more than the union
of these two skillsets (Cosden, McHenry, and Katz 2023;
Goth et al. 2024; Cohen et al. 2018; Society of Research
Software Engineering 2025). Following Goth et al. 2024, we
look at skills referenced in the job postings in three main
categories: technical skills, research skills, and
communication skills. We also track additional skills, such
as management and supervisory experience.

To help understand the RSE job market, we extract
information about education and experience requirements for
positions. We also examine structural characteristics of
the positions shared in the postings, such as whether the
position allows remote work, salary information, and
funding source and duration for academic positions.

This collection of RSE job postings can help the US RSE
community develop guidance for those looking to enter the
field, improve recruitment and hiring practices, and
understand both the commonalities and variation across RSE
positions. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading24">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse24"
aria-expanded="false" aria-controls="collapse24">
Building RSE Capacity with the Experiential DataSquad Model<br> Paula Lackie and Elliot Pickens
</button>
</h5>
</div>

<div id="collapse24" class="collapse" aria-labelledby="heading24" data-parent="#accordion">
<div class="card-body">
<p> The rise of AI tools, while automating entry-level
programming, creates a paradox: it threatens the
development of future computer scientists by potentially
truncating foundational learning experiences. This
narrowing of the skilled programmer pipeline occurs even as
demand for innovative research software grows. Since
practical experience is crucial yet often lacking in
traditional academic programs, this proposal explores the
DataSquad Model as a possible solution.
The DataSquad model effectively bridges the gap between
theoretical academic curricula and industry demands through
three key components. First, its robust peer mentoring
system creates a sustainable knowledge transfer ecosystem.
Second, students develop versatile skills across diverse
technical and collaborative roles, preparing them for
multifaceted professional environments. Finally, the
model's deliberate commitment to diversity, equity, and
inclusion ensures both broader participation and the
development of solutions that address varied user needs and
perspectives.
The DataSquad model is a unique approach to experiential
learning that employs students in real-world,
data-intensive projects. Students work in teams, taking on
roles such as project management, technical writing,
software design, data wrangling, and data analysis. A key
feature of the model is its emphasis on mentorship, where
more experienced students guide and support those with less
experience, fostering a collaborative learning environment.
This structure not only develops technical skills but also
cultivates essential "people skills" such as communication,
teamwork, appropriate documentation, and overall project
management.
Furthermore, the DataSquad model demonstrates a strong
commitment to DEI. The program actively recruits and
supports students from historically underrepresented
backgrounds, including students of color, gender-diverse
individuals, international students, and first-generation
Americans, providing targeted mentorship and advancement
opportunities often absent in traditional academic
environments.
Although it was originally designed to address data science
problems, the DataSquad model has successfully evolved to
support the development of specialized research software
solutions, demonstrating its adaptability and broader
applicability across computational domains. While the
longest running DataSquad is at Carleton College,
additional institutions, including UCLA and the University
of Toronto, have added or plan to add a DataSquad to their
institution. (UCLA
https://uclalibrary-stage.library.ucla.edu/about/programs/ucla-library-datasquad,
U Toronto, UMN).

In this talk we will present the model, the multiple ways
it can be made sustainable, discuss the ways in which
additional DataSquad collaborations have been successful or
have modified the model for their need, and how the
experience helped to propel alumni into higher levels of
work after college.
The DataSquad model may provide a compelling blueprint for
RSE training programs seeking to bridge the gap between
academia and practice, cultivate essential skills, and
promote DEI. By prioritizing practical experience,
mentorship, and inclusive practices, this approach can
effectively address the growing demand for qualified RSEs
while building a more diverse and collaborative research
software engineering community.

Gemini was used to tighten this proposal. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading25">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse25"
aria-expanded="false" aria-controls="collapse25">
From Hot Dogs to Human-Centered Design: Empathy in Software
Development<br> Lisa Gatzke and Jessica Saw
</button>
</h5>
</div>

<div id="collapse25" class="collapse" aria-labelledby="heading25" data-parent="#accordion">
<div class="card-body">
<p> This presentation introduces the Visual Analytics and UIX
(User Interface and Experience) team at the National Center
for Supercomputing Applications (NCSA). Since expanding in
2021, our team has developed over 40+ academic research
applications, integrating design thinking and software
engineering to solve complex scientific problems.
Positioned at the intersection of data, design, and user
needs, we focus on creating software interfaces that are
not only functional but empathetic and user-centered.

In this talk, we will describe how the concept of
“unreasonable hospitality,” borrowed from the restaurant
service industry1, can be applied to software development
practice. We will (1) define the concept as it applies to
the service industry, (2) describe how it is applied to
software development practices, and (3) provide specific
recommendations for how to integrate these practices into
your team’s software development process.

Unreasonable hospitality, originally described by Will
Guidara, former co-owner of the fine dining establishment
Eleven Madison Park, encapsulates the practice of making
people feel seen and welcome, giving them a sense of
belonging1. Drawing from a real-life story of extraordinary
service involving a simple hot dog at a high-end New York
restaurant, we reflect on how noticing small details and
anticipating needs can elevate an experience. The approach
involves careful observation, recognizing what is uniquely
important to guests, and designing a direct response to
address guests needs and, just as importantly, wants.

What if, in our software development practices, we applied
a parallel approach—one that goes beyond functional
adequacy and task completion to prioritize the overall user
experience. We distinguish between functional requirements
(needs) and experiential enhancements (wants), arguing that
in the context of software (even research software!), the
latter are not optional but essential. Given that we now
spend a significant portion of our lives interacting with
software, these digital environments must strive to become
more humane.

Moreover, just as Guidara proposes that lessons from
hospitality are essential for fostering a positive work
culture regardless of industry domain, we advocate for
bringing principles of hospitality into the heart of
software development teams. A hospitality-first culture
fosters cross-disciplinary collaboration, mutual respect,
and a deeper sense of shared purpose. It demonstrates that
empathy is not limited to user-facing design—it can and
should be woven into the fabric of internal workflows,
shaping how teams communicate, collaborate, and support one
another.

In summary, service pertains to the creation of
functionally reliable systems, whereas hospitality
encompasses the design of user experiences that are
intuitive, inclusive, and emotionally satisfying. We argue
that in our work, wants—such as clear guidance, accessible
design, and consistent feedback—are actually needs,
essential to building trust and usability. We advocate for
embedding empathy at every stage of design and development,
emphasizing collaboration, communication, and mutual
respect between designers and developers. Through
thoughtful handoffs, shared language, and a culture of
hospitality-first teamwork, we aim to build software that
not only functions well but also makes users feel seen,
supported, and empowered. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading26">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse26"
aria-expanded="false" aria-controls="collapse26">
Accessing your networks: Adapting interpersonal connections
for robust software development and sustainability<br> John Parent
</button>
</h5>
</div>

<div id="collapse26" class="collapse" aria-labelledby="heading26" data-parent="#accordion">
<div class="card-body">
<p> As RSEs, our focus is often on the technical aspects of our
work that move us forward, looking to create new software,
complete research, or both, frequently collaborating within
focused teams centralized around specific goals,
occasionally sharing with a broader group. However,
developing research software is rarely so localized, we
often need to use the code of others, and others need to
use the code we produce. These interconnected networks of
software relationships can often go overlooked.

Inspired by, and extending the talk “Leveraging Liaisons In
Your Network For Software Sustainability” given at HPSF
this year, this talk will explore the human side of the
open source and research software development ecosystem. We
will focus on how the connections to those around us can
form a rich network of developers that can facilitate the
development of stronger, more sustainable software, and how
you can discover, build, and engage with the networks
around you.

Using a series of real world case studies centered around
developers working on scientific, research, and tooling
software exploring, growing, and leveraging their
relationships to establish networks of developers we will
explore how these connections allowed these developers to
produce, improve, and make their software more sustainable.

This talk will provide attendees with an indepth
exploration of these networks, how they were established,
their outcomes, and finally, what can be done in day to day
development to discover, foster, and engage their own
networks. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading28">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse28"
aria-expanded="false" aria-controls="collapse28">
Design Thinking for Implementation: Leveraging Design
Systems for Sustainable and Reproducible Research Software<br> Leigh Fu, Emma Grisanzio, and Jackson Vaughan
</button>
</h5>
</div>

<div id="collapse28" class="collapse" aria-labelledby="heading28" data-parent="#accordion">
<div class="card-body">
<p> Scientific research values reproducibility, transparency,
and collaboration—principles that should extend to the
software that supports it. Yet research scientific software
is often developed without systematic design approaches or
dedicated UX expertise, leading to tools that may be
functional but hard to use, scale, or sustain.
At the National Center for Supercomputing Applications
(NCSA), we’ve seen how intentional design practices can
make a meaningful difference in developing research
software. We value design thinking and emphasize that UX
design is not merely aesthetic or post hoc, but a critical
part of implementation that shapes how users interact with
data, models, and tools. Our goal is to build scientific
software that is more accessible, sustainable, and
supportive of the reproducibility of both user workflows
and development processes, and choosing the right design
system as a foundation is essential to that process.
A well-chosen and well-maintained design system enables
faster collaboration, clearer communication, and enhances
user experience through more consistent and usable
interfaces. In this talk, we introduce how design systems
and component libraries—when thoughtfully selected and
adapted—can bridge the gap between design and development.
We’ll share insights from our work supporting
interdisciplinary teams at NCSA, where software must adapt
to long project lifecycles, domain-specific needs, and
diverse user expertise. We’ll present a practical framework
for evaluating and customizing existing design systems in
both design (e.g. Figma) and development (e.g. React/Vue
libraries) contexts, helping teams make informed decisions
based on their goals, user needs, and capacity. We’ll also
highlight how early design choices influence not just
usability, but reproducibility, maintainability, and
cross-team collaboration over time.
By integrating design thinking into implementation
workflows, research software teams can build more
intuitive, trustworthy, and enduring tools—software that,
like good science, is built to be tested, shared, and built
upon. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading29">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse29"
aria-expanded="false" aria-controls="collapse29">
Program and Technical Management on a Product-Driven
Research Project<br> Rob Kooper and Chris Pond
</button>
</h5>
</div>

<div id="collapse29" class="collapse" aria-labelledby="heading29" data-parent="#accordion">
<div class="card-body">
<p> Managing a research project with a strong product
development focus introduces a unique blend of challenges
and opportunities—particularly when the project spans
institutions, disciplines, and sectors. In this talk, we
share lessons learned and effective strategies from our
experience managing a large-scale, multi-institutional
research effort with production, research, and
commercialization objectives.

Our project is led by a major research university and
involves collaboration across multiple departments, a
federal agency, a leading clinical and research
institution, and commercial partners. This structure
introduces complex interdependencies, competing timelines,
and varying institutional cultures and priorities.

We will explore how we navigate and balance:

* Timelines and Dependencies: Given both the research
nature of the project and the product nature, how do we
balance the dichotomy of research exploration versus
product deliverables?

* Cross-institutional Collaboration: Building trust and a
shared vision among partners with differing missions, from
academic inquiry to regulatory compliance to market
readiness. Academic researchers often want to publish their
work quickly, while industry will want to keep ideas closed
until patents or other protections are in place. This is
especially noticeable in the academy, which has a
publish-or-perish mindset.

* Leadership and Management Layers: Clarifying roles and
maintaining alignment across product owners, principal
investigators, project managers, and engineering leads,
while ensuring transparent decision-making and
communication.

* Production vs. Research Tensions: Ensuring software and
systems meet real-world reliability and usability
standards, while supporting exploratory research and
iteration. With academia looking at publications, code is
sometimes rushed and not fully production-ready. Which team
hardens the system?

* Commercialization Pathways: Integrating commercial
perspectives early in the research lifecycle and managing
intellectual property, regulatory, and operational
constraints. This is critical to be done early in the
project to prevent anyone feeling left out, or feeling like
their ideas are stolen.

We will share tools, processes, and communication
strategies that have helped us manage this complexity,
including structured program management frameworks,
collaborative roadmapping practices, and lightweight but
effective governance models. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading30">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse30"
aria-expanded="false" aria-controls="collapse30">
Technical Debt and Code Migration<br> John Holland
</button>
</h5>
</div>

<div id="collapse30" class="collapse" aria-labelledby="heading30" data-parent="#accordion">
<div class="card-body">
<p> RSEs often have to deal with code which wasn’t originally
designed with testing, maintenance or performance in mind,
or was written in a language or a style which is now
considered outdated, obsolete or insecure. This is a
problem for RSEs writing and maintaining software for
long-lived research programs, who may be slowed by this
technical debt. A common response is to start a project to
rewrite the code in another programming language or an
updated framework, and in parallel to make functional
improvements. Anecdotally, this kind of project is at risk
of delays and cost-overruns.
In some fields, like web programming, the time for a
framework to appear, reach its zenith of  popularity, and
then become uninteresting and obsolete, might be a handful
of years. In others, code which has been in use for decades
continues to be used.
In this talk I’ll discuss some of the lessons our group
learned during upgrade projects, and ask what we might be
able to learn from long-lived code.
First we’ll look at a project to migrate an image
processing pipeline from MATLAB to Julia and make it
HPC-ready. We’ll focus on the availability of ready-to-use
image processing functions, the costs of reimplementation,
and the characteristics which help a library to endure.
Then we’ll look at how our group has standardized its web
development stack, and what we learned about React,
Tailwind, Typescript, Vite and Next.js. We’ll also look at
how changes in Google Firebase hosting, which were meant to
make developers’ lives easier, made our code review process
much less intuitive, and how that was resolved. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading31">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse31"
aria-expanded="false" aria-controls="collapse31">
Beyond Copilot: RSE Team Lessons Learned in AI-First
Development<br> Caleb Reinking and Kristina Radivojevic
</button>
</h5>
</div>

<div id="collapse31" class="collapse" aria-labelledby="heading31" data-parent="#accordion">
<div class="card-body">
<p> The RSE team at the University of Notre Dame’s Center for
Research Computing (CRC) has incorporated broad use of
coding assistant technology in the form of GitHub Copilot
inside of Visual Studio Code since its launch. Like many in
the software development industry [1], we found Copilot’s
capabilities to provide immense value. In the past year,
there has been an evolution of coding assistants in the
form of Large Language Model (LLM) based coding tools and
an AI-first coding experience. At its most extreme, “vibe
coding” emerged as a way of conversing with your IDE to
generate entire products without writing a single line of
code yourself [2] [3]. Recently, Integrated Development
Environments (IDEs) have emerged that utilize LLMs for code
completion and full “vibe coding” functionality. Each of
these products, along with standalone LLMs that excel in
software engineering and reasoning, promises great gains in
software development efficiency by showing short-form demo
projects, but it is unclear whether they yield
organizational or long-term value for a team without first
hand experience.

To gain the first hand experience required to understand
contextual fit and value of AI-first coding methods at the
CRC, we ran a structured pilot test of the Cursor IDE [4]
with a cross-functional cohort of the Notre Dame CRC. The
pilot group was open to anyone within the department and
required that participants commit to testing the IDE as
their primary development environment for three months. The
pilot group consisted of 13 different members of the
Center, including 7 RSEs of various seniority. The other 6
participants ranged from Graduate Student to HPC Engineers
and non-technical staff. In addition to using Cursor as
their main development environment, the pilot cohort met
fortnightly to form a community of practice and knowledge
sharing within the Center. The diversity of software
development experience, level of difficulty of the
technical assignments, and languages and frameworks
enhanced the pilot group’s range of assessment of Cursor’s
features in comparison to the existing Visual Studio Code /
Copilot norms.

At the conclusion of the test, each participant completed a
survey that captured quantitative and qualitative
evaluations of their Cursor experience. The responses of
this group were overwhelmingly positive about their
experience. All technical contributors responded that
Cursor added at least 50% efficiency gains to their coding
workflows, with several reporting 100% efficiency gains.
However, despite the reported gains, adoption
recommendations for our broader team were mixed within the
group. The survey identified aspects of AI-first coding
that are both radically helpful as well as where it falls
short.

Due to the feedback and evidence of realized value by
adding Cursor to development flows, the CRC team decided to
fund Cursor subscriptions for all RSEs on our team as part
of a base developer toolkit. We continue to use Cursor as a
primary tool while also adapting software development
processes in light of its strengths and weaknesses [5]. In
this talk, I will discuss the process used to pilot Cursor,
the lessons learned by utilizing Cursor on various
projects, the outcomes of the completion survey, and
considerations for any RSE contributor or leader currently
deciding whether to introduce AI-first development
processes within their workflows. </p>
</div>
</div>
</div>

<div class="card">
<div class="card-header d-flex justify-content-center" id="heading32">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapse32"
aria-expanded="false" aria-controls="collapse32">
User-facing tutorials as code: reproducible and reliable
tutorials with CI/CD<br> Brigitta Sipőcz
</button>
</h5>
</div>

<div id="collapse32" class="collapse" aria-labelledby="heading32" data-parent="#accordion">
<div class="card-body">
<p> User-facing tutorials typically combine code, narrative
text, execution results, and visualizations. However, the
target audience for these tutorials can vary significantly.
Some tutorials serve as documentation for libraries,
accessed by users during asynchronous learning, while
others are designed for one-off workshops deployed on
specific scientific platforms.

This talk presents best practices for maintaining reliable
and reproducible executable tutorials, developed as part of
a Scientific Python Ecosystem Coordination (SPEC) document.
These guidelines distinguish between different types of
tutorials and workshop materials, offering targeted
recommendations for each category.

I will demonstrate an example repository that we've created
as a template and showcase our implementation of best
practices for Jupyter-based tutorials in core scientific
Python libraries such as NumPy and NetworkX. I'll also
discuss the practices we've adopted for Python tutorials at
the NASA/IPAC Infrared Science Archive.

The presentation focuses specifically on our ecosystem for
maintaining, testing, and deploying tutorials to the
scientific user community. In our approach, we treat
tutorials as we do open source library code: testing them
through automated and regular CI/CD processes while
presenting them in an aesthetically pleasing, user-friendly
format. </p>
</div>
</div>
</div>

</div>
