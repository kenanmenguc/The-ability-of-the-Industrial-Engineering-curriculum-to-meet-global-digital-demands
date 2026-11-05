# The-ability-of-the-Industrial-Engineering-curriculum-to-meet-global-digital-demands
The ability of the Industrial Engineering curriculum to meet global digital demands
# Curriculum–Labor Market Alignment: A Network-Based Analysis

## Overview
This repository contains the code and datasets used in the study examining the alignment between the undergraduate curriculum of Istanbul Technical University (ITU) Industrial Engineering (IE) program and global digital labor market demands.

The study uses a network-based framework to compare the skills supplied by university courses with the qualifications demanded in freelance job postings on Upwork (September 2026).

## Repository Contents

- **Code/** – Source code for data processing, keyword extraction, network construction, centrality analysis, and curriculum–market alignment assessment.
- **Supply Data/** – Qualification and keyword data extracted from the ITU Industrial Engineering undergraduate curriculum.
- **Demand Data/** – Qualification data extracted from approximately 10,000 Upwork job postings, representing 3,482 unique qualifications.

## Methodology
The analysis constructs weighted, undirected co-occurrence networks for both curriculum supply and labor market demand. Network characteristics are examined using:

- Degree Centrality
- Betweenness Centrality
- Closeness Centrality
- Eigenvector Centrality
- PageRank
- HITS Authority Scores

Three curriculum scenarios are evaluated:
1. Compulsory courses.
2. Compulsory and departmental elective courses.
3. All courses, including university-wide electives.

A supernode approach is used to evaluate the position of each curriculum scenario within the global digital labor market network.

## Purpose
The repository provides the data and computational workflow supporting the study's findings. It aims to offer a reproducible framework for evaluating curriculum relevance and identifying potential skill gaps between higher education and evolving digital labor market requirements.

## Data Source
- **Labor Market Data:** Upwork job postings, September 2026.
- **Curriculum Data:** Istanbul Technical University, Industrial Engineering Undergraduate Course Catalog.

