---
title: Reproducibility Standards for Economics
subtitle: FOSSProF Final Report
banner: econ-ark-logo.png
exports:
  - format: pdf
    template: arxiv_nips
    output: report.pdf
  - format: docx
    output: report.docx
acknowledgements: |
  This project was funded by the [Johns Hopkins University](https://jhu.edu) [Open Source Programs Office](https://ospo.library.jhu.edu/) and the [Alfred P. Sloan Foundation](https://sloan.org).
---

# Project Overview

## Project Summary

% Briefly describe the project, its objectives, and the open source software it focused on.

The Economics profession needs to catch up to other technical fields in software development, reproducibility practices, and "exchangability" of results.

To that end, [Econ-ARK](https://econ-ark.org) has been working for several years on the [REMARK](https://github.com/econ-ark/REMARK) project, a set of standards and tools for reproducibility for computational modeling in economics.  [REMARK] are self-contained and complete projects whose contents should be executable by anyone on any modern computer (local or cloud), so long as the platform has the necessary hardware (generically described). A critical aspect of REMARK is the emphasis on clear documentation, testing procedures, and standardized metadata to ensure that research outputs are not only reproducible but also easily understandable and reusable

The design specs of the REMARK standard have been crafted with the collaboration of the editor of a projected journal that would require all submissions to abide by the REMARK standard. 

While we have solved most of the computational challenges (using the blossoming ecosystem of tools including Docker containers, version control, etc), one piece of the infrastructure needed to complete the specification is still lacking: A robust, reproducible, and portable standard for production of the text of the paper (or other research product).

The project sponsored by FossProf allowed us to hire a developer, *Curvenote*, to fill in some crucial gaps required to translate the standard medium of technical writing, $\LaTeX$, to the new world of lightweight reproducible content. The bulk of the other FossProf funding allowed some JHU PhD students to create new example REMARKs that use these tools.

### A brief history of REMARK

The REMARK project started as a means to enhance the sharing and reproducibility of research that utilized the [Econ-ARK](https://econ-ark.org)'s [HARK](https://docs.econ-ark.org) toolkit. As the development of [HARK] was mostly guided by active research, it was important not only to expand the codebase but also to integrate the code with the documentation and drafting of academic manuscripts. In economics, however, the standard practice is to treat the research manuscript and code as entirely separate entities, with the code being used as a tool to generate results that are posted in the manuscript but then relegated to a `.zip` file that is attached to the published paper. This practice is not only inconvenient for researchers but also limits the ability to reproduce and build upon previous work, setting back the field of Economics.

Recognizing the need to integrate the development of scientific software with the publication of research, [Econ-ARK] began working on REMARK standard to make the models and results from the toolkit easy to share. As the project grew, it became clear that REMARK could be a useful tool for the broader Economics community.

## Target Audience

% Who are the primary users or beneficiaries of the project? Are there secondary groups that benefit?

REMARKs origins are deeply rooted in the field of Economics, and it primarily targets students, researchers, and practitioners interested in reproducibility and open economic science. However, this project is not limited to the field of Economics and is intended to be a valuable resource for any field that uses scientific publishing technologies. As we've worked on the REMARK standard, we've recognized the broader need for reproducible research practices, both in Economics but also in the broader Computational Social Sciences, where practitioners are increasingly interested in catching up to the standards set by open source software in other fields.

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

:::{figure} sce_letter
:alt: An excerpt from A Letter from the Society for Computational Economics President Lilia Maliar
:align: center

An excerpt from A Letter from the Society for Computational Economics President Lilia Maliar describing the presentation of the REMARK project at the 30th International Conference for Computing in Economics and Finance. This screenshot was taken from [the SCE website](https://comp-econ.com/).
:::

The presentation consisted of introducing the REMARK standard, showing off the capabilities of REMARKs through a demo, and discussing the benefits of reproducibility in the Economics community.

After the presentation, we received feedback by a few researchers who were very interested in the REMARK standard, and were particularly eager to introduce their students to the toolset. We would love to take this presentation and workshop on the road, and introduce REMARKs to the next generation of economists.

:::{iframe} https://www.youtube.com/embed/ykA2L9PNgW8?si=APVDvGG2OFzeYWNl
:width: 100%
A recap of the presentation we gave at CEF 2024 and a discussion of REMARKs with the [OpenSource.Science] Economics interest group.
:::

## Technical Milestones

% Discuss any specific technical milestones achieved, such as code releases, documentation updates, or bug fixes. Quantify accomplishments with metrics where possible (e.g., user growth, code contributions).

A major milestone of this project was the expansion of MyST compatibility with $\LaTeX$ syntax. Because many of the previous REMARKs were written in $\LaTeX$, it was important to ensure backwards compatibility and the ability to refresh existing REMARKs with new MyST capabilities. Although we have not yet reached the goal of complete backwards compatibility, we have made significant progress in this area and have made it easier to transition to the new standard. This work will continue in the future, and we welcome contributions from the open source community to help us reach this goal.

Second, we started work on a `remark` command-line-interface tool that can be used to generate REMARK templates and check them against the REMARK standard. This tool also includes functionalities for building environments and running reproducibility scripts.

Third, we have continued to expand the catalog of existing REMARKs, including the addition of several new REMARKs of student projects as well as active research projects both within and outside [Econ-ARK].

## Challenges and Solutions

% Share any challenges encountered during the project and how you addressed them.

# Outcomes and Impact

## Project Impact

% Describe the positive impact of the project on the Hopkins community, the open source software ecosystem, or any other relevant groups. Use concrete examples and data to support your claims where possible.

The overarching objective of REMARK is to improve the reliability and trustworthiness of scientific findings within fields heavily reliant on computational methods. By promoting the use of standardized tools and workflows, REMARK aims to make computational research in economics and social sciences more transparent and reproducible.

REMARK encourages the adoption of best practices in software development, documentation, and manuscript preparation, within the economics community which has traditionally lagged behind other computational fields. Our goal is to facilityate knowledge sharing and collaboration, reduce duplication efforts, and accelerate the dissemination of knowledge within the field.

## Community Engagement

% Did you actively engage with the open source community through contributions, conferences, or workshops? Share details and metrics of participation.

Our team primarily engaged with the main developers of the [MyST] project through their company [Curvenote]. We set up a weekly meeting where we discussed our needs for the REMARK project as well as suggestions for how to improve the MyST project itself. The team at MyST/Curvenote is incredibly experienced and connected with the open science and publishing communities, and we have learned a lot from them.

Additionally, we advocated for the use of reproducibility standards at the 30th International Conference for Computing in Economics and Finance and at the [OpenSource.Science] Economics interest group. We met with many students and researchers interested in open source software for reproducible research and advocated for the adoption of REMARKs as a standard for reproducible research in Economics.

## Sustainability and Future Plans

% Explain how the project will be sustained beyond the grant period. Are there plans for future development, funding, or community support? Is there potential for further impact?

### Renaming the project

The need for REMARK arose from our desire to make our own research more reproducible and to share our work with others. However, our engagement with the broader community has highlighted the need for reproducibility standards beyond our application and field. Currently, REMARK stands for "R[eplications]/[eproductions] and Explorations Made using ARK", clearly linking it to the Econ-ARK project. This close association can be perceived as a limitation, creating confusion and potentially hindering broader adoption. 

To address this issue, we have discussed internally the need to rename the project into **"SCI-PASS"**, which stands for "Scholarly Communication Infrastructure for Publishing and Archiving Scientific Software". This name change signifies a strategic shift toward establishing a more universal and inclusive standard for reproducible scientific software. Moreover, it clearly communicates the project's purpose and intended scope, eliminating the misconception that it's solely tied to Econ-ARK or Python. This language-agnostic standard has the potential to attract a wider range of researchers and institutions, fostering greater collaboration and advancing the practice of reproducible research across diciplines. 

It is important to note that renaming REMARK is not merely a cosmetic change, but rather a crucial step toward building a robust and sustainable ecosystem for reproducible research. The evolution of the project involves developing a comprehensive roadmap for implementation which includes overcoming technical obstacles, establishing clear metadata guidelines, and creating user-friedly tools and resources to facilitate broad applicability and adoption. Additionally, we will continue to actively engage with the scientific community to promote the standard and foster collaboration, including establishing communication channels with journal editors, data editors, and researchers from diverse fields. In essence, "SCI-PASS" represents a pivotal step toward achieving the project's ambitious goals of promoting and standardizing reproducible research practices across the scientific community. As such, we also consider "SCI-PASS" as short for "scientific passport", a term that encapsulates the idea of portability and exchangeability of research outputs.

:::{important}

**SCI-PASS** stands for:
1. *Scholarly Communication Infrastructure for Publishing and Archiving Scientific Software* - a new name for the REMARK project to better reflect its scope and potential for broader adoption.
2. *Scientific Passport* - enables scientific software to be portable across different environments. 

:::


### Adapting to Evolving Research Practices

To be successful, the REMARK/SCI-PASS project will need to embrace modern publishing technologies. Recognizing the limitations of $\LaTeX$, this grant helped us integrate modern scientific publishing tools like Jupyter Notebooks and MyST Markdown. This shift toward the Executable Books ecosystem is intented to enhance user-friendliness, interactivity, and accessibility for researchers. In the long-term, we aim to further integrate with open science infrastructure, such as established open science publishing platforms for peer-review and publishing like [Open Journals](https://theoj.org/) and [The Journal of Open Source Software](https://joss.theoj.org/). 

While REMARK currently focuses on `python` software, we are commited to expanding langauge support to accomodate the diverse set of tools used in computational research. This expansion aims to broaden the project's reach and applicability across disciplines. Moreover, the project's long-term sustainability depends on active community engagement, which includes collaborating with journal and data editors, organizing workshops and tutorials, and establishing an independent board of advisors with expertise in computational science, library science, and relevant research domains. By embracing these adaptations, the REMARK/SCI-PASS project aims to evolve into a robust and sustainable standard for reproducible research, aligning with evolving practices and solidyfing its place withint the future of open science. 


### Taking REMARK/SCI-PASS on the road

This grant allowed us to host a workshop at the 30th International Conference for Computing in Economics and Finance in Singapore, where we discussed open science, reproducibility, and the REMARK standard. The experience and feedback we gathered was incredibly valuable, and we are eager to take the project on the road to more conferences and events. Below we describe a few of the ways in which we plan to advocate for open science and reproducibility:

1. **Replication Competitions** - Competitions where researchers are challenged to replicate the results of notable papers, which will provide a practical demonstration of the REMARK standard and incentivize adoption. 
2. **Tutorials and Workshops** - Target students and researchers to provide hands-on experience using our tools, demonstrating how to create reproducible research outputs and higlighting the advantages of open science. 
3. **Talks** - Engage with journal editors and data editors to seek feedback and collaboration, to get a better sense of how our project can streamline review process, ensure reproduciblity, and enhance the credibility of published research. 

By combining these outreach efforts, the REMARK/SCI-PASS project can expand its reach and encourage wider adoption. 


% ## Lessons Learned

% Share key takeaways and insights gained from the project.

% ## Attachments

% Include relevant documents such as screenshots, code samples, documentation updates, or presentations.

# Financial Information

## Grant Expenditures

% Provide a detailed breakdown of how the grant funds were used. This should be consistent with the approved budget in the grant proposal.

:::{attention}

Please see attached Financial Report for a detailed breakdown of how the grant funds were used. 

:::

The majority of the funds were used to contract with Curvenote to integrate the MyST tools into the REMARK project. We also supported the work of three Johns Hopkins University PhD students over the summer of 2024 to produce REMARKs of their ongoing research projects. Finally, we hosted a workshop at the 30th International Conference for Computing in Economics and Finance in Singapore, and used the remaining funds for travel and lodging. 



% ## Budget Variance

% Explain any significant deviations from the original budget.

[Econ-ARK]: https://econ-ark.org/
[REMARK]: https://github.com/econ-ark/REMARK
[Curvenote]: https://curvenote.com/
[MyST]: https://github.com/jupyter-book/mystmd
[OpenSource.Science]: https://opensource.science/
