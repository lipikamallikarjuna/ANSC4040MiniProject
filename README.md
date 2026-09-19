## Missing RFID Cow Identification - ANSC 6060 (Grad Student) Mini Project

## Project Overview

This project aims to use existing farm data to identify the most likely cow IDs for records with missing RFID information. The goal is to restore the ability to link these records with existing information such as milk yield, pregnancy, reproduction, and other relevant cow-level data.The project will focus on developing a reproducible and responsible data-analysis/modeling workflow while maintaining confidentiality and appropriate use of sensitive on-farm information.

## Project Goals

* Identify records with missing RFID IDs
* Explore existing variables and methodologies that can be used for cow identification
* Develop and evaluate a data-linkage/modeling approach
* Identify the most likely cow ID for missing RFID records
* Evaluate prediction accuracy and uncertainty
* Document the complete workflow for reproducibility
* Follow best practices such as right naming conventions, documentation etc.
* Present the results and limitations in a final poster

## Data & Ethics

This project will follow:

* **Confidentiality** of farm and animal-level information
* **Ethical data practices**
* **FAIR principles** — Findable, Accessible, Interoperable, and Reusable
* Responsible handling and reporting of model-derived cow identities

Raw confidential farm data will **not** be uploaded to the public GitHub repository.

## Reproducibility

The project will document the data-processing, feature engineering, modeling, evaluation, and visualization workflow. Code, notebooks, metadata, and non-sensitive outputs will be organized so the workflow can be reproduced by users with access to the required data.

## Repository Organization

The GitHub repository will contain:

* `README.md` — Project description, workflow, timeline, and documentation
* `LICENSE` — License for publicly available project materials
* `.gitignore` — Prevents confidential/unnecessary files from being uploaded such as the farm dataset
* `notebooks/` — Analysis and modeling notebooks
* `data/` — Data documentation and, but not publicly shared
* `results/` — Non-confidential results and figures
* `poster/` — Final poster materials

## Naming Convention

A consistent **PascalCase naming convention** will be used for project files and relevant variables. Numbered notebooks will be used to indicate the order of the workflow.

## Project Timeline

| Week      | Task                                                     | Deliverable         |
| --------- | -------------------------------------------------------- | ------------------- |
| **1**     | Setup, repo, data inspection, timeline, brainstorm       | Project plan        |
| **2**     | Data exploration, cleaning and understanding             | Data exploration    |
| **2**     | Identification of missing RFID records                   | Preprocessed data   |
| **2**     | Feature exploration and engineering                      | Candidate features  |
| **3**     | Model development                                        | Initial model       |
| **3**     | Model evaluation and final analysis                      | Evaluation results  |
| **4**     | Poster preparation & Presentation                        | Poster presentation |
| Throughout| GitHub organization and reproducibility documentation    | Complete repository |

## Project Setup details: 

* The project will be executed using VS code as an IDE and use of AI to assist with the codes.
* Model Choice:

## Final Deliverables

* Organized public GitHub repository
* README
* LICENSE
* `.gitignore`
* Data/metadata documentation & Naming Conventions
* Analysis and modeling notebooks
* Reproducible workflow
* Model results and evaluation
* Final poster presentation

