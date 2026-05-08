# 🌱 Smart Agriculture System using IoT

An IoT-powered solution for modern farming that integrates **real-time monitoring**, **automated irrigation**, and **machine learning-based crop recommendations**. This project was developed as part of the B.Tech program in Electronics & Communication Engineering at **Haldia Institute of Technology**.

![image alt](https://github.com/Deepak-008/Smart-Agriculture-Using-IOT-with-ML-Integration/blob/main/circuit.png)
---

## 📖 Overview
Traditional farming often relies on manual checks and guesswork. Our Smart Agriculture System leverages IoT sensors and cloud-based data processing to:
- Monitor **temperature, humidity, and soil moisture** in real time.
- Automate irrigation when soil moisture drops below a threshold.
- Send alerts to a mobile app when critical conditions occur.
- Recommend suitable crops based on soil nutrient data using **machine learning**.

This approach improves resource efficiency, reduces manual intervention, and promotes sustainable farming practices.

---




![image alt](https://github.com/Deepak-008/Smart-Agriculture-Using-IOT-with-ML-Integration/blob/main/Ckt_DIA.png)

## 🏗️ System Architecture
The system follows a layered architecture:

1. **Sensing Layer**  
   - DHT11 sensor (temperature & humidity)  
   - Capacitive soil moisture sensor  

2. **Processing Layer**  
   - ESP32 microcontroller (Wi-Fi + Bluetooth)  
   - Arduino IDE for programming  

3. **Communication Layer**  
   - Wi-Fi/Bluetooth modules  
   - Cloud storage & processing (ThingsBoard, Blynk, Adafruit IO)  

4. **Actuation Layer**  
   - Automated irrigation pump  
   - Mobile app alerts (Flutter/React Native)  

---

## ⚙️ Hardware Components
- ESP32 DevKitC V4  
- DHT11 Sensor  
- Capacitive Soil Moisture Sensor v1.0/v2.0  
- LM2596 Voltage Regulator  
- Vero Board, DC barrel jack, pin headers, on/off switch  

---

## 💻 Software Components
- **Arduino IDE** (C/C++) for ESP32 programming  
- **Mobile App** (Flutter/React Native) for real-time monitoring  
- **IoT Platforms** (optional): ThingsBoard, Blynk, Adafruit IO  
- **Machine Learning Models**: Decision Trees for crop recommendation  

---

[image alt](https://github.com/Deepak-008/Smart-Agriculture-Using-IOT-with-ML-Integration/blob/main/UI.png)
---

## 🤖 Machine Learning Integration
The ML workflow includes:
1. **Data Collection** – Soil nutrients (Ca, K, P, S, Mg), temperature, rainfall  
2. **Preprocessing** – Normalization & cleaning  
3. **Model Building** – Decision Tree algorithm  
4. **Prediction** – Crop recommendation based on soil/environment data  
5. **Visualization** – Graphs & insights for farmers  

---

## 🚀 Features
- 🌡️ Real-time monitoring of farm conditions  
- 💧 Automated irrigation system  
- 📱 Mobile app alerts for critical conditions  
- 🌾 Crop recommendation using ML  
- 🌍 Promotes sustainable farming practices  

---

## 📌 Future Scope
- Integration with **AI-powered pest/disease detection**  
- Expansion to **multi-crop recommendation systems**  
- Use of **5G & edge computing** for faster data processing  
- Blockchain-based **secure farm data management**  

---

## 👨‍💻 Authors
- Deepak Kumar Pandey (21/ECE/048)  
- Aryan Kumar (21/ECE/032)  
- Anupam Pandey (21/ECE/025)  
- Anurag Kumar Karn (21/ECE/026)  
- Bhaskhar Kumar (21/ECE/040) 

Under the supervision of **Dr. Jagannath Samanta**, Associate Professor, Dept. of ECE, Haldia Institute of Technology.

---

