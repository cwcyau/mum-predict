# MUM-PREDICT

WP1 analysis and methodology repository for the MUM-PREDICT project.

## Team Members

- Christopher Yau
- 1x PDRA (Manchester, to be appointed)
- Jonathan Kennedy
- Utkarsh Agrawal

## Overview 

We will determine the clusters and trajectories of health conditions in pregnant women with pre-existing MM. We will define morbidities as a continuum where possible using biomarkers and physiological measurements, and take into account subclinical disease status (e.g. subclinical hypothyroidism) and severity of disease (e.g. diabetes with microvascular complications). Our preliminary cluster analysis featured dominance of mental health conditions for women entering pregnancy with MM, but also, distinct clusters driven by metabolic-inflammatory pathways. 

We will conduct in depth analysis of clusters to identify determinants during their life course, where required with other successful collaboratives (e.g. Cardiff and/or Newcastle University). For example, for clusters predominantly driven by mental illness, we will determine timelines of diagnosis, their sequence and associated determinants at each time point using SAIL data and BiB cohort data, as these have linkage to detailed data on wider determinants (i.e. education, census, health survey, care and family court datasets). This analysis will also allow us to describe in detail the social, clinical and lifestyle circumstances that associate with a woman’s transition between multimorbid states.

In addition, we will report how these clusters differ by age, ethnicity and socioeconomic factors, which can inform strategies to reduce inequalities. For example, we expect to see a mental health dominant trajectory that involves rapid accumulation of mental health conditions, where young women who experience deprivation and multiple adversities (e.g., looked-after child, intimate partner violence) are overrepresented. We will identify potential protective factors to reduce the chance of such transitions, for example factors such as access to higher education or employment might correlate because they indicate improving social circumstances.

## Datasets

- CPRD Pregnancy Register with Mother-Baby linkage and Hospital Episodes Statistics (HES) linkage (UK), 
- SAIL (Wales), 
- NSD (Scotland)
- Northern Ireland Maternity System (NIMATS) 
- Born in Bradford (BiB).

## Analysis plan

For the discovery and characterisation of MM clusters and trajectories we will use multi-state regression modelling (MSRM) based on the well-established framework implemented in the R package `msm`. 

MSRMs model the probability of an individual transitioning from one set of conditions to another as functions of stable and time varying prognostic factors allowing the effects of age, ethnicity, parity, social-deprivation and lifestyle factors on clustering and trajectories to be assessed.

## Deliverables Outputs (Timeline in Years (Yr)): 

1) Key MM clusters and trajectories (Yr1); 
2) Their determinants, in specific clusters (e.g. clusters dominated by mental conditions) (Yr2); 
3) Time-points for future preventive interventions (Yr2); and 
4) Inequalities observed and strategies to reduce them (Yr3).

