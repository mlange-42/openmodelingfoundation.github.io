---
title: Documentation
linkTitle: Documentation
cascade:
  type: docs
  github_issue_filter: "label:\"standards - documentation\""
  github_issue_template: documentation.md
  github_discuss_category: "documentation-standards"
weight: 2
---

{{% standards-preamble %}}
These standards promote documentation needed for others to understand a model and reproduce its results.
{{% /standards-preamble %}}

## Overview of Documentation Standards

## Goals for Documentation Standards

Documentation of a model, together with the provided model code, needs to facilitate the understanding of the intentions of the developer, and make the model easier to test, use, and link to other models. It should also describe assumptions made about phenomena being modeled and what information is used to create and test the model.

We suggest three main categories of documentation:
- Metadata
- Methods and theoretical foundation
- Implementation

## Minimal Documentation Standards

### Overview
- "1-pager"
- Purpose
- Summary of structure
- Processes modeled

### General Metadata
- Name and version of the model
- Model project page (organizational website or repository, if available)
- Description of the model, including its purpose or goals and the type or formalism of the model (e.g., system dynamic, agent based model, machine learning), preferably accompanied by relevant keywords
- Name(s) and contact information of the developer(s)/author(s)
- Date of release
- [OSI-approved license](https://opensource.org/licenses)
- [How to cite the software](https://www.force11.org/software-citation-principles)
- Location where the model is posted or published (e.g. PID or DOI)
- Computer language or platform used for programming
- Software and/or hardware requirements needed to run the model and replicate any published results
- All data dependencies needed to run the model and replicate any published results
- Information on how to install the model so that it can be run (e.g., compilation and/or execution instructions)
- Use cases: References to reports or publications where the model is used
- Changes since the last version (if the model is an update) including bug fixes, new features, or other substantive modifications, where appropriate.
- [Harmonization with schema.org and codemeta metadata vocabularies](https://codemeta.github.io/)
- Development status (e.g., experimental, deployed, peer-reviewed, ...)
- Funding sources

### Sample applications
- Get-started guide
- Use case narratives
- link to publications overview (automated, ideally)

### Model Documentation: Methods and theoretical foundation
- Assumptions: What are the key assumptions made that define the dynamics of the model?
- Model structure: provide a flow diagram of the model.
- Equations and rules: What are the equations of the model? What are agents' precise behavioral rules (e.g. represented as a decision tree)?
- Temporal resolution, time stepping, and units 
- Spatial dimensionality, resolution, extent, grid type if relevant
- Limitations, domain ranges: What is this model specifically NOT intended to do.
- Links to open access resources

### Implementation 

#### Interface: Input/Output and Variables 
- Key input parameters and their values and domain ranges and units (minimum input requirements for model operation and default values, where appropriate) 
- Initial conditions  
- Forcing functions that affect the dynamics of the model.  
- Control variables  
- Key output variables and domain ranges
- Provide sample runs that illustrate the dynamics of the model.

#### Validating installation
- Provide sample input and output files, including run script, such as a cookbook or benchmark

#### Model evaluation, uncertainty, and sensitivity
- Provide data used for calibration and evaluation of the model, if data are public. 
- Describe how calibration and evaluation to verify the accuracy of the model were performed. 
- List of publications on evaluation, uncertainty, sensitivity analyses for your model
- Describe or provide benchmarks for validation of your model
- Links to open access resources

## Ideal Documentation Standards
- [ODD Protocol for Describing Agent-Based and Other Simulation Models](http://jasss.soc.surrey.ac.uk/23/2/7.html)

## Cyberinfrastructure and Tools for Implementation of Documentation Standards
- Cross-links between documentation sections
- Bibliographic documentation / management system (e.g., Mendeley links)
- Tagged content management system entry form (linkage between sections)

## Examples and References for Documentation
- TBD


