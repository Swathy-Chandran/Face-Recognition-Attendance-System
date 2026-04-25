# Face Recognition Attendance System

## 📌 Project Overview
This project is a real-time attendance system that uses face recognition to automate attendance tracking. It eliminates the need for manual registers or fingerprint systems by identifying individuals through a webcam.

---

## ⚙️ Technologies Used
- Python
- Flask
- OpenCV
- Machine Learning (KNN Algorithm)
- Pandas

---

## 🚀 Features
- Real-time face detection using webcam
- Face recognition and identification
- Automatic attendance marking with timestamp
- CSV-based attendance storage
- Simple web interface using Flask

---

## 🧠 Development Process

### 1. Planning
The goal was to automate attendance using face recognition instead of traditional manual methods.

### 2. Design
- Used OpenCV for face detection
- Used KNN algorithm for face recognition
- Flask used for backend web interface

### 3. Implementation
- Collected face images and stored them in structured folders
- Trained a machine learning model using KNN
- Integrated real-time webcam feed for detection
- Stored attendance data in CSV format

### 4. Testing
- Tested with multiple users
- Verified recognition accuracy
- Fixed detection issues in different lighting conditions

---

## ⚠️ Toughest Problems Solved

### Problem 1: Face Detection Accuracy
Faces were not detected properly under different lighting conditions.

✔ Solution: Adjusted detection parameters and improved preprocessing using grayscale conversion.

---

### Problem 2: Model Prediction Errors
Incorrect identification due to insufficient training data.

✔ Solution: Increased training samples and structured dataset properly.

---

## ▶️ How to Run

### Step 1: Install dependencies

pip install -r requirements.txt

### Step 2: Run the application

python app.py


### Step 3: Open browser

http://127.0.0.1:5000/

## 📸 Output

![Attendance](https://github.com/user-attachments/assets/306652b1-bce5-4c36-a453-fdf5cab16bcb)
![Face Detection](https://github.com/user-attachments/assets/b06e19ff-6f72-4824-9deb-52623ef83c63)


## 📌 Future Improvements
- Use deep learning models for better accuracy
- Store attendance in database instead of CSV
- Improve UI/UX

---

## 🎯 Outcome
A working system that detects faces in real-time and marks attendance automatically, reducing manual effort.

## 👩‍💻 Author
Swathy Chandran N
