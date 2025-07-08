# Smart Sensor Monitoring App – Flutter + Firebase + ESP32

A real-time mobile application built using **Flutter**, integrated with **Firebase Realtime Database**, and connected to an **ESP32 microcontroller**. This project was developed and tested during my internship at **Mannlowe**, with the goal of demonstrating seamless cloud-connected sensor data visualization on mobile devices.

---![3](https://github.com/user-attachments/assets/ae8c6ed3-f837-497f-8f10-57b94a1fc106)
![2](https://github.com/user-attachments/assets/b4acf4ed-9502-4b88-8e77-6dbffab3897a)
![1](https://github.com/user-attachments/assets/c0f92f0a-59da-41e5-a287-122de6f84dd2)


## 🚀 Features

- 🔹 Real-time monitoring of sensor values (e.g., temperature, humidity)
- 🔹 Integration with Firebase Realtime Database for data sync
- 🔹 Modular architecture for future support of multiple sensor types
- 🔹 User-friendly Flutter interface for live visualization
- 🔹 Easily expandable for BLE or Wi-Fi–based microcontroller communication

---

## 📱 Technologies Used

| Layer             | Tools / Frameworks                    |
|-------------------|----------------------------------------|
| Mobile Frontend   | Flutter, Dart                         |
| Cloud Backend     | Firebase Realtime Database, Firebase Auth (optional) |
| IoT Hardware      | ESP32, DHT11 (or similar sensors)     |

---

## 🧪 Use Cases

This project can be adapted for:
- 🌡️ **IoT-based environmental monitoring**
- 🏥 **Healthcare prototype apps for sensor tracking**
- 🧠 **Educational and research demonstration tools**
- 📲 **Any real-time mobile data visualization system**

---

## 🔧 Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/esp32.git
cd esp32

Install Flutter Dependencies

bash
Copy
Edit
flutter pub get
Connect Firebase

Create a Firebase project

Add google-services.json to android/app/

Enable Firebase Realtime Database

Run the App

bash
Copy
Edit
flutter run
📂 Project Structure
bash
Copy
Edit
lib/
 ├── main.dart             # Entry point
 ├── home.dart             # UI to show live sensor data
 ├── firebase_service.dart # Firebase connectivity logic
 └── sensor_model.dart     # Sensor data model structure
📘 Project Background
This project was built and refined during my internship at Mannlowe, where I contributed to mobile and IoT-based product development. It served as a hands-on demonstration of integrating real-world hardware with real-time cloud systems using Flutter and Firebase.

I was responsible for:

Setting up Firebase DB architecture

Building the mobile interface in Flutter

Writing backend logic for syncing ESP32 data

Testing and debugging end-to-end data flow

🎯 Key Learning Highlights
Hands-on experience in real-time mobile app development

Cloud-based communication between hardware and software

Clean code structuring and modular Dart development

Firebase Authentication and database security basics

👨‍💻 Developer
Ishan 

