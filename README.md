![TLP Level Badge](https://img.shields.io/badge/TLP-WHITE-white)

# iAM.AMR Model and Module Directory

This repository contains links and download instructions for the iAM.AMR models. 


## Contents

- [iAM.AMR Model and Module Directory](#iamamr-model-and-module-directory)
  - [Contents](#contents)
  - [About](#about)
- [Directory](#directory)
  - [Story Models](#story-models)
    - [iAM.AMR.3GC](#iamamr3gc)
    - [iAM.AMR.CHI](#iamamrchi)
    - [iAM.AMR.FQC](#iamamrfqc)
    - [iAM.AMR.PIG](#iamamrpig)
  - [Other Models and Modules](#other-models-and-modules)
    - [The Hub Module](#the-hub-module)
    - [The Swine Weaner Prevalence Module](#the-swine-weaner-prevalence-module)
    - [iAM.AMR.FREE Model](#iamamrfree-model)
- [Conventions](#conventions)
- [Get and Run a Story Model](#get-and-run-a-story-model)
- [More Resources](#more-resources)


## About

Each iAM.AMR model is referred to as a *story*, and represents a specific drug-microbe-commodity combination. Each of these *story models* are connected to a central *Hub module* (and various other modules) to provide data in a plug-and-play fashion.

A copy of the [iAM.AMR.HUB](https://goto.iam.amr.pub/repo-hub) module **is required to run the iAM.AMR story models**.



# Directory

## Story Models

### [iAM.AMR.3GC](https://github.com/iAM-AMR/iAM.AMR.MODEL_3GC)

![badge-story](https://img.shields.io/badge/model-story-green) ![badge-forerunner](https://img.shields.io/badge/model-forerunner-blue)

A model exploring third-generation cephalosporin resistance across all animal species.


### [iAM.AMR.CHI](https://github.com/iAM-AMR/iAM.AMR.MODEL_CHI)

![badge-story](https://img.shields.io/badge/model-story-green) ![badge-forerunner](https://img.shields.io/badge/model-forerunner-blue)

A model exploring resistance to all antimicrobials and pathogens in chickens.


### [iAM.AMR.FQC](https://github.com/iAM-AMR/iAM.AMR.MODEL_FQC)

![badge-story](https://img.shields.io/badge/model-story-green) ![badge-forerunner](https://img.shields.io/badge/model-forerunner-blue)

A model exploring resistance to fluoroquinolones for Campylobacter in swine and cattle.


### [iAM.AMR.PIG](https://github.com/iAM-AMR/iAM.AMR.MODEL_PIG)

![badge-story](https://img.shields.io/badge/model-story-green)

A model exploring pigs.



## Other Models and Modules

### [The Hub Module](https://goto.iam.amr.pub/repo-hub)

![badge-module](https://img.shields.io/badge/module-core-red)

See the [documentation](https://goto.iam.amr.pub/docs_model_framework) for more details.

### [The Swine Weaner Prevalence Module](https://github.com/iAM-AMR/iAM.AMR.MOD_swine_weaner_prev)

![badge-module](https://img.shields.io/badge/module-data-orange)

Data including the prevalence of resistance at early stages in swine production.

### [iAM.AMR.FREE Model](https://github.com/iAM-AMR/iAM.AMR.MODEL_FREE)

![badge-story](https://img.shields.io/badge/model-story-green) ![badge-forerunner](https://img.shields.io/badge/model-forerunner-blue)

The *Free Edition* models is maintained by [@chapb](https://goto.amr.pub/chapb), and is the reference for core model implementation.



# Conventions

![Model Status](assets/model_status.png)

Generally, *story models* are named `iAM.AMR.XYZ` (and stored in a `iAM.AMR.MODEL_XYZ` repository), where `XYZ` is a string of three to four characters that uniquely describe the model. See the [relevant documentation](https://goto.iam.amr.pub/docs_model_framework) for more details.



# Get and Run a Story Model

1. Locate the story model repository (see directory above) 
1. If a *release* is provided follow the link to download the release as a ZIP
   - *check under the *release* heading on the right-hand side of the page* 
1. If no *release* is provided, use the green *code button* to download the current main-branch commit as a ZIP
1. Repeat steps 2 & 3 for the [Hub module](https://goto.iam.amr.pub/repo-hub)
1. Unzip the files in the same directory, and open the story model to begin
   - *if prompted (if you have unzipped the repositories to different directories), browse locate the Hub module*
1. Evaluate the main *Output node* to run the entire model in its default state



# More Resources

- [GitHub Download Instructions](https://goto.iam.amr.pub/gh-start-here-github)
- [Documentation](https://goto.iam.amr.pub/docs)

If none of these resources address your question, feel free to contact [@chapb](https://goto.amr.pub/chapb).

