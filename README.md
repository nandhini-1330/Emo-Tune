# **🎵 Emo-Tune**

Emo-Tune is a smart music recommendation system that detects a user's emotional state and recommends songs accordingly.
The system supports three independent modes of emotion input — **Text**, **Voice**, and **Face Detection (Camera)** — in addition to a **Quiz-based mode** for mood assessment.

## **📖 Overview**

Traditional music players require users to manually search or select playlists.
Emo-Tune removes this friction by analyzing the user's current emotional state and automatically curating song recommendations that match their mood, using whichever input method the user prefers.

## **✨ Features**

| Feature | Description |
|---|---|
| 📝 **Text-Based Detection** | Users describe their mood in natural language; the input is analyzed to classify emotion. |
| 🎙️ **Voice-Based Detection** | Speech is captured via microphone and processed to infer emotional tone. |
| 📷 **Facial Detection (Camera)** | Real-time webcam-based facial expression analysis to identify emotion. |
| 🧩 **Quiz Mode** | A structured, question-based alternative for mood assessment. |
| 🎧 **Emotion-Based Recommendations** | Curated song suggestions mapped to detected emotion categories (Happy, Sad, Angry, Neutral). |
| 🌐 **Language Selection** | Users can choose a preferred language before proceeding. |
| ⚡ **Lightweight Front-End Architecture** | Built entirely with HTML, CSS, and JavaScript; no backend server required to run. |

## **🗂️ Project Structure**

```text
Emo-Tune/
├── index.html          # Landing page
├── language.html       # Language selection
├── proj.html           # Input mode selection (Quiz / Text / Voice / Face)
├── quiz.html           # Quiz-based mood detection
├── emo.html            # Emotion detection interface
├── songs.html          # Song recommendation and playback
├── emo.mp4             # Face detection demo video
├── happy.mp3            # Sample track - Happy
├── sad.mp3               # Sample track - Sad
├── angry.mp3              # Sample track - Angry
└── neutral.mp3             # Sample track - Neutral
```



