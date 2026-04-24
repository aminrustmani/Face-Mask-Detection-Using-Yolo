# 😷 Face Mask Detection System (Real-Time)

## 📌 Overview

This project is a real-time **Face Mask Detection System** built using YOLOv8 and Streamlit. It detects whether people are wearing masks, not wearing masks, or wearing masks incorrectly in both images and videos.

The system is designed for applications like:

* Public health monitoring
* Smart surveillance systems
* Crowd compliance analysis

---

## 🚀 Features

* ✅ Image upload detection
* 🎥 Video upload detection
* ⚡ Real-time inference using YOLOv8
* 📊 High accuracy (trained model with ~0.99 mAP)
* 🖥️ Interactive web interface using Streamlit

---

## 🧠 Model Details

* Model: YOLOv8 (Ultralytics)
* Classes:

  * Mask
  * No Mask
  * Incorrect Mask
* Framework: PyTorch
* Export Options: `.pt`, `.onnx`, `.torchscript`

---

## 📁 Project Structure

```
Face-Mask-Detection/
│── app.py
│── best.pt
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run the App

```
streamlit run app.py
```

---

## 🌐 Deployment (Streamlit Cloud)

1. Push this project to GitHub
2. Go to Streamlit Community Cloud
3. Click **New App**
4. Select your repository
5. Set:

   * Main file: `app.py`
6. Click Deploy 🚀

---

## 📸 Demo

Upload an image or video to detect:

* 😷 Mask
* ❌ No Mask
* ⚠️ Incorrect Mask

---

## 💡 Future Improvements

* Live webcam detection
* Mask violation counter
* Alert system
* Dashboard analytics

---

## 👨‍💻 Author

Muhammad Amin

---

## 📜 License

This project is open-source and available for educational and commercial use.
