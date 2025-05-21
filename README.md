# 🔊 Dangerous Sound Detection using Deep Learning

This project focuses on detecting dangerous and emergency sounds using deep learning models such as CNN, RNN, CRNN, and VGG19. Audio clips are transformed into STFT or Mel spectrograms and passed through trained models to classify 13 types of dangerous events.

---

## 🎯 Project Objective

To develop a real-time or batch-processing system that can classify potentially hazardous sounds (e.g., gunshots, explosions, alarms) using acoustic features and deep learning, aiding applications in public safety and UAV-based surveillance.


---

## 🔍 Detected Sound Classes

The system can classify the following 13 sound types:

- Gun Shots
- Explosion
- Emergency Alarm
- Fire
- Wildfire
- Screaming
- Dog Bark
- Car Horn
- Glass Breaking
- Siren
- Thunder
- Wind
- Tsunami

---

## 🧠 Models Trained

| Model       | Input Type | Accuracy |
|-------------|------------|----------|
| CNN         | STFT       | 91.56%   |
| CNN         | Mel        | 87.86%   |
| RNN         | STFT       | 71.35%   |
| RNN         | Mel        | 71.95%   |
| CRNN        | STFT       | 87.04%   |
| CRNN        | Mel        | 85.64%   |
| VGG19       | STFT       | 83.86%   |
| VGG19       | Mel        | 81.35%   |

---

## 🛠️ Tech Stack

- Python, NumPy, TensorFlow/Keras
- Librosa (audio preprocessing)
- Matplotlib (spectrogram visualization)
- Streamlit (web app deployment)
- OpenCV / PIL (image handling)

---

 For a complete list of references, technical methodology, and experimental results, please refer to the full paper.

