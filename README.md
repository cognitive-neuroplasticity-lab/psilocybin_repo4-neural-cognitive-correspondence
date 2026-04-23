# Neural-Cognitive Correspondence in the Psilocybin Dataset

A neuroimaging analysis project examining how psilocybin-related changes in large-scale brain networks correspond with cognitive performance and behavioural outcomes.

This repository extends temporal network analysis into brain-behaviour modelling by testing whether neural reorganization aligns with preserved, enhanced, or altered cognition across participants.

## Project Aim

To test whether variation in psilocybin-associated network changes meaningfully relates to cognitive performance profiles, and to establish a scalable framework for future subject-level longitudinal and translational analyses.

## Dataset Used

- Dataset: Psilocybin Precision Functional Mapping  
- OpenNeuro ID: ds006072  
- Population: Healthy adults  
- Design: Repeated-measures pharmacological neuroimaging study  
- Modalities Available: Resting-state fMRI, Task fMRI, Structural MRI, Diffusion MRI

## Analytical Scope

This repository focuses on a proof-of-concept framework using:

- Cognitive domain landscape mapping
- Network-level cognition signatures
- Participant-level brain-behaviour associations
- Cognitive response profile clustering
- Reproducibility and feature stability testing

## Why a Brain-Behaviour Pipeline Was Used

Neural effects alone do not determine scientific or therapeutic relevance. A brain-behaviour pipeline was used to test whether measurable changes in network organization correspond with cognition rather than assuming that all neural change is functionally meaningful.

This preserves the central scientific question: when does neuroplasticity translate into cognitive outcomes?

Future repositories may extend this framework using full longitudinal repeated-measures behavioural datasets.

## Methods

The repository used a lightweight and scalable workflow:

- Map candidate datasets and cognitive domains
- Profile network-cognition association signatures
- Quantify participant-level brain-behaviour relationships
- Cluster participants into cognitive response profiles
- Evaluate robustness using bootstrap and ranking analyses

## Main Findings

- Executive-control and salience networks showed the strongest cognitive associations
- Greater network reorganization was linked with higher cognitive performance
- Participants could be grouped into distinct cognitive response profiles
- Association rankings were stable under resampling
- Brain-behaviour correspondence can be modelled reproducibly in scalable workflows

## Repository Workflow

### Notebook 1 - Cognitive Dataset Landscape

Mapped candidate datasets and cognitive domains suitable for correspondence analyses.

### Notebook 2 - Network Cognition Signature

Profiled associations between major brain networks and cognitive domains.

### Notebook 3 - Brain Behaviour Association

Tested participant-level relationships between network change and cognition.

### Notebook 4 - Cognitive Profile Clustering

Clustered participants into distinct neural-cognitive response profiles.

### Notebook 5 - Brain Behaviour Reproducibility

Evaluated robustness of findings using confidence intervals and feature stability analyses.

## Limitations

- Proof-of-concept modelling rather than full raw cohort ingestion
- Network summaries rather than voxelwise inference
- Simplified behavioural representations for scalable demonstration
- Cross-sectional correspondence emphasis before full longitudinal modelling

## Future Directions

- Subject-level repeated-measures cognition analyses
- Symptom and well-being outcome coupling
- Dose-response cognitive trajectories
- Multi-session predictive modelling
- Cross-dataset meta-analytic correspondence synthesis

## Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Maintained By

Aditya Sundaray
