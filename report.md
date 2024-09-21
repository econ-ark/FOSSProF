---
title: Reproducibility Standards for Economics
subtitle: FOSSProF Final Report
banner: econ-ark-logo.png
exports:
  - format: pdf
    template: arxiv_nips
---

# Project Overview

## Project Summary

% Briefly describe the project, its objectives, and the open source software it focused on.

The Economics profession needs to catch up to other fields in software development and reproducibility practices. To address this problem, [Econ-ARK] has been working on [REMARK], a set of standards and tools for reproducibility in our work in Economics. REMARKs aims to be self-contained and complete projects whose contents should be executable by anyone on any computer (as long as it meets a minimal set of requirements and software).

This project aims to expand the REMARK standard to allow for the use of modern scientific publishing technologies such as Jupyter notebooks and [MyST] markdown and extend the REMARK standard to integrate with modern scientific publishing technologies. A critical aspect of REMARK is the emphasis on clear documentation, testing procedures, and standardized metadata to ensure that research outputs are not only reproducible but also easily understandable and reusable

### A brief history of REMARK

The REMARK project was started as a means to enhance the sharing and reproducibility of research that utilitzed [Econ-ARK]'s software. As the development of [HARK] was mostly guided by active research, it was important to not only expand the codebase but also to integrate the code with the documentation and drafting of academic manuscripts. In Economics, however, the standard practice is to treat the research manuscript and code as separate entities, with the code being used as a tool to generate results that are posted in the manuscript but then relegated to a `.zip` file that is attached to the published paper. This practice is not only inconvenient for researchers but also limits the ability to reproduce and build upon previous work, setting back the field of Economics.

Recognizing the need to integrate the development of scientific software with the publication of research, [Econ-ARK] began working on REMARK to showcase their own work in a more comprehensive manner. As the project grew, it became clear that REMARK could be a useful tool for the broader Economics community.

## Target Audience

% Who are the primary users or beneficiaries of the project? Are there secondary groups that benefit?

REMARKs origins are deeply rooted in the field of Economics, and it primarily targets students, researchers, and practitioners interested in reproducibility and open economic science. However, this project is not limited to the field of Economics and is intended to be a valuable resource for any field that uses scientific publishing technologies. As we've worked on REMARK, we've recognized the broader need for reproducible research practices, both in Economics but also in the broader Computational Social Sciences, where practitioners are increasingly interested in catching up to the standards set by open source software in other fields.

## Code Repository

% Please include links to publicly available code repositories.

This project is a collaboration between the [Econ-ARK] team and [Curvenote]. The [REMARK] standard can be found at the [REMARK GitHub repository](https://github.com/econ-ark/REMARK), but much of the code generated during this project has been integrated into the [MyST] project.

:::{tip}

- The [R[eplications/eproductions] and Explorations Made using ARK](https://github.com/econ-ark/REMARK) project is publicly available on GitHub.
- This project led to many contributions to the [MyST] project, a collection of tools for working with MyST markdown and is also publicly available on GitHub.
  :::

# Project Activities and Progress

## Work Completed

% Clearly outline the activities undertaken during the grant period. Did you achieve all your planned goals? If not, explain why and what was accomplished instead.

The primary goal of this project was to engage with and integrate the [MyST] markdown tools into the [REMARK] project to expand the range of tools available for the standard. To do this, we established a running meeting with the [Curvenote] team (among whom most MyST core developers work) to brainstorm the best way to integrate MyST into REMARK.

We also worked with some Johns Hopkins Economics PhD students to produce REMARKs of their projects, both to provide feedback on the REMARK standard and to show how REMARK can produce high-quality, reproducible research.

Lastly, we gave a presentation of the REMARK project at the [30th International Conference for Computing in Economics and Finance](https://comp-econ.com/30th-conference/), where we engaged with many students and researchers interested in open source software for reproducible research and advocated for the adoption of REMARKs as a standard for reproducible research in Economics.

### Collaboration with Myst/Curvenote

Throughout the project, we used the following issue to track our progress:

- [REMARK #152: Improvements to MyST Markdown](https://github.com/econ-ark/REMARK/issues/152)

This issue tracks the many contributions to the [MyST] project that were supported by this grant. A primary focus of this work was the extension of MyST markdown to support the translation of latex syntax into MyST markdown.

Among economists, the use of $\LaTeX$ is ubiquitous, and many researchers are deeply invested in the existing $\LaTeX$ environment. For this reason, we wanted to make the REMARK standard more flexible and accessible to adopt.

### Student generation of REMARKs

We used this grant to support the work of three Johns Hopkins University PhD students, [John Green], [Adam Edwards], and [Ashish Kumar], in the Department of Economics, for the development of REMARKs of their projects.

Engaging with students to produce REMARKs allowed us to gather feedback on the standard and to improve the documentation and tools available to researchers. Moreover, it will allow these students to produce high-quality, reproducible, and portable research that can be used as part of their job market and portfolio materials. It is our hope that this will lead to more visibility of their research and more exposure.

### Presentation of REMARK project at [CEF 2024](https://comp-econ.com/30th-conference/)

At the [30th International Conference for Computing in Economics and Finance](https://comp-econ.com/30th-conference/), hosted by Nanyang Technological University in Singapore, we gave a presentation of the REMARK project and engaged with many students and researchers interested in open source software for reproducible research.

The presentation consisted of introducing the REMARK standard, showing off the capabilities of REMARKs through a demo, and discussing the benefits of reproducibility in the Economics community.

After the presentation, we received feedback by a few researchers who were very interested in the REMARK standard, and were particularly eager to introduce their students to the toolset. We would love to take this presentation and workshop on the road, and introduce REMARKs to the next generation of economists.

:::{iframe} https://youtu.be/ykA2L9PNgW8?si=QUVD4_MIxf2Nqf2i
:width: 100%
A recap of the presentation we gave at CEF 2024 and a discussion of REMARKs with the [OpenSource.Science] Economics interest group.
:::

## Technical Milestones

% Discuss any specific technical milestones achieved, such as code releases, documentation updates, or bug fixes. Quantify accomplishments with metrics where possible (e.g., user growth, code contributions).

## Challenges and Solutions

% Share any challenges encountered during the project and how you addressed them.

# Outcomes and Impact

## Project Impact

% Describe the positive impact of the project on the Hopkins community, the open source software ecosystem, or any other relevant groups. Use concrete examples and data to support your claims where possible.

The overarching objective of REMARK is to improve the reliability and trustworthiness of scientific findings within fields heavily reliant on computational methods.

## Community Engagement

% Did you actively engage with the open source community through contributions, conferences, or workshops? Share details and metrics of participation.

## Sustainability and Future Plans

% Explain how the project will be sustained beyond the grant period. Are there plans for future development, funding, or community support? Is there potential for further impact?

### Renaming the project

### Cultivating Community Ownership and Contribution

### Adapting to Evolving Research Practices

### Securing Financial Support

### Taking the project on the road

## Lessons Learned

% Share key takeaways and insights gained from the project.

% ## Attachments

% Include relevant documents such as screenshots, code samples, documentation updates, or presentations.

# Financial Information

## Grant Expenditures

% Provide a detailed breakdown of how the grant funds were used. This should be consistent with the approved budget in the grant proposal.

## Budget Variance

% Explain any significant deviations from the original budget.

[Econ-ARK]: https://econ-ark.org/
[REMARK]: https://github.com/econ-ark/REMARK
[Curvenote]: https://curvenote.com/
[MyST]: https://github.com/jupyter-book/mystmd
[OpenSource.Science]: https://opensource.science/
