# IndicOCR – Multi-Lingual OCR Evaluation Dataset

A benchmark and evaluation repository for Optical Character Recognition (OCR) on English and Hindi text, developed under the guidance of Dr. Anand Mishra, Department of Computer Science & Engineering, Indian Institute of Technology Jodhpur (IITJ).

## Project Overview

IndicOCR is designed to evaluate OCR systems on real-world images containing both English and Hindi scripts. The repository provides a curated dataset of annotated images along with structured JSON annotations and OCR outputs, enabling systematic assessment of text detection, recognition, and script identification performance.

The project serves as a resource for researchers and developers working in document analysis, scene text recognition, multilingual OCR, and computer vision.

## Related Project

The primary OCR framework used for generating and evaluating results is IndicPhotoOCR, developed by Dr. Anand Mishra and collaborators.

Repository: https://github.com/Bhashini-IITJ/IndicPhotoOCR

---

## Repository Structure

text IndicOCR_testing-master/ 
├── DC_Images/ │   └── Images/              # Input images used for OCR evaluation │ 
├── DC_jsons/ │   └── Jsons/               # Ground-truth annotations │                             # - Polygon coordinates │                             # - Text transcripts │                             # - Language labels 
│ └── Jsons_final/             # OCR-generated output results 

## Dataset Description

The dataset consists of:

- 40 annotated images containing English and Hindi text
- Real-world scene images with diverse layouts and text styles
- Ground-truth JSON annotations for each image
- OCR-generated output files for performance comparison

Each annotation includes:

- Polygon-based text region coordinates
- Recognized text content
- Script/language labels (English or Hindi)

## Features

- Multi-language OCR evaluation
- English and Hindi script identification
- Structured annotation format for benchmarking
- Real-world scene text dataset
- OCR output comparison and analysis

## Technologies Used

- Python
- Computer Vision
- Optical Character Recognition (OCR)
- Image Processing
- Text Detection and Recognition
- Script Identification

## Contributions

Key contributions of this work include:

- Evaluation of OCR performance on English and Hindi scripts
- Development of structured annotation datasets for benchmarking
- Image preprocessing techniques to improve recognition accuracy
- Generation and organization of OCR outputs in JSON format
- Support for multilingual text recognition research

## Research Guidance

Dr. Anand Mishra  
Professor, Department of Computer Science & Engineering  
Indian Institute of Technology Jodhpur (IITJ)

## Acknowledgements

This repository is developed for research and evaluation purposes and builds upon the IndicPhotoOCR framework developed by the IIT Jodhpur research team.
