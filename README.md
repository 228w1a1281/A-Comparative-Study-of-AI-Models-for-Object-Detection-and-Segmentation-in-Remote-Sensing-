# 🌍 A Comparative Study of AI Models for Object Detection and Segmentation in Remote Sensing

This repository contains a complete implementation and comparative analysis of **AI models for object detection and segmentation** using remote sensing imagery. 
---
## 📂 Repository Structure


A-Comparative-Study-of-AI-Models/
│── 📄 B-27-1-f.pptx # Project Presentation
│── 📄 Final Complete Report -B-27.pdf # Detailed Project Report
│── 📄 Buildings_comparision.ipynb # Major Project (Building Footprint Extraction)
│── 📄 Mini1.ipynb # Mini Project 1 (SAM Multi-class Segmentation)
│── 📄 Mini2 (1).ipynb # Mini Project 2 (Coconut Tree Analysis)
│── README.md


---

## 📌 Project Overview

This project focuses on comparing **Machine Learning, Deep Learning, and Foundation Models** for remote sensing applications.

### 🔹 Key Areas Covered
- Object Detection  
- Semantic Segmentation  
- Multi-class Segmentation  
- Comparative Model Analysis  

---

## 🧠 Models Used

- **U-Net** → Semantic Segmentation  
- **DeepLabV3+** → Advanced Segmentation  
- **RCNN** → Object Detection  
- **Random Forest** → Machine Learning Classification  
- **SAM (Segment Anything Model)** → Prompt-based Segmentation  

---

## 📊 Project Breakdown

### 1️⃣ Mini Project 1: Multi-Class Segmentation using SAM  
📄 `Mini1.ipynb`

- Uses SAM for multi-class segmentation  
- No training required (zero-shot learning)  
- Generates masks using prompts  

✅ **Output:** Multi-class segmented satellite images  

---

### 2️⃣ Mini Project 2: Coconut Tree Detection & Analysis  
📄 `Mini2 (1).ipynb`

- RCNN → Tree detection  
- U-Net & SAM → Segmentation  
- Comparative study for canopy extraction and analysis  

✅ **Output:**
- Detected coconut trees  
- Segmented canopy regions  

---

### 3️⃣ Major Project: Building Footprint Extraction  
📄 `Buildings_comparision.ipynb`

- Dataset: INRIA Aerial Image Dataset  
- Patch-based approach (256×256)  
- Total samples: ~3800 patches  

#### 🔹 Models Compared
- U-Net  
- DeepLabV3+  
- SAM  
- Random Forest  

#### 🔹 Workflow
- Preprocessing → Patch extraction  
- Model training → Prediction  
- Thresholding → Binary mask  
- Patch reconstruction → Full image  

✅ **Output:**
- Building footprint maps  
- Overlay visualizations  
- GIS-ready outputs  

---

## 📈 Evaluation Metrics

- Accuracy  
- IoU (Intersection over Union)  
- Precision  
- Recall  
- F1-score  

---

## ⚙️ How to Run

### ▶️ Open Notebooks
- Upload `.ipynb` files to **Google Colab** or open in Jupyter Notebook  

### ▶️ Install Required Libraries

pip install numpy pandas matplotlib opencv-python torch torchvision

▶️ Execute
Run all cells step-by-step
Update dataset paths if required
---
## 📽️ Project Presentation

📄 B-27-1-f.pptx

Includes:

- Problem Statement
- Methodology
- Implementation Workflow
- Results & Comparison
---

## 📄 Final Report

📄 Final Complete Report -B-27.pdf
Includes detailed explanation of:

- Algorithms
- System architecture
- Results analysis
- Conclusion & future work

**🎯 Applications** 
- Urban Planning (Building Detection)
- Smart Agriculture (Tree Analysis)
- GIS Mapping
- Environmental Monitoring

---
## 👩‍💻 Author

** Miss Dasapalli Pravallika ** 
Velagapudi Ramakrishna Siddhartha Engineering College
Vijayawada, India

## ⭐ Key Highlights
Comparative study of ML, DL, and Foundation Models
Real-world satellite image applications
End-to-end pipeline implementation
Includes notebooks, report, and presentation
