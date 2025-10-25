# 🌟 Lumos Navigation App for the Visually Impaired 

**Lumos** is an accessibility-focused navigation app designed to help visually impaired users navigate safely and efficiently. It combines **real-time object detection** , **voice-guided navigation** , and **offline support**  in a single Flutter-based application.

This project was created for the **🎃 Hackoween Hackathon**!  

---

## 👩‍💻 Team Members
- **Tanisha Mathur** 
- **Sanchita Sunil**   
- **Archana Shivakumar**  
- **Sudev Suresh** 

For queries or collaboration, reach us via **📧 Gmail** or **🔗 LinkedIn**.

---

## 🚀 Features

### 🌐 Online Model (Requires Internet)
Powered by **Gemini API** for real-time processing.

1. **🔍 Surroundings Detection**
   - Real-time object detection using the online model.
   - Voice output describing nearby objects.
   - Voice input supported for interaction.

2. **💡 Flashlight Control**
   - Tap to switch on the flashlight.
   - Tap again to switch it off.

3. **🗺️ Voice Navigation**
   - Navigate from **Place A to Place B** using **Google Maps** API.
   - Voice-guided directions ensure hands-free navigation.

4. **🗺️ Plain Maps**
   - Opens Google Maps for manual navigation.

---

### 📦 Offline Model (Works Without Internet)
Powered by **COCO dataset** with **SSD MobileNetV1 (TF Lite)** model.

- Detects objects in real-time without internet connectivity.  
- Ensures accessibility even in areas with poor or no network coverage.  

---

### 🔀 Smart Switch
- Automatically checks if the device has network connectivity.  
- Switches between **offline** and **online** models based on network availability.  

---

## 🛠️ Built With
- **Flutter** – Cross-platform mobile framework 🖥️📱  
- **Dart** – Programming language used for Flutter development 📝  
- **TensorFlow Lite** – For offline model inference 🤖  
- **Gemini API** – For online real-time object detection 🌐  
- **Google Maps API** – For navigation and directions 🗺️  

---

## 🎮 Usage

1. Launch the app 🚀  
2. The **smart switch** automatically selects the appropriate model (online/offline) 🔄  
3. Use the buttons to:
   - **🔍 Check surroundings** (object detection with voice output)  
   - **💡 Toggle flashlight**  
   - **🗣️ Enable voice-guided navigation**  
   - **🗺️ Open plain maps**  
4. Follow voice instructions for safe and accessible navigation ✅  

---

## ⚙️ Installation

1. Ensure **Flutter SDK** is installed ⚡  
2. Clone the repository:
   ```bash
   git clone <repository-url>
