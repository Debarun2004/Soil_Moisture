# 🌾 AI-Driven Smart Irrigation & Crop Suitability Prediction System 🤖💧

Welcome to the repository for the **AI-Driven Smart Irrigation & Crop Suitability Prediction System** — a smart agriculture project that leverages **Machine Learning** and **IoT** to automate watering and recommend crops based on soil conditions. 🌱

---

## 📽️ Project Demo

[![Watch on Google Drive](https://img.shields.io/badge/Watch%20Demo-Google%20Drive-blue?logo=google-drive)](https://drive.google.com/file/d/1z4FhQ-K3q2XhB8Lv2uIuqx6dO0zdjcXn/view?usp=drive_link)


> *(Video coming soon — stay tuned!)*

---

## 🚀 Project Overview

This system is built using **Raspberry Pi 3B+** and **Arduino Uno**, along with a set of sensors and actuators to monitor environmental conditions and automate irrigation based on soil needs.

### 💡 Key Features:
- ✅ **Crop Suitability Prediction** using ML (e.g., k-NN/Decision Tree)
- 🌡️ Real-time monitoring of **Soil Moisture**, **Temperature**, **Humidity**, and **Soil pH**
- 💦 **Automated Irrigation** with DC pump control via relay
- 🔄 Live data transmission from Arduino to Raspberry Pi
- 📊 Data logging for ML-based decision making

---

## 🧰 Hardware Used

| Component                  | Purpose                              |
|---------------------------|--------------------------------------|
| 🧠 Raspberry Pi 3B+        | Central Processing and ML prediction |
| 🔌 Arduino Uno            | Sensor data collection               |
| 🌡️ DHT22 Sensor           | Measures temperature and humidity    |
| 💧 Soil Moisture Sensor   | Detects water content in soil        |
| ⚗️ Analog pH Sensor        | Measures soil pH level               |
| 🔄 Relay Module (Opto)    | Controls the water pump              |
| 🚿 DC Water Pump          | Waters the soil                      |
| 🔋 5V Battery             | Portable power source                |

---

## 🔍 How It Works

1. **Arduino** collects data from soil moisture, pH, and DHT22 sensors.
2. Data is transmitted to **Raspberry Pi** via serial.
3. Raspberry Pi preprocesses the data and feeds it into a trained ML model to:
   - Predict the most suitable crops 🌽🌾🍅
   - Decide whether irrigation is needed 💦
4. If needed, the **relay module** triggers the **water pump** to irrigate the soil.
5. All data is logged and visualized for analysis.

---

## 🧠 ML Model

- Model: `k-Nearest Neighbors (k-NN)` or `Decision Tree Classifier`
- Trained using real and synthetic soil datasets
- Features: Soil Moisture, pH, Temperature, Humidity

---

## 🖥️ Tech Stack

- **Python** (Data processing, ML, serial communication)
- **Arduino C++** (Sensor interfacing)
- **Scikit-learn** (ML model)
- **Pandas / NumPy** (Data wrangling)
- **Matplotlib / Seaborn** (Optional visualizations)
- **Raspberry Pi GPIO / Serial** (I/O & Communication)


