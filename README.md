# AI Driven Accident Detection System

AI-powered accident detection system using Python, OpenCV, and YOLOv4. This can be installed on roadside CCTV cameras for real-time monitoring. Sends instant alerts via Twilio API, enabling quick emergency response and enhancing road safety in smart city environments.

## 🚀 Features

-  Real-time detection of vehicles and persons using YOLOv4
-  Automatic accident detection based on bounding box overlap (proximity)
-  Alarm sound playback for alert
-  Optional phone call trigger via Twilio (configurable)
-  Image display for visual feedback
-  Webcam integration (compatible with Google Colab)


## 📦 Requirements

- Python 3.x
- OpenCV
- NumPy
- Twilio
- Google Colab (for webcam capture)

## Install dependencies:

```bash
pip install opencv-python-headless numpy twilio
```

## 📸 How It Works
1. Captures an image from webcam (Colab)

2. Detects persons and vehicles using YOLOv4

3. Analyzes proximity between bounding boxes

4. If close enough (overlapping), raises an accident alert

5. Plays an alarm sound

6. (Optional) Calls a phone number using Twilio API

## 🧠 Model Info
- Model: YOLOv4
- Dataset: COCO (Common Objects in Context)
- Classes Used: person, car, bus, truck, motorcycle

  
## 🤝 Contributing
Contributions are welcome! If you’d like to improve StudySphere, follow these steps:
1. **Fork the repository**
2. **Create a new branch:**
   ```bash
   git checkout -b feature-branch
   ```
3. **Make your changes and commit:**
   ```bash
   git commit -m "Add a new feature"
   ```
4. **Push to your fork and create a Pull Request**
   ```bash
   git push origin feature-branch
   ```


## 🎯 Connect with Me
For any queries or suggestions, feel free to reach out!
- **GitHub:** [@varshakaturu](https://github.com/varshakaturu)
- **LinkedIn:** [Varsha Katuru](https://linkedin.com/in/varshakaturu)
- **Email:** varshakaturu@gmail.com

---

✨ **Empowering safety through AI.** ✨
