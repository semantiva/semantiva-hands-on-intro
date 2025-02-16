# Semantiva Hands-On Introduction

This repository contains a series of Jupyter notebooks designed to provide a **practical, step-by-step introduction** to Semantiva’s image processing capabilities. Unlike the main “image specialization” code repository, this repo is **exclusively** for documentation, tutorials, and hands-on examples. 

## Repository Overview

Each notebook focuses on a different aspect of Semantiva’s functionality, gradually guiding you from basic image operations to advanced model fitting. 

1. **[01_Basic_Image_Operations.ipynb](01_Basic_Image_Operations.ipynb)**
   - Set up your environment
   - View and save images in Jupyter
   - Simple image algorithms and basic probes

2. **[02_Context_Types_and_TypeBased_Design.ipynb](02_Context_Types_and_TypeBased_Design.ipynb)**
   - Introduces the concept of typed contexts and why they matter  
   - Explores type-based design fundamentals for structuring data and operations  
   - Provides best practices and troubleshooting tips


3. **[03_Building_a_Pipeline.ipynb](03_Building_a_Pipeline.ipynb)**
   - Introduce context operations (renamer, deleter)
   - Learn the pipeline architecture (AlgorithmNode, ProbeNode)
   - Execute and monitor pipelines (YAML configuration, inspection, timers)

4. **[04_DataCollections_and_ImageStacks.ipynb](04_DataCollections_and_ImageStacks.ipynb)**
   - Handle `DataCollection` objects (image stacks)
   - Adapt pipelines for multi-image workflows
   - Advanced probes and transformations

5. **[05_Advanced_Workflows_and_ModelFitting.ipynb](05_Advanced_Workflows_and_ModelFitting.ipynb)**
   - Parametric data generation (2D Gaussian generator)
   - Model fitting with `PolynomialFittingModel` and `ModelFittingContextOperation`
   - Build a multi-node pipeline for feature extraction and fitting


## Getting Started

1. **Clone the Repository**

   ```bash
   git clone git@github.com:semantiva/semantiva-hands-on-intro.git
   cd semantiva-hands-on-intro
   ```

## Usage Notes

- Each notebook is **self-contained**, meaning it has its own examples and references. Start with `01_Basic_Image_Operations.ipynb` if you’re completely new to Semantiva.
- The notebooks build on each other, but you can jump to later topics if you’re only interested in specific features (like multi-image stacks or advanced workflows).


---

**Happy exploring!** We hope these notebooks help you learn and innovate with Semantiva’s image processing tools.
