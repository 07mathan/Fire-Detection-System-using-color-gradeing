
**Fire Detection System**

A Python-based computer vision application designed to detect fire in video streams in real-time. This system processes video frames, identifies fire characteristics, triggers a localized audible alarm, and sends automated email alerts for instant notification.

🚀 Features

* **Real-Time Video Processing:** Analyzes video files or live camera streams to detect visual signs of fire.
* **Audible Alerts:** Automatically plays a fire alarm sound (`.mp3`) when a fire is detected.
* **Email Notifications:** Sends an automated email alert (via `test_email.py`) to notify emergency contacts or administrators instantly.
* **Dual Mode:** Comes with test scripts to verify email configurations independently of the core computer vision logic.

---

## 📂 Repository Structure

The repository contains the following core files:

| File / Folder | Description |
| :--- | :--- |
| **`Run.py`** | The main execution script that runs the fire detection logic on video streams. |
| **`test_email.py`** | A standalone utility script to test and verify your SMTP email notification settings. |
| **`Fire detect .txt`** | Documentation/notes regarding the logic, dependencies, or pixel thresholds used for detection. |
| **`Fire Alarm Sound.mp3`** | The audio file triggered to sound an alarm upon successful fire detection. |
| **`Fire video 1.mp4` / `Fire video 2.mp4`** | Sample video clips containing fire footprints used for testing and validation. |
| **`videoplayback.mp4`** | Additional video material for system simulation. |

---

## 🛠️ Getting Started

### 1. Prerequisites
Ensure you have Python installed on your machine along with the required libraries (such as OpenCV, NumPy, and Pygame or Playsound for audio). You can install common dependencies via pip:

pip install opencv-python numpy pygame

**2. Configuration**
Before running the system, set up your email credentials inside test_email.py and Run.py (e.g., SMTP server, sender email, app password, and receiver email) to ensure notifications are successfully sent.

**3. Running the System**
To test the email notification system independently:

python test_email.py

To launch the main fire detection system using the sample videos or your camera:

python Run.py


**🤝 Contributing**

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to report a bug or suggest improvements.
