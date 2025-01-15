# Image Registration

## Overview
The primary aim of the project is to design, implement, and analyze algorithms for 3D object registration, with a focus on accuracy and efficiency. This project emphasizes the registration of medical images, which are crucial in diagnostics and treatment, especially for detecting diseases and identifying cancerous changes.

## Expected Outcomes
- Development of algorithms for 3D object registration, encompassing both linear and nonlinear methods.
- Performance analysis in various conditions, particularly for large and irregular datasets, such as microscopic images.

## Problem Scope
3D image registration aligns two or more images of the same scene to enhance analysis. It has broad applications, including:

- medicine: registering images from different modalities such as MRI, CT, PET, and ultrasound to achieve comprehensive visualization of organs.
- geodesy: analyzing terrain changes based on satellite imagery.
- astronomy: comparing images of the sky taken at different time intervals.

## Methodology
The project leverages both linear transformations (e.g., translations, rotations, scaling) and nonlinear transformations (e.g., free-form deformations). Key methods include:
Linear Methods
- Rigid transformations (Rigid Registration, Euler Transform).
- Affine transformations (Affine Registration).
- Scaling and translations (Similarity Transform, Translation Transform).
  
Nonlinear Methods
- Free-form deformations (FFD, Multilevel FFD).
- Elastic registrations for local deformations.

## Requirements
- Python 3.8 or newer
- [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

## Installation and Setup

To set up the environment needed to run the project, follow the steps below:

### 1. Clone the Repository
First, clone this repository:
```bash
git clone <git repository url>
cd repo-name
```
### 2. Create Environment from environment.yml
Use Conda to create the environment from the environment.yml file:
```bash
Skopiuj kod
conda env create -f environment.yml
```
### 3. Activate the Environment
Activate the created environment:
```bash
Skopiuj kod
conda activate sitkpy
```
Note: The environment name is specified in the environment.yml file. It is usually found in the name: section of the file header.

### 4. Run the Project
After activating the environment, you can run the project. Navigate to the Notebook section to find Jupyter Notebook files, which can be used to test the implemented methods.
