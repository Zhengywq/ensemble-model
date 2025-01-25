# User-Guided Interactive Machine Learning for High-Throughput, Multi-Scale Helium Bubble Segmentation and Quantification

## Overview

This project introduces a novel **User-Guided Interactive Machine Learning Framework** for high-throughput, multi-scale helium bubble segmentation and quantification. Combining advanced image processing techniques with deep learning, the framework leverages Mask R-CNN for semantic segmentation and incorporates GCM for refined analysis. This tool provides a scalable and customizable approach for helium bubble analysis, empowering researchers with precise, user-friendly, and interactive workflows.

---

## Key Features

- **Multi-Scale Segmentation:** Accurate detection and segmentation of helium bubbles across varying scales.
- **User-Guided Interactive Learning:** Incorporates user feedback for improved model performance and result customization.
- **Quantification Module:** Extracts geometric and morphological data from segmented images.
- **High-Throughput Analysis:** Processes large datasets efficiently, with support for batch processing.
- **Flexibility:** Easily configurable parameters for diverse datasets.

---

## Installation

Ensure you have Python 3.8+ and the following libraries installed:

### Core Libraries
```bash
pip install numpy pandas opencv-python-headless matplotlib imutils pillow

### Directory Structure
/kaggle
  ├── /input
  │   ├── /shottest
  │   │   ├── /image              # Input images
  │   │   ├── /labels/5-shot      # Corresponding annotations
  │   ├── /modelandsthnec         # Pretrained model files
  ├── /working
      ├── /saveoutput             # Directory for saving output
