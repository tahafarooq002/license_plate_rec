# License Plate Recognition (LPR) System

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Jupyter%20Notebook-orange)

A complete **Automatic License Plate Recognition (ALPR)** system built using **Python, OpenCV, and OCR**.  
This project detects license plates, extracts them, preprocesses them, and reads characters using OCR.

---

## 🚀 Features
- 🔍 **License Plate Detection** (contours or deep learning)
- 🧹 **Preprocessing Pipeline** (grayscale, thresholding, noise removal)
- 🔠 **OCR Recognition** using Tesseract
- 📊 **Result Visualization**
- 📓 Fully implemented in: **`license_plate_rec.ipynb`**

---

## 🛠️ Technologies Used
| Tool | Purpose |
|------|---------|
| **Python** | Main language |
| **OpenCV** | Image processing & detection |
| **Pytesseract** | Text recognition |
| **NumPy** | Computation |
| **Matplotlib** | Plotting |
| **Jupyter Notebook** | Development |

---

## 📁 Project Structure
license_plate_recognition/
│
├── license_plate_rec.ipynb # Main notebook
├── requirements.txt # Dependencies
├── README.md # Documentation
├── .gitignore # Git ignores
├── LICENSE # MIT License
└── assets/
├── sample_input.jpg # Optional demo image
└── sample_output.jpg # Optional result preview


---

## ▶️ How to Run

### **1️⃣ Install dependencies**
```bash
pip install -r requirements.txt
```
### **2️⃣ Open the notebook
```bash
jupyter notebook license_plate_rec.ipynb
```

### **3️⃣ Run cells

Upload an image → process → recognize → output text.


### **  Example Pipeline

Load image

Detect plate

Crop plate

Preprocess

OCR text extraction

Show results

### **  Future Improvements

Deep learning plate detection (YOLOv8 / RCNN)

Custom OCR training

Multi-region (US, EU, India, etc.)

Video stream real-time recognition

Add unit tests (PyTest)

Add CI workflow (GitHub Actions)

