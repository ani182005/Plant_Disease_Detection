# 🌿 Plant Disease Detection using Deep Learning & Embedded Systems 🚀

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Tomato_leaf_with_Early_blight.JPG" alt="Plant Leaf" width="500"/>
</p>

---

## 📌 Project Overview  

🌱 Plant diseases significantly affect crop yield and farmer income.  
This project focuses on **automated plant disease detection** using **Convolutional Neural Networks (CNNs)** and further optimizes the model to run on **embedded systems (ESP32-CAM)**.  

✨ The goal:  
- Train a CNN model to classify plant leaf diseases.  
- Achieve high accuracy while keeping the model lightweight.  
- Deploy the model into **low-power IoT hardware** for real-time disease detection.  

---

## 🧩 Features  

✅ Deep Learning model (TensorFlow / Keras)  
✅ Works with **10 disease classes**  
✅ Visualization of accuracy & confusion matrix 📊  
✅ Conversion to **TensorFlow Lite (TFLite)** for deployment  
✅ Optimized for **ESP32-CAM / IoT boards** 🌍  

---

## 📂 Dataset  

📸 **Dataset Structure:**  


- Each folder contains images of diseased and healthy plant leaves.  
- Classes include *Early Blight, Late Blight, Bacterial Spot, Septoria Leaf Spot, Healthy, etc.*  

> 🔗 [(https://www.tensorflow.org/datasets/catalog/plant_village)]

---

## 🏗️ System Design  

The system follows these main stages:  

1. 📥 **Image Acquisition** – Plant leaf images are captured.  
2. 🧹 **Preprocessing** – Images are resized, normalized, and prepared for training.  
3. 🧠 **Model Training** – A CNN model is trained to classify diseases.  
4. 📊 **Evaluation** – Accuracy and confusion matrix are used for testing.  
5. 🔄 **Optimization** – The model is compressed and converted to TensorFlow Lite.  
6. 💻 **Deployment** – The optimized model is deployed on ESP32-CAM for real-time detection.  

---

## 📊 Results  

✔️ High accuracy in disease classification  
✔️ Successfully reduced model size with TensorFlow Lite  
✔️ Deployment possible on **ESP32-CAM hardware**  

<p align="center">
  <img src=""C:\Users\user\Downloads\img1.png"" alt="Accuracy Graph" width="500"/>
</p>


---

## ⚙️ Hardware Implementation  

The hardware setup involves:  

- 📸 **ESP32-CAM** for image capture and local inference  
- ☁️ WiFi module for sending data to cloud/mobile devices  
- 🔋 Battery/USB as power supply  
- 🖥️ Laptop/Server for optional monitoring  

The ESP32-CAM runs the compressed **TensorFlow Lite Micro** model and classifies diseases in real-time.  

---

## 📦 Software Requirements  

- Python 🐍 (≥3.8)  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib, Seaborn  
- Arduino IDE / PlatformIO (for ESP32 deployment)  

---

## 🚀 Future Improvements  

- 🌍 Deploy model on cloud with live dashboard  
- 📲 Mobile app for farmer-friendly usage  
- 🛰️ Integration with drones or CubeSats for large-scale monitoring  
- 🧠 Improve accuracy with transfer learning (e.g., MobileNetV2, EfficientNet)  

---

## 📸 Demo (Screenshots)  

<p align="center">
  <img src="https://cdn.dribbble.com/users/926537/screenshots/4502924/media/61b1bdbb7e2a9b8db0b785c63fc7b60d.gif" alt="Demo GIF" width="500"/>
</p>

---

## 🤝 Contributors  

👨‍💻 **Anirruthan Naarayanan**  
- 📚 2nd Year Engineering Student @ VIT Chennai  
- Enthusiast in AI, IoT & Embedded Systems  

---

## 📝 License  

📜 This project is licensed under the **MIT License**.  
Feel free to use, modify, and share 🌱.  

---

<p align="center">✨ If you like this project, give it a ⭐ on GitHub! ✨</p>
