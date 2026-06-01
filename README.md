# IndicOCR – Multi-Language Text Identification

A testing and evaluation repository for OCR-based text identification across English and Hindi scripts, developed under the guidance of **Dr. Anand Mishra**, Department of Computer Science & Engineering, IIT Jodhpur.

The Actual Repo link to the IndicPhoto OCR developed by Anand mishra and other teamates is given [here]([https://www.google.com](https://github.com/Bhashini-IITJ/IndicPhotoOCR))

## Overview

This project focuses on identifying and recognizing text from real-world images containing English and Hindi scripts using Optical Character Recognition (OCR) techniques. It includes a dataset of annotated images along with structured JSON outputs produced by the OCR pipeline.

## Repository Structure

```
IndicOCR_testing-master/
├── DC_Images/
│   └── Images/          # Input images (PNG/JPG) used for OCR testing
├── DC_jsons/
│   └── Jsons/           # Ground truth annotations with polygon coordinates,
│                        # recognized text, and script/language labels
└── Jsons_final/         # Final OCR output results per image
```

## Dataset

- **40 images** covering diverse real-world scenes with English and Hindi text
- Each image has a corresponding JSON annotation file containing:
  - Polygon bounding coordinates for each text region
  - Recognized text string
  - Script/language label (`English` / `Hindi`)

## Technologies

- **Language:** Python
- **Domain:** Image Processing, Optical Character Recognition (OCR)
- **Techniques:** Text region detection, script identification, preprocessing for improved recognition accuracy

## Key Contributions

- Worked on text identification for **English and Hindi** scripts using OCR techniques
- Implemented **image preprocessing** steps to improve recognition performance
- Structured OCR outputs into JSON format for evaluation and analysis

## Guide

**Dr. Anand Mishra**  
Department of Computer Science & Engineering  
Indian Institute of Technology Jodhpur (IITJ)
