# 🚗 VEHICLE-NUMBER-PLATE-DETECTION 🔍
> *AI-Powered Number Plate Recognition System for Indian Vehicles – with State Detection & OCR Magic!*

<p align="center">
  <img width="805" height="438" alt="image" src="https://github.com/user-attachments/assets/7875c8cc-4f94-460a-8efb-9132548766a8" />

 

</p>

---

## 💡 Overview

**VEHICLE-NUMBER-PLATE-DETECTION** is an AI-powered Flask web application that:
<img width="1706" height="846" alt="image" src="https://github.com/user-attachments/assets/8f65670d-f543-4aa8-ab69-763d81720390" />

✅ Detects **vehicle number plates** from images using **TensorFlow's SSD** model  
🧠 Extracts text using **EasyOCR**  
📍 Identifies the **Indian state** based on the license plate  
🌐 Provides a web interface ready to deploy on **Pivotal Cloud Foundry**  

All powered by machine learning & computer vision — like magic, but real!

---

## ⚙️ Tech Stack

| Component          | Technology Used                |
|--------------------|--------------------------------|
| Object Detection    | TensorFlow (SSD MobileNet)     |
| OCR                 | EasyOCR                        |
| Web Framework       | Flask                          |
| Image Processing    | OpenCV                         |
| Deployment Ready    | Pivotal Cloud Foundry          |
| Language            | Python                         |

---

## 🧠 AI in Action

| AI Feature         | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| 🎯 Object Detection | Detects number plates using SSD MobileNet                                  |
| ✍️ OCR             | Extracts alphanumeric text using deep learning (EasyOCR)                   |
| 🗺️ State Mapping   | Maps license prefix to Indian states (e.g., MH → Maharashtra)              |
| 🖥️ Flask UI       | Clean dashboard to upload and scan vehicle images                          |

---

## 📸 Image Dashboard Preview

> Here's what a real-time dashboard **could look like** in your implementation:

<p align="center">
  <img width="1049" height="526" alt="image" src="https://github.com/user-attachments/assets/0c0cb034-7356-41bd-bc3d-f3e7cd476095" />

  <br>

</p>

<p align="center">
 <img width="1143" height="689" alt="image" src="https://github.com/user-attachments/assets/f6d09181-75f3-4eb5-a058-0d9152e5b479" />
  <em>Image Source: indiamart.com</em>
</p>

---

## 🖼️ Input Requirements

- Minimum Image Size: **800x600 px** (for optimal accuracy)
- Supported Formats: `.PNG`, `.JPG`, `.JPEG`
- Clear view of the **front/rear** number plate

---

## 🚀 Getting Started

### 🔧 1. Clone the Repo

```bash

```
git clone https://github.com/yourusername/VEHICLE-NUMBER-PLATE-DETECTION.git
cd VEHICLE-NUMBER-PLATE-DETECTION


---
## 📦 2. Install Dependencies
pip install -r requirements.txt
---
## 🖥️ 3. Run the Web App
python app.py
Now open your browser and go to:
http://localhost:5000

💻 Demo Flow
1️⃣ Upload Vehicle Image
       ↓
2️⃣ Plate Detected via TensorFlow SSD
       ↓
3️⃣ OCR reads the Number Plate
       ↓
4️⃣ State Decoded from Prefix
       ↓
5️⃣ Results shown on Dashboard!

## 🛠 Folder Structure
📁 vehicle-number-plate-detection
│
├── app.py                  # Flask backend
├── static/                 # CSS, JS, image files
├── templates/              # HTML pages
├── model/                  # SSD model files
├── utils/                  # Helper functions
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

## 🌐 Deploy to Cloud
✅ Ready for Pivotal Cloud Foundry, Heroku, Render, or even Docker.
Just add your Procfile, manifest.yml, and you're good to go.

## 🔮 Future Enhancements
🎥 Real-time webcam feed support

🧑‍✈️ Challan generation for rule violation

🚗 Vehicle make/model prediction

🛰️ GPS integration for geo-tagging

📱 Mobile-friendly PWA version

## 🧪 Sample Output
Input Image	Plate Text	State
car1.jpg	MH12AB1234	Maharashtra
vehicle_2.jpg	DL05XZ3342	Delhi

## For queries, collaborations, or feedback, feel free to reach out:
📧 ajinkyaspatil2011@gmail.com




## From Snap to State – an AI-fueled number plate scanner that decodes India’s roads in real-time, with power and precision.
