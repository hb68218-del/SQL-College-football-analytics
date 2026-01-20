---
title: "Technical Research Contribution"
subtitle: "Large Scale Document Processing and Data Preparation"
author: "Haeun (Sally) Bae"
date: "`r Sys.Date()`"
output:
  html_document:
    toc: false
    number_sections: false
---

# Technical Research Contribution

**Independent Research Support Project**  
**Haeun (Sally) Bae**

---

## Project Objective

The objective of this work was to design and implement a scalable technical pipeline to process large volumes of unstructured document data for academic research use. The focus was on building reliable, automated methods for text cleaning, document segmentation, metadata extraction, and data validation to support downstream analysis conducted by the research team.

This contribution emphasizes data engineering, automation, and reproducible research practices rather than substantive research findings.

---

## Technical Process Overview

### Data Ingestion and File Handling

I worked with large scale document exports stored in batch file formats. Raw files were preserved in their original form, and automated directory traversal was implemented to enable scalable processing across hundreds of documents.

Key technical focus areas:
- Batch file handling
- File system automation
- Traceability of raw inputs

---

### Text Conversion and Normalization

Unstructured documents were programmatically converted into plain text to enable reliable parsing. Cleaning steps were applied to remove formatting artifacts, normalize whitespace, and standardize character encoding.

Key technical focus areas:
- Text normalization
- Encoding cleanup
- Preprocessing for structured parsing

---

### Document Segmentation

Many source files contained multiple documents bundled together. I implemented logic to identify document boundaries and split batch files into individual article level records, ensuring one document per observation.

Key technical focus areas:
- Pattern based document segmentation
- Consistent record structuring
- Error handling for edge cases

---

### Metadata Extraction

I developed structured parsing logic to extract consistent metadata fields from each document, including identifiers, publication details, source information, and full text. Fallback rules were applied to reduce missing values and improve robustness.

Key technical focus areas:
- Regular expression based parsing
- Structured metadata design
- Validation of extracted fields

---

### Keyword Detection and Flagging

To support efficient document review, I implemented keyword based detection across full document text. This produced keyword hit counts and categorical indicators that assist with filtering and prioritization.

Key technical focus areas:
- Configurable keyword frameworks
- Automated text scanning
- Feature generation for analysis readiness

---

## What I Built

- A Python based document processing pipeline  
- Automated workflows for cleaning and structuring unstructured text  
- Metadata extraction logic using pattern matching techniques  
- Keyword detection mechanisms to support large scale review  
- Validation checks to ensure consistent and reproducible outputs  

---

## Technical Skills Demonstrated

- Python scripting and automation  
- Text processing and regular expressions  
- Data cleaning and preprocessing  
- Pipeline design for unstructured data  
- Reproducible research workflows  
- Data validation and quality control  

---

## Outcome and Impact

The technical pipeline successfully transformed large scale unstructured document exports into clean, structured datasets suitable for academic research workflows. The reliability, scalability, and clarity of the technical implementation contributed to the project’s selection for presentation at the **Terry College of Business Annual Stakeholder Research Meeting**, where the focus was on methodology and technical approach rather than research findings.

