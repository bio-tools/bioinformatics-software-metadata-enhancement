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
    orcid: 0000-0001-9727-2544
    affiliation:
  - name: Ove Johan Ragnar Gustafsson
    orcid: 0000-0002-2977-5032
    affiliation: 6
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
  - name: Australian BioCommons, University of Melbourne, Victoria, Australia
    index: 6
  - name: National Life Science Supercomputing Center, Technical University of Denmark, Denmark
    index: 7

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

The goal of this project is to cross-compare and analyze the metadata centralized in the Tools Ecosystem to maintain high quality descriptions, together with the EDAM ontology [@providesDataFor:10.1093/bioinformatics/btt113] linked used for many annotations of these resources. In order to achieve these goals we need to design tools and processes that detect curation bottlenecks, perform rigorous data cross-validation and generate detailed reporting about potential issues and actionable items.

We present here in a first section the results of these analyses, and in a second section the methods and approach we used, before to discuss potential perspectives for improved monitoring and curation of the Tools Ecosystem metadata and EDAM, as well as the insights to the .

# Results

## EDAM usage in bio.tools

_a barplot specifying which proportion of each EDAM section is used in bio.tools_

_a barplot specifying which concepts of each section are most used for annotation in bio.tools_ 

## bio.tools annotation completeness

_a Venn diagram specifying which proportion of bio.tools is annotated with topics/operations/data/formats (can you do this with a Venn?)_

_an Upset diagram specifying which proportion of bio.tools is annotated with topics/operations/data/formats (can you do this with a Venn?)_

## tool function signatures

_a plot of the proportion of validated complete function signatures in bio.tools_

_a listing of the top 10 most erroneous function signatures in bio.tools_

# Methods

To facilitate the analysis of the data extracted from the Tools Ecosystem and other resources, we decided to make them available in a SPARQL endpoint, a solution that enables the querying of RDF resources. The various resources uploaded to a GraphDB-based SPARQL endpoint include:
- the EDAM ontology [@providesDataFor:jon_ison_2020_3899895], available in its development version at https://raw.githubusercontent.com/edamontology/edamontology/main/EDAM_dev.owl.
- the bio.tools contents [@providesDataFor:Ison2019], available on the Tools Platform Ecosystem git repository as a Turtle-formatted BioSchemas [@providesMethodFor:gray2017bioschemas] file at https://raw.githubusercontent.com/bio-tools/content/master/datasets/bioschemas-dump.ttl.
- (add something here about the WorkflowHub [@usesDataFrom:carole_goble_2021_4605654] dump provided by Johan and Alban).

The analysis of the data is performed using SPARQL queries, which are performed using a number of Jupyter notebooks. The various results are visualized using python libraries such as matplotlib and R packages.

# Perspectives

# Code availability

The code described to run the analyses and obtain the results presented here is freely available [on GitHub](https://github.com/bio-tools/biohackathon2022). The data collected are also freely available on the [Tools Ecosystem main repository](https://github.com/bio-tools/content/) and on the [EDAM repository](https://github.com/edamontology/edamontology/).

## Acknowledgements
This work was funded/supported by ELIXIR, the research infrastructure for life-science data.

## References
