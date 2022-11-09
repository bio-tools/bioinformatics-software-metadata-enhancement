---
title: 'Scientific and technical enhancement of bioinformatics software metadata using the Tools Ecosystem open infrastructure'
title_short: 'Enhancement of bioinformatics software metadata'
tags:
  - Software Metadata
  - Ontologies
  - Workflows
  - Semantic Web
  - Bioinformatics
authors:
  - name: Lucie Lamothe
    orcid: 
    affiliation: 1
  - name: Jennifer Rugaard Bregndahl Jensen
    orcid: 
    affiliation: 
  - name: Hans Ienasescu
    orcid: 
    affiliation:
  - name: Johan Gustafsson
    orcid: 
    affiliation:
  - name: Alban Gaignard
    orcid: 
    affiliation:
  - name: Dmitry Repchevski
    orcid: 
    affiliation:
  - name: Radka Svobodová
    orcid: 
    affiliation:
  - name: Tomas Racek
    orcid: 
    affiliation:
  - name: Magnus Palmblad
    orcid: 0000-0002-5865-8994 
    affiliation: 3
  - name: Matúš Kalaš
    orcid: 
    affiliation:
  - name: Hervé Ménager
    orcid: 0000-0002-7552-1009
    affiliation: 1, 2
affiliations:
  - name: Institut Français de Bioinformatique, Evry, F-91000, France
    index: 1
  - name: Institut Pasteur, Université Paris Cité, Bioinformatics and Biostatistics Hub, F-75015 Paris, France
    index: 2
  - name: Leiden University Medical Center, Postbus 9600, 2300 RC Leiden, The Netherlands
    index: 3
date: 9 November 2022
cito-bibliography: paper.bib
event: BH22EU
biohackathon_name: "BioHackathon Europe 2022"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Paris, France, 2022"
group: Project 25
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/bio-tools/bioinformatics-software-metadata-enhancement
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Lucie Lamothe,  Jennifer Rugaard Bregndahl Jensen \emph{et al.}
---


# Introduction

The Tools Ecosystem is a centralized repository for the open and transparent exchange of metadata about software tools and services in Bioinformatics and Life Sciences.
It serves as the foundation for the sustainability of the diverse Tools Platform services, and for the interoperability between all these essential services (bio.tools [@usesDataFrom:Ison2019], BioContainers, OpenEBench, Bioconda, WorkflowHub, usegalaxy.eu) and related resources outside of the ELIXIR Tools Platform (e.g. Bioschemas).

The goal of this project is to cross-compare and analyze the metadata centralized in the Tools Ecosystem to maintain high quality descriptions, together with the EDAM ontology [@usesDataFrom:10.1093/bioinformatics/btt113] [@usesDataFrom:jon_ison_2020_3899895] linked used for many annotations of these resources. In order to achieve these goals we need to design tools and processes that detect curation bottlenecks, perform rigorous data cross-validation and generate detailed reporting about potential issues and actionable items.

Multiple strategies will be explored:
- Comparison of the functional profiles of bio.tools entries with the corresponding semantic constraints defined in EDAM. Develop software to identify and report on inconsistencies between resources.
- Comparison of the metadata defining a software tool with the knowledge extracted from publications that cite it, as well as the workflows that use it.

Beyond the immediate improvement of the metadata, we plan to use the results of these analyses in order to:
- Automate relevant analyses using continuous integration mechanisms (extending previous and current work in EDAM and the Tools Ecosystem)
- Improve curation user interfaces to reduce the risk of annotation errors.
- Provide high quality functional tool profiles to be used in the context of workflow annotation

Another important goal is to provide onboarding of and support for scientific communities joining the Biohackathon.

Given the nature of the data we use in this project, we will be working in close collaboration with the project "Enhance RDM in Galaxy by utilizing RO-Crates", who will also be leveraging workflow and software metadata from the same resources.

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table 1
| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

Tables and figures should be given before they are mentioned in the main text.
A figure is added with:

![BioHackrXiv logo](./biohackrxiv.png)
 
Figure 1. The BioHackrXiv logo.

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2


# Results


# Discussion

...

## Acknowledgements
This work was funded/supported by ELIXIR, the research infrastructure for life-science data.

## References
