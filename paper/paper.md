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
    orcid: 0000-0002-3840-8760
    affiliation: 4, 5
  - name: Tomáš Raček
    orcid: 0000-0002-0296-2452
    affiliation: 4, 5
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
  - name: CEITEC-Central European Institute of Technology, Masaryk University, Kamenice 5, 602 00, Brno, Czech Republic
    index: 4
  - name: National Centre for Biomolecular Research, Faculty of Science, Masaryk University, Kamenice 5, 625 00, Brno, Czech Republic
    index: 5
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
It serves as the foundation for the sustainability of the diverse Tools Platform services, and for the interoperability between all these essential services (bio.tools [@usesDataFrom:Ison2019], BioContainers [@usesDataFrom:10.1093/bioinformatics/btx192], OpenEBench, Bioconda, WorkflowHub, usegalaxy.eu) and related resources outside of the ELIXIR Tools Platform (e.g. Bioschemas).

The goal of this project is to cross-compare and analyze the metadata centralized in the Tools Ecosystem to maintain high quality descriptions, together with the EDAM ontology [@usesDataFrom:10.1093/bioinformatics/btt113] [@usesDataFrom:jon_ison_2020_3899895] linked used for many annotations of these resources. In order to achieve these goals we need to design tools and processes that detect curation bottlenecks, perform rigorous data cross-validation and generate detailed reporting about potential issues and actionable items.

We present here in a first section the technical solution constructed to enable these analyses, and in the second section the first results obtained.

# Technical architecture

# Tools Ecosystem metrics

## EDAM usage in bio.tools

_a barplot specifying which proportion of each EDAM section is used in bio.tools_

_a barplot specifying which concepts of each section are most used for annotation in bio.tools_ 

## bio.tools annotation completeness

_a Venn diagram specifying which proportion of bio.tools is annotated with topics/operations/data/formats (can you do this with a Venn?)_

_an Upset diagram specifying which proportion of bio.tools is annotated with topics/operations/data/formats (can you do this with a Venn?)_

# Perspectives

## Acknowledgements
This work was funded/supported by ELIXIR, the research infrastructure for life-science data.

## References
