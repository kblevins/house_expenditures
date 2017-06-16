---
title: "Draft Read Me"
author: "Eric and Ryan"
date: "1/17/2017"
output: html_document
---

**Slack:** #propublica

**Project Description:** This ProPublica repository is part of Data for Democracy. Our purpose is to collaboratively work through analytic processes that support the journalism at ProPublica. 

## Analysis Workflow

Reading, cleaning, and analyzing data should be done in a reproducible notebook format when possible. 

### Loading and Cleaning Datasets
For each analysis, data needs to be loaded and cleaned to a format that is useable for the current analysis and for future analyses.

After data has been cleaned, the resulting dataset should be written as a csv. The csv should be made available on [data.world](https://data.world/data4democracy/house-expenditures). 

### Exploratory Analysis
Team members working in exploratory analysis work up general statistics, distributions of important variables, and hypotheses based on initial exploration of covariation. If this analysis is in a notebook that is different from the cleaning script, there should be documentation of which scripts need to be run in order to reproduce the analysis results. 

When an analysis job is complete, a pull request to the GitHub repo should be made to be edited by collaborators of the project or a committee of assigned editors.

### Modeling
Team members use modeling techniques to test the hypotheses generated in the exploratory analysis phase and to quantify relationships between variables in the data. Team members may also be working to test specific hypotheses generated by ProPublica.

Algorithms used in the modeling should be vetted through open discussions with the team and through pull requests, and final model specification should be a collaborative effort using any individual findings from the discussion. The project readme should outline these specifications, and the final modeling code should be pushed to the GitHub repo.

### Reporting
Team members detail the findings in a reproducible report that can be immediately used by ProPublica. All sources and data used should be linked in the report, and the project readme containing all background in methodology and links to data and code.