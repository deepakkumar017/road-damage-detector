# 🚧 RoadScan AI — Road Damage Detection System

An AI-powered system that detects road damages like potholes and cracks from images or videos, classifies their severity, extracts GPS location, and generates detailed inspection reports.

---

## 📌 Project Overview

RoadScan AI is designed to help in:

* Smart city infrastructure monitoring
* Road maintenance automation
* Government inspection systems

The system uses **YOLOv8 (Deep Learning)** to detect road damages and provides a complete analysis pipeline.

---

## 🚀 Features

* 🔍 Detects road damages:

  * Potholes
  * Longitudinal Cracks
  * Transverse Cracks
  * Alligator Cracks

* 📊 Severity Classification:

  * LOW
  * MEDIUM
  * CRITICAL

* 📍 GPS Extraction from image metadata

* 📄 Automated PDF Report Generation

* 🌐 Web Dashboard (Flask-based)

* 🎥 Video Processing Support

---

## 🧠 Tech Stack

* **AI/ML:** YOLOv8, OpenCV
* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Libraries:** Pillow, ReportLab, NumPy, Pandas
* **Deployment:** Antigravity

---

## 📂 Project Structure

```
road-damage-detector/
│
├── data/
├── models/
├── static/
├── templates/
├── utils/
│
├── app.py
├── train.py
├── requirements.txt
```

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```
git clone https://github.com/yourusername/roadscan-ai.git
cd roadscan-ai
```

### 2. Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install Dependencies

```
pip install -r requirements.txt
```

### 4. Run Application

```
python app.py
```

---

## 📊 Dataset

* IEEE RDD2022 Dataset (India subset)
* Contains annotated images of road damages

---

## 🎯 Future Enhancements

* Real-time mobile app integration
* Live road scanning using CCTV
* Government API integration
* AI model optimization for edge devices

---

## 👨‍💻 Author

**Mohit Jangra**

* Full Stack Developer | AI Enthusiast
* GitHub: https://github.com/yourusername

---

## ⭐ Acknowledgment

* YOLOv8 by Ultralytics
* RDD2022 Dataset

---

## 📌 Status

🚧 Currently under development (Phase 1 Completed)
