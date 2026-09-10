# Explainable AI for Diabetic Retinopathy Screening in Rural India

**SIH26038 | MathWorks Problem Statement**

A MATLAB-based Explainable AI pipeline for automated Diabetic Retinopathy (DR) screening, designed for rural Primary Healthcare Centres in India.

---

## Project Overview

India has one of the highest numbers of diabetic patients in the world. Diabetic Retinopathy is a leading cause of preventable blindness. Early detection can prevent up to 90% of vision loss, but rural areas face a severe shortage of ophthalmologists.

This project develops a complete **Explainable AI screening system** that:
- Checks image quality
- Enhances the fundus image
- Classifies DR severity (5 classes)
- Provides visual explanation using Grad-CAM
- Supports a simple web interface for screening

---

## Key Features

- **Image Quality Assessment** (Blur + Illumination)
- **CLAHE Enhancement**
- **EfficientNet-B0 Classification** (Transfer Learning)
- **Grad-CAM Explainability**
- **Streamlit Web Interface**
- **Patient History Tracking**
- **Telemedicine Workflow Simulation**

---

## Results

| Metric                          | Value     |
|--------------------------------|-----------|
| Validation Accuracy            | 91.27%    |
| Referable DR Sensitivity       | 96.31%    |
| Referable DR Specificity      | 96.55%    |

**Referable DR** = Moderate + Severe + Proliferative DR

---

## Dataset

- **APTOS 2019** (Resized 224×224 version)
- 5 Classes: No_DR, Mild, Moderate, Severe, Proliferate_DR

---

## Tech Stack

| Component               | Technology                  |
|------------------------|-----------------------------|
| Deep Learning          | MATLAB Deep Learning Toolbox |
| Image Processing       | MATLAB Image Processing Toolbox |
| Model                  | EfficientNet-B0             |
| Explainability         | Grad-CAM                    |
| Frontend               | Streamlit (Python)          |
| Simulation             | MATLAB Script               |

---

## Project Structure
