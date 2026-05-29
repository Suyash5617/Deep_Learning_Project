````md
# Real Time Image Classification System using Deep Learning and OpenCV

## 📌 Project Overview
This project performs **real-time image classification** using **Deep Learning**, **TensorFlow**, and **OpenCV**.

The system captures live video through a webcam and classifies objects or scenes in real time using the pre-trained **MobileNetV2** convolutional neural network model trained on the **ImageNet** dataset.

---

## 🚀 Features
- Real-time webcam image classification
- Deep Learning-based object recognition
- Uses pre-trained MobileNetV2 model
- Live prediction display with confidence score
- Fast and efficient real-time performance
- Simple and user-friendly implementation

---

## 🛠️ Technologies Used
- Python
- OpenCV
- TensorFlow
- Keras
- NumPy
- Deep Learning
- Convolutional Neural Networks (CNN)

---

## 📂 Project Structure

```bash
Realtime_Image_Classification.py
README.md
````

---

## ▶️ How to Run the Project

### Step 1: Install Required Libraries

```bash
pip install opencv-python tensorflow numpy
```

### Step 2: Run the Program

```bash
python Realtime_Image_Classification.py
```

---

## 🎥 Working

1. The webcam captures live video frames.
2. Each frame is preprocessed and resized to 224x224.
3. MobileNetV2 predicts the object category.
4. The predicted class label and confidence score are displayed on the screen in real time.

Press **'q'** to exit the application.

---

## 🧠 Deep Learning Model

The project uses:

### MobileNetV2

* Lightweight CNN architecture
* Pre-trained on ImageNet dataset
* Optimized for real-time applications

---

## 📸 Sample Output

* Person : 98.5%
* Laptop : 95.2%
* Bottle : 93.7%

---

## 📈 Applications

* Smart Surveillance Systems
* AI-based Monitoring
* Object Recognition
* Real-time Computer Vision
* Automation Systems


