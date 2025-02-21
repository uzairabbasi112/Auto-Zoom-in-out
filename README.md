# **Face Distance Estimation Using MediaPipe**  
This project estimates the distance of a face from the camera using **MediaPipe Face Landmarks**. It calculates the distance based on the relative positions of two facial landmarks.  

---

## 🚀 **Features**  
✅ Uses **MediaPipe Face Mesh** for landmark detection  
✅ Calculates distance based on landmark separation  
✅ Works in **real-time** with a webcam  
✅ Can be adapted for various distance estimation applications  

---

## 📌 **Installation**  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Project**  
   ```bash
   python main.py
   ```

---

## 🎯 **How It Works**  
1. **MediaPipe Face Landmarks** detects key facial points.  
2. The program measures the **pixel distance** between two specific points (e.g., eyes, nose, or lips).  
3. It estimates the **real-world distance** from the camera based on a reference calibration.  

---

## 🛠 **Dependencies**  
- Python 3.x  
- OpenCV  
- MediaPipe  
- NumPy  

Install all dependencies using:  
```bash
pip install opencv-python mediapipe numpy
```

---

## 📸 **Example Output**  
The program continuously tracks the selected face landmarks and displays the calculated distance on the video feed.  

---

## 📝 **Future Improvements**  
- Use **multiple landmarks** for better accuracy  
- Improve **calibration** for real-world distance mapping  
- Implement a **deep learning model** for enhanced performance  

---
