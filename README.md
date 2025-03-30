# Thermal_Ocular_Dataset

Antony Morales-Cervantes [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3669--2638-green)](https://orcid.org/0000-0003-3669-2638);  
Gerardo Marx Chávez-Campos [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3945--9903-green)](https://orcid.org/0000-0003-3945-9903);  
Ricardo Martínez-Parrales [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--4051--6434-green)](https://orcid.org/0000-0003-4051-6434);  
Sergio E. Hernández-Da Mota [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5882--3462-green)](https://orcid.org/0000-0001-5882-3462);  
Francisco Javier González [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1346--9073-green)](https://orcid.org/0000-0002-1346-9073);  
Edgar Guevara [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--2313--2810-green)](https://orcid.org/0000-0002-2313-2810)

This repository contains the thermographic ocular dataset used in the study titled **"Non-Invasive Evaluation of Ocular Diseases through Thermal Asymmetry Analysis and Machine Learning."** The dataset consists of thermal images captured from 39 patients with different ocular conditions, taken before and after pupil dilation, at specific intervals (0, 5, and 10 seconds) following eye opening.

## Contents

- **Dataset**: A collection of thermographic facial images organized by patient.
  
  - **Folder Structure**:
    - The root folder contains 39 folders named `paciente 1`, `paciente 2`, ..., `paciente 39`.
    - Each patient's folder contains two subfolders (when available): `antes de dilatar` and `despues de dilatar`.
    - Each of these subfolders contains infrared thermographic images (`.jpg`) taken at 0, 5, and 10 seconds after the patient opened their eyes.
    - An additional file named `content.txt` lists the image organization and acquisition timing.
    - A file named `Excel_clinico.xlsx` contains clinical metadata, including diagnosis per eye, demographics, medications, and comorbidities.

## Methodology

Thermal images were acquired using a FLIR thermal camera under controlled clinical conditions. Patients were instructed to close their eyes for 10 seconds and then open them while thermal images were captured at 0, 5, and 10 seconds. This process was repeated before and after pharmacological pupil dilation.

Each image was labeled and linked to its respective diagnosis by a certified ophthalmologist. These annotations were later used in machine learning models for classification of ocular diseases based on thermal asymmetry analysis.

## Purpose

This dataset supports research in infrared thermography applied to ocular diagnostics. It can be used to study:
- Thermal distribution and asymmetry in the periorbital region.
- Effects of pupil dilation on thermal signatures.
- Associations between thermal patterns and ocular diseases using machine learning.

## How to Use

1. **Clone the Repository**:  
2. Explore the Dataset:
Browse through the folders to analyze thermal images, and refer to Excel_clinico.xlsx for metadata and ocular diagnoses per eye.
3. Use the Data:
Integrate the thermograms and metadata for image processing, feature extraction, or training classification models as shown in the associated article.

## Data Availability Statement
The thermographic ocular dataset used for the study is openly available via GitHub:
https://github.com/morales-cervantes/Thermal_Ocular_Dataset

## Authors' Contributions
Antony Morales-Cervantes led the data collection. All authors contributed to data analysis and interpretation. All authors approved the final version of the manuscript for publication.
