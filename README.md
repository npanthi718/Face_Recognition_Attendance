# 🚀 Face Recognition-Based Attendance System with Python & OpenCV

[![Made with Python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

---

## 🌟 Project Overview

The **Face Recognition-Based Attendance System** is a smart and efficient solution for automating attendance management using Python, OpenCV, and facial recognition technology. This project is designed to capture, recognize, and record attendance seamlessly, providing a robust alternative to traditional attendance systems.

---

## 🎯 Key Features

- **Face Registration:** Capture and store face images for attendance recognition.
- **Automated Attendance:** Detect faces and mark attendance automatically.
- **Data Management:** Store attendance records as `.csv` files by subject.
- **Interactive Interface:** Simple and user-friendly UI for easy interaction.
- **Efficient Recognition:** Utilizes OpenCV for real-time face detection.

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/facerec-attendance.git
cd facerec-attendance
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Prepare Directory

Create a `TrainingImage` folder in the project directory.

### 4. Configure Paths

Update paths in `attendance.py` and `automaticAttendance.py` according to your system.

### 5. Run the Application

```bash
python attendance.py
```

---

## 🌀 How It Works

1. **Register New Student:** Enter ID and Name, then click `Take Image`.
2. **Capture Images:** The system takes 50 face images and stores them in `TrainingImage`.
3. **Train the Model:** Click `Train Image` to convert images into a recognizable model.
4. **Automatic Attendance:** Select a subject and start attendance marking.
5. **View Attendance:** Check the recorded attendance in a tabular format.

---

## 📸 Screenshots

### 🔹 User Interface

![UI Screenshot](path_to_your_image)

### 🔹 Face Capture Process

![Face Capture](path_to_your_image)

### 🔹 Attendance Marking

![Attendance Marking](path_to_your_image)

### 🔹 Attendance in Tabular Format

![Tabular Attendance](path_to_your_image)

---

## 💡 Tips for Best Performance

- Ensure good lighting conditions during face capture.
- Provide a clear and unobstructed view of the face.
- The more images captured, the better the recognition accuracy.

---

## 🛠️ Technologies Used

- **Python 3.9**
- **OpenCV 4.x**
- **Face Recognition Library**
- **Flask** (Optional for Web UI)
- **Pandas** (For data management)

---

## 💖 Support & Contributions

Feel free to open issues or submit pull requests to contribute to this project. If you find this helpful, give a ⭐ to support!

---

## 🤝 Connect with Me

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://linkedin.com/in/yourprofile)

Stay awesome! 🚀✨
