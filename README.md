# AI-Powered-Web-Application-for-Automated-Attendance-Through-Facial-Recognition

An intelligent attendance system that leverages **facial recognition** to automatically register attendance.  
Designed for educational institutions, workplaces, and events, this web application eliminates manual attendance marking while ensuring accuracy and efficiency.

---

## 📌 Features

- **Facial Recognition**: Real-time detection and recognition using OpenCV and a KNN classifier.
- **Automated Logging**: Records attendance (name + timestamp) into CSV files upon verification.
- **Streamlit Dashboard**: Interactive web app for live attendance records with auto-refresh.
- **Voice Feedback** *(Windows only)*: Audible confirmation for successful logging.
- **Easy Registration**: Quickly enroll new faces via webcam for future recognition.

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **Streamlit**
- **scikit-learn** (KNN Classifier)
- **Pandas**
- **Pickle** (for training data storage)

---

## 📌 How It Works

1. Open the webcam to detect faces.
2. Match detected faces with the trained dataset.
3. On pressing **'o' key**, logs name & time to CSV.
4. Streamlit dashboard auto-refreshes to show updated logs.

---

## 📖 Use Cases

- Classroom attendance automation
- Employee check-in/out
- Event participant tracking
