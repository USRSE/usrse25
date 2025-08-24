---
layout: page
title: Workshops
description:
menubar: program
permalink: program/workshops/
menubar_toc: true
set_last_modified: true
---

<a name="w-pegasus"></a>
## AI Workflows with ACCESS Pegasus

_Karan Vahi and Mats Rynge_

Workflows are a key technology for enabling complex
scientific computations. They capture the interdependencies
between processing steps in data analysis and simulation
pipelines as well as the mechanisms to execute those steps
reliably and efficiently. Workflows can capture complex
processes, promote sharing and reuse, and also provide
provenance information necessary for the verification of
scientific results and scientific reproducibility.

Participants will learn to use Pegasus, a leading
scientific workflow management system now integrated into
the ACCESS Support offerings
(https://support.access-ci.org/pegasus). ACCESS Pegasus
provides a fully hosted environment built on Open OnDemand
and Jupyter, enabling users to develop and run workflows
directly from a web browser. Workflow execution is powered
by HTCondor Annex, allowing jobs to run across multiple
ACCESS resources, including PSC Bridges-2, SDSC Expanse,
Purdue Anvil, NCSA Delta, and IU Jetstream2.
Through hands-on exercises in a hosted Jupyter notebook,
participants will work through an example LLM-RAG (Large
Language Model - Retrieval Augmented Generation) workflow
that leverages GPUs across ACCESS resources. Along the way,
the tutorial will address key challenges and best practices
across the entire workflow lifecycle.

Pegasus (https://pegasus.isi.edu) is used in a number of
scientific domains doing production grade science. Pegasus
is used in astronomy, gravitational wave science,
bioinformatics, civil engineering, climate modeling,
earthquake science, molecular dynamics and other complex
analyses.

------

<a name="w-agile"></a>
## Agile Foundations for RSEs: Building an AI Assistant with Agile

_Tisha Charles and David Luet_

This 90-minute workshop introduces Agile methodology and
its application to RSE projects. Participants will learn
the core principles and values of Agile and explore common
frameworks such as Scrum and Kanban. The workshop includes
a hands-on exercise where participants collaboratively plan
a simplified "Gemini Gem" feature, applying Agile
techniques to user story creation, sprint planning, and
backlog management. Google Gemini Gems are customizable
versions of the Gemini AI chatbot, allowing users to create
specialized AI assistants for specific tasks. This
practical approach will equip RSEs with valuable skills to
manage complex software projects, foster collaboration with
researchers, and deliver incremental value in research. No
prior experience in Agile or Gemini Gems development is
required. Participants should bring a laptop, have a Google
account that has access to Gemini, and, optionally, a
GitHub account.

------

<a name="w-user"></a>
## Learning to Talk with Your Users: User Experience Research for RSEs

_Johanna Cohoon, Rajshree Deshmukh, and Mary Goldman_

A few conversations with users can have a big impact. User
research helps engineers uncover unmet needs, design more
intuitive tools, reduce development churn by catching
issues before they're coded, and decrease support
needs—ultimately saving time, effort, and cost across the
project lifecycle. This workshop will provide practical
instruction on a common technique for user research:
semi-structured interviews. Semi-structured interviews are
a flexible method for gathering rich information about
experiences, perspectives, values, and challenges that can
be used to improve research software products. Workshop
participants will learn about recruitment, protocol
development, and analysis and will leave the workshop with
reusable resources for future use. Through this training,
research software engineers will gain confidence in
identifying user requirements and experience issues,
gathering actionable feedback, and prioritizing future
development directions.

------

<a name="w-testing"></a>
## An Experimentalist Approach to Software Testing

_Jeff Soules and Brian Ward_

Most builders of research software believe they should
write tests for their tools, yet many struggle to do so
efficiently and effectively. Formal strategies like
Test-Driven Design may seem intimidating or inaccessible,
while developers relying on an ad-hoc approach can suffer
from “blank page syndrome” and struggle to provide
efficient, complete coverage of essential functionality.
Sometimes this leads to tests which actually spend more
time testing mathematical properties or theories rather
than the implementation, wasting both compute time and
developer time; in other cases, developers fall back to
manual tests, leading to developer anxiety and questionable
software reliability.

In this workshop, we introduce a scientist-friendly
perspective on software tests: tests are controlled
experiments run on the implementation code. We will
demonstrate a minimal setup for automated testing and the
features to expect from a good testing system, and cover
examples of common failures in test design. Participants
will have the opportunity to apply this approach by
revising practical examples—both of flawed tests, and of
implementation code that creates friction when writing
tests—before we reconvene as a full group to discuss
solutions.

A computer will be needed for full participation, though
attendees without one will still benefit from the
discussion. Exercises will be provided in Python and C++.

------

<a name="w-futures"></a>
## Resilient Data Futures: How Do We Save, Share, and Fund Critical Data Stores Outside Traditional Systems?

_Elianna DeSota and Jon Starr_

U.S.-funded data repositories are increasingly unstable,
losing funding, or shutting down entirely without closing
processes, or a clear path towards maintaining this data.
This rupture not only threatens long-term access to
research outputs, but they highlight how fragile our
current models for data stewardship are.

This workshop aims to unlock the latent knowledge in the
RSE community by crowdsourcing pre-existing solutions for
storing and sustaining large datasets, identifying the
barriers to use, and agreeing on one step we can take
together towards sustainable data infrastructure. The RSE
community is the current stewards of our research
infrastructure, and are both most at risk when data
infrastructure is shut down or deprioritized. We’re also
most well-positioned to define solutions that can support
continued research.

Computers are not required, but recommended for digital
note taking.

------

<a name="w-sleap"></a>
## Introduction to Multi-Animal Pose Tracking with SLEAP

_Elizabeth Berrigan, Andrew Park, and Talmo Pereira_

This hands-on workshop introduces SLEAP (Social LEAP
Estimates Animal Poses), an open-source deep learning
framework for pose estimation and tracking—the process of
identifying and following grouped landmarks, represented as
nodes and edges, across video frames. Originally developed
for animal behavior research, SLEAP is now a
general-purpose toolkit used in diverse applications
including plant phenotyping, disease progression
monitoring, reinforcement learning, and behavioral analysis
in space.

Participants will learn the full SLEAP workflow: defining
skeletons or graph structures, labeling keypoints, training
and configuring deep learning models, running inference,
tracking across frames, proofreading predictions, and
exporting results. The workshop highlights SLEAP’s
intuitive human-in-the-loop interface, fast training and
inference (with support for pretrained models), and
flexible Python API for integration into research pipelines.
To support hands-on participation, each attendee will
access a cloud-based virtual machine with SLEAP
pre-installed and GPU acceleration. No prior deep learning
experience or software installation is required—just a
laptop with Google Chrome, a stable internet connection,
and a Gmail account.

By the end of the session, participants will be equipped to
apply SLEAP to their own datasets for efficient, scalable,
and reproducible pose estimation and tracking.

------

<a name="w-cyverse"></a>
## Hands-on scalable cloud automation and platform services for AI using CyVerse

_Edwin Skidmore, Sarah Roberts, and Michelle Yung_

Ready to empower your research project or community of
users with the latest AI infrastructure? This hands-on
workshop provides Research Software Engineers (RSEs) with
the skills to build and support your own bespoke, secure
AI/ML infrastructure using the powerful resources of
CyVerse.

As RSEs, we are increasingly being called upon to provide
custom Large Language Model (LLM) and machine learning (ML)
integrations to address research problems. Identifying a
platform that is both developer-friendly and user-friendly
for deploying modern applications – such as those built
with Gradio and Streamlit – along with an ever-growing
ecosystem of MLOps tools, while providing an integrated
institutional authentication, can be daunting. Discover how
CyVerse can help you deliver these software and services
faster while providing access to high-performance
computing, massive data storage, and flexible cloud
environments – including commercial clouds (AWS, Azure,
etc) and cutting-edge GPUs available at no cost through NSF
Jetstream2!

We'll guide you through using CyVerse's CACAO (Cloud
Automation & Continuous Analysis Orchestration) for
effortless deployment in the cloud, including your very own
LLMs. You’ll also learn how to harness CyVerse APIs to
seamlessly integrate its services into your custom
applications and scientific workflows. Bring your laptop,
sign up for a free CyVerse account, and get ready for
practical exercises that will get you started in building
tailored tools that can converse directly with your
research data!

------
<a name="w-joss"></a>
## The Journal of Open Source Software: Live demonstration and discussion

_Patrick Diehl, Daniel S. Katz, Kyle Niemeyer_

The Journal of Open Source Software (JOSS) supports valuing research software contributions to the open source software (OSS) ecosystem by providing a free, diamond open access, and open-source venue that is run in the style of OSS itself. A particularly distinctive element of JOSS is that it uses open peer review in a collaborative, iterative format, unlike most publishers. Additionally, all the components of the process—from the reviews to the papers to the software that is the subject of the papers to the software that the journal runs—are open. In this session, we will describe JOSS’s history and its peer review process using an editorial bot and present statistics gathered from JOSS’s public review history on GitHub showing an increasing number of peer reviewed papers each year. We will then demonstrate JOSS showing the various roles that exist, including author, editor, and reviewer. Before and while running this live demo, we will take questions from the audience and discuss JOSS, research software, and publishing more widely. We'll end by discussing some challenges JOSS faces.
