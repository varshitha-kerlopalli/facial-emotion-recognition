# 🎭 Face Detection & Emotion Recognition System

A real-time Face Detection and Emotion Recognition system built using Deep Learning and OpenCV.  
The system detects human faces using Haar Cascade and predicts emotions using a trained CNN model.

---

## 🚀 Features

✔ Real-time face detection using OpenCV  
✔ Emotion prediction using trained deep learning model  
✔ Uses Haar Cascade classifier  
✔ Pre-trained model included (`model_file_30epochs.h5`)  
✔ Clean and simple implementation  

---

## 🛠️ Tech Stack

- Python
- OpenCV
- TensorFlow / Keras
- NumPy

---

## 📂 Project Structure

```
Face-Detection-Project/
│
├── main.py                               # Main application file
├── test.py                               # Testing script
├── testdata.py                           # Data testing utilities
├── haarcascade_frontalface_default.xml    # Haar cascade file for face detection
├── model_file_30epochs.h5                 # Trained CNN model (30 epochs)
├── README.md                              # Project documentation
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/face-detection-project.git
cd face-detection-project
```

### 2️⃣ Install Dependencies

```bash
pip install numpy opencv-python tensorflow
```

---

## ▶️ How to Run

```bash
python main.py
```

The webcam will open and start detecting faces and predicting emotions in real time.

---

## 🧠 Model Details

- CNN based architecture
- Trained for 30 epochs
- Saved as: `model_file_30epochs.h5`
- Input: Grayscale face image
- Output: Emotion class prediction

---

## 🎯 Example Emotions Detected

- Happy
- Sad
- Angry
- Surprise
- Neutral
- Fear
- Disgust

---

## 📌 How It Works

1. Capture real-time video from webcam  
2. Detect faces using Haar Cascade  
3. Preprocess detected face  
4. Pass face to trained CNN model  
5. Display predicted emotion on screen  

---

## ⚠️ Important Notes

- Make sure webcam is connected.
- If the `.h5` file is larger than 100MB, use Git LFS before pushing to GitHub.
- Ensure all files are in the same project directory.

---

## 📈 Future Improvements

- Improve model accuracy
- Add GUI interface
- Deploy as web application
- Add emotion statistics tracking

---

## 👩‍💻 Author

**Varshitha Kerlopalli**

---

⭐ If you like this project, give it a star on GitHub!
