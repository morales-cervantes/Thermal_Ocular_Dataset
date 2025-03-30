# Thermal_Ocular_Dataset

Antony Morales-Cervantes [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3669--2638-green)](https://orcid.org/0000-0003-3669-2638); Gerardo Marx Chávez-Campos [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3945--9903-green)](https://orcid.org/0000-0003-3945-9903); Ricardo Martínez-Parrales [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--4051--6434-green)](https://orcid.org/0000-0003-4051-6434); Sergio E. Hernández-Da Mota [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5882--3462-green)](https://orcid.org/0000-0001-5882-3462); Francisco Javier González [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1346--9073-green)](https://orcid.org/0000-0002-1346-9073); Edgar Guevara [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--2313--2810-green)](https://orcid.org/0000-0002-2313-2810)

This repository contains a curated dataset of **infrared thermographic images of the human eye** captured from 39 patients, before and after pharmacological pupil dilation. These thermal images were used in the research article titled:  
**“Non-Invasive Evaluation of Ocular Diseases through Thermal Asymmetry Analysis and Machine Learning”**.


## Contents

The dataset is structured as follows:

- Each folder is named as `paciente N`, where `N` is the patient number (from 1 to 39).
- Inside each folder, there are subfolders:
  - `antes de dilatar`: Thermal images taken **before** dilation.
  - `despues de dilatar`: Thermal images taken **after** dilation.
- Each subfolder contains 6 to 8 thermographic images (`.jpg` format) labeled with acquisition timestamps representing **0s, 5s, and 10s** after eye opening.

Excel file contains detailed diagnostic annotations **per eye** from a certified ophthalmologist, including:

- Sex, age, medical history (diabetes, hypertension, etc.)
- Pathologies per eye (e.g., cataracts, diabetic retinopathy, AMD)
- Medication, physical activity, cosmetic use

## Methodology

Thermal images were acquired using a FLIR thermal camera under controlled clinical conditions. Patients were instructed to close their eyes for 10 seconds and then open them while thermal images were captured at 0, 5, and 10 seconds. This process was repeated before and after pharmacological pupil dilation.

Each image was labeled and linked to its respective diagnosis by a certified ophthalmologist. These annotations were later used in machine learning models for classification of ocular diseases based on thermal asymmetry analysis.

## Purpose

This dataset supports research in infrared thermography applied to ocular diagnostics. It can be used to study:
- Thermal distribution and asymmetry in the periorbital region.
- Effects of pupil dilation on thermal signatures.
- Associations between thermal patterns and ocular diseases using machine learning.

## How to Use

1. Clone the repository or download the ZIP:
   ```bash
   git clone https://github.com/morales-cervantes/Thermal_Ocular_Dataset.git 
2. Explore the Dataset:
Browse through the folders to analyze thermal images, and refer to data_information.xlsx for metadata and ocular diagnoses per eye.
3. Use the Data:
Integrate the thermograms and metadata with your own scripts or thermal analysis pipelines, or training classification models as shown in the associated article.

## Data Availability Statement
The thermographic ocular dataset used for the study is openly available via GitHub:
https://github.com/morales-cervantes/Thermal_Ocular_Dataset

## Authors' Contributions
Antony Morales-Cervantes led the data collection. All authors contributed to data analysis and interpretation. All authors approved the final version of the manuscript for publication.
