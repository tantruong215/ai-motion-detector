# AI-Based Motion Detector

A smart motion detection camera that uses a quantized MobileNet SSD to identify human presence and ignore background movement.

---

### ⚙️ Hardware Design
- Raspberry Pi Zero + Pi Camera
- USB PIR sensor
- 5V regulated LiPo battery

---

### 🧠 Control/Software Features
- Run MobileNet inference via TensorFlow Lite
- Ignore false triggers (tree sway, shadows)
- Log image/video + alert via email

---

### 📊 Results (Expected)
- Detect human within 3 m
- <10% false positive rate
- Email + local storage on detection

---

### 🧰 Tools Used
- Python, OpenCV, TensorFlow Lite
- Flask or SMTP for alerts
- GitHub Actions for retraining

---

### 🚧 Project Status
🛠️ Status: In Progress – Summer 2025
