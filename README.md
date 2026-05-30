# AI Real-Time Audio & Video Gym Trainer 🏋️‍♀️🤖

An AI-powered fitness coaching system that uses real-time computer vision and audio feedback to guide users during workouts. The application analyzes body posture through webcam input, tracks exercise movements, counts repetitions, detects incorrect form, and provides intelligent voice-based coaching for a more interactive and engaging fitness experience.

## 🚀 Live Demo

🚀 Live Demo: https://ai-realtime-audio-video-gym-coach.streamlit.app/
🌐 Project Website: https://real-time-ai-gym.netlify.app/
💻 GitHub Repository: https://github.com/Inquisitive-shreya/AI-realtime-Gymcoach

---

# ✨ Features

* 🎥 Real-time exercise detection using webcam input
* 🧍 AI-powered posture and form correction
* 🔢 Automatic repetition counting
* 🔊 Intelligent audio-based workout feedback
* 🏋️ Multiple exercise support:

  * Push-ups
  * Squats
  * Lunges
  * Shoulder Press
  * Biceps Curl
* 📊 Workout tracking and session monitoring
* ⚡ Real-time pose landmark analysis
* 🖥️ Interactive Streamlit user interface
* 🧩 Modular detector architecture for scalability

---

# 🛠️ Tech Stack

## Frontend

* Streamlit
* HTML/CSS

## Backend / AI

* Python
* OpenCV
* MediaPipe
* NumPy
* Pandas

## Audio & Realtime Processing

* gTTS
* streamlit-webrtc
* WebRTC

---

# 🧠 How It Works

The application captures webcam input and processes body landmarks using MediaPipe Pose Estimation. Joint angles and movement patterns are analyzed in real time to detect exercise stages, count repetitions, and identify posture mistakes.

Based on workout events and movement analysis, the AI coach generates real-time audio feedback to guide users and improve exercise performance.

---

# 📂 Project Structure

```bash
AI-realtime-Gymcoach/
│
├── core/
├── detectors/
├── ml_models/
├── services/
│   ├── auth/
│   ├── coaching/
│   ├── config/
│   ├── persistence/
│   ├── state/
│   ├── tracking/
│   ├── ui/
│   └── vision/
│
├── static/
├── .streamlit/
├── main.py
├── requirements.txt
├── packages.txt
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Inquisitive-shreya/AI-realtime-Gymcoach.git
cd AI-realtime-Gymcoach
```

## 2️⃣ Create Virtual Environment

```bash
python -m venv .venv
```

## 3️⃣ Activate Environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / Mac

```bash
source .venv/bin/activate
```

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
streamlit run main.py
```

---

# 📌 Deployment Note

The realtime webcam version works best in a local environment. Due to WebRTC and browser/network limitations on cloud platforms like Streamlit Community Cloud, realtime webcam streaming may not work consistently for all users.

However, the core AI pose detection pipeline, exercise analysis system, posture tracking, and workout monitoring features function correctly.

---

# 🎯 Future Improvements

* Personalized AI workout recommendations
* Advanced workout analytics dashboard
* Voice command integration
* Multi-person exercise tracking
* Cloud database integration
* Mobile application support

---

# 👩‍💻 Developer

**Shreya Singh**
Final Year Computer Science Engineering Student
AI/ML & GenAI Enthusiast

---

# 📄 License

This project is licensed under the MIT License.
