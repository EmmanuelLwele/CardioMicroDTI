# 🫀 CardioMicroDTI

Clinical-grade platform for microstructural risk stratification in aortic stenosis using cardiac diffusion tensor imaging (cDTI).

---

## 🚀 Overview

CardioMicroDTI is a decision support tool that integrates:

- Diffusion MRI (cDTI)
- Myocardial microstructure analysis
- Biomechanical modeling
- AI-based risk stratification

to support surgical timing in aortic stenosis.

---

## 🧠 Features

- cDTI tensor reconstruction (FA, MD, fiber orientation)
- LV segmentation and AHA 17-segment mapping
- Microstructural Integrity Score
- Risk stratification dashboard
- Clinical report generation

---

## 🏗 Architecture

MRI → DICOM → Processing Pipeline → Risk Model → Clinical Dashboard

---

## 📂 Project Structure

See `/src`, `/notebooks`, and `/app` for implementation.

---

## 📊 Dataset

Due to data privacy, full datasets are not included.

Sample processed data is available in `/data/sample/`.

External datasets:
- Cardiac Atlas Project
- MRXCAT phantom
- Ex vivo DTI datasets

---

## ⚙️ Installation

```bash
git clone https://github.com/yourname/CardioMicroDTI.git
cd CardioMicroDTI
pip install -r requirements.txt
