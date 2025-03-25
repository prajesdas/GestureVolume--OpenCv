

# 🎵 GestureVolume – Hand Gesture Volume Control ✋🔊  

🚀 Control your system volume using simple hand gestures! **GestureVolume** leverages OpenCV, MediaPipe, and system commands to adjust volume dynamically based on finger distance. No need to touch your keyboard or mouse!  

---

## ✨ Features  
- 🖐️ **Hand Tracking:** Uses MediaPipe to detect hand movements in real-time.  
- 🔊 **Volume Control:** Move your thumb and index finger to adjust system volume.  
- 🎥 **Live Camera Feed:** See real-time hand tracking with interactive UI.  
- ⚡ **Smooth Transitions:** Gradient volume bar with animated updates.  
- 🖥️ **Cross-Platform:** Works on macOS (modify for Windows/Linux support).  

---

## 🎥 Demo  
🔹 **Thumb & Index Finger Apart → Volume Up** 🔼  
🔹 **Thumb & Index Finger Close → Volume Down** 🔽  
![Screenshot 2025-03-26 013914](https://github.com/user-attachments/assets/48e143f8-7510-489e-8c60-9711f35fc54f)

![Screenshot 2025-03-26 013934](https://github.com/user-attachments/assets/2dbebe44-f511-4203-9f6b-34e6d8c28926)

![Screenshot 2025-03-26 013948](https://github.com/user-attachments/assets/f483f1c2-1f99-4a40-a128-cb9a2894bb0c)

![Screenshot 2025-03-26 014024](https://github.com/user-attachments/assets/0277c368-fd86-47d3-a3d2-3721323d6e01)

---

## 🛠️ Installation  

### 1️⃣ Install Dependencies  
Ensure Python is installed, then run:  
```bash
pip install opencv-python mediapipe
```  

### 2️⃣ Run the Script  
```bash
python gesture_volume.py
```  

---

## 🎮 How It Works  
1. **Move your thumb and index finger apart** – Volume increases 🔼  
2. **Bring them closer together** – Volume decreases 🔽  
3. **Track progress with the volume bar** – Updates in real-time!  

📌 **Press 'Q' to exit the program.**  



