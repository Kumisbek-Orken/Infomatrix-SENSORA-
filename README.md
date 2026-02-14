# SENSORA+ 🛡️
**A Lightweight, Unified Offline AI Ecosystem for Sensory Accessibility**

SENSORA+ is an intelligent assistive platform engineered to empower individuals with visual, hearing, and speech impairments. The project focuses on high-performance, **offline-first** processing, ensuring that life-changing technology is accessible on standard hardware without relying on cloud services or internet connectivity.

---

## 🌟 Core Modules

The ecosystem integrates three specialized AI-driven modes into a single, seamless interface:

1.  **Blind Mode (Visual Assistance):**
    * **Real-time Object Detection:** Powered by an optimized **YOLOv8** architecture.
    * **Spatial Awareness:** Calculates object coordinates and proximity to the user.
    * **Audio Feedback:** Converts environmental data into instant voice commands.

2.  **Deaf Mode (Auditory Assistance):**
    * **Offline ASR:** Real-time speech-to-text transcription using local speech recognition engines.
    * **Noise Filtration:** High-accuracy processing in public or noisy environments.
    * **Visual Dialogue:** Allows users to "read" conversations instantly on-screen.

3.  **Mute Mode (Speech Assistance):**
    * **Geometric Gesture Recognition:** Translates sign language/gestures into text and speech.
    * **Optimized Algorithm:** Utilizes **OpenCV** with **Convexity Defects** and **Hull analysis**.
    * **Zero-Latency:** Mathematically optimized to run at high FPS even on low-end CPUs.

---

## 🛠️ Technical Stack

* **Language:** Python 3.9+
* **Computer Vision:** OpenCV, Ultralytics YOLOv8
* **Data Processing:** NumPy (Geometric calculations)
* **Speech Engines:** Vosk / SpeechRecognition (Offline implementations)
* **Target Hardware:** Standard Laptop/PC CPU (Optimized for inference without GPU)

---

## 🚀 Key Advantages

* **Independence:** Works 100% offline, making it reliable in remote areas or locations with poor connectivity.
* **Privacy:** All data is processed locally; no audio or video is ever uploaded to the cloud.
* **Efficiency:** Bridges the gap between heavy AI models and standard hardware through rigorous code optimization.
* **Scientific Foundation:** Built upon the synthesis of extensive academic research and dissertations on computer vision.

---

## 📋 Installation & Usage

1. **Clone the repository:**
   git clone [https://github.com/your-username/sensora-plus.git](https://github.com/your-username/sensora-plus.git)

Install dependencies:

pip install -r requirements.txt
Run the application:

python main.py
