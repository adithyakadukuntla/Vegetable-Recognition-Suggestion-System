# Vegetable Recognition & Suggestion System

## 📌 Overview
The **Vegetable Recognition & Suggestion System** is an AI-powered application that helps users recognize vegetables from images and provides personalized health-based vegetable suggestions. It utilizes **YOLOv5** for object detection and recommends vegetables based on user-inputted health conditions.

## 🚀 Features
- **Vegetable Recognition**: Detects vegetables from uploaded or captured images using YOLOv5.
- **Health-Based Recommendations**: Suggests vegetables based on user health conditions.
- **User-Friendly Interface**: Simple and intuitive UI for easy interaction.
- **Real-Time Detection**: Users can capture images in real time for recognition.
- **Dataset Trained on Multiple Vegetables**: Supports recognition of various vegetable classes.

## 🛠️ Technologies Used
- **YOLOv5** - Object detection model for vegetable recognition.
- **Python** - Backend implementation.
- **Flask/FastAPI** - Web framework for handling API requests.
- **React.js/HTML-CSS-JS** - Frontend for user interaction.
- **Pandas & NumPy** - Data handling and processing.
- **OpenCV** - Image processing and handling.

## 📂 Project Structure
```
Vegetable-Recognition-Suggestion-System/
│-- dataset/                 # Vegetable images dataset
│-- models/                  # Trained YOLOv5 model
│-- backend/                 # API and processing logic
│   ├── app.py               # Main backend script
│   ├── recommendation.py    # Health-based recommendation logic
│-- frontend/                # Web UI
│-- requirements.txt         # Required dependencies
│-- README.md                # Documentation
```

## 📖 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Vegetable-Recognition-Suggestion-System.git
cd Vegetable-Recognition-Suggestion-System
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Backend
```bash
cd backend
python app.py
```
### 4️⃣ Start the Frontend
```bash
cd frontend
npm install
npm start
```

## 🎯 How It Works
1. **User uploads or captures an image**.
2. **YOLOv5 detects the vegetables in the image**.
3. **User enters health-related data (e.g., diabetes, high blood pressure, etc.)**.
4. **The system suggests vegetables that are beneficial for the user's condition**.
5. **The user receives recommendations in an easy-to-understand format**.

## 🏆 Example Use Case
- A user with **high blood pressure** uploads an image of a vegetable.
- The system recognizes it as **Spinach**.
- The recommendation engine suggests **spinach, beetroot, and carrots** as beneficial vegetables.




## 📜 License
This project is licensed under the MIT License.

## ✨ Acknowledgments
- YOLOv5 Team for the object detection model.
- Open-source contributors for helpful resources.
- Users and testers for feedback and improvements.

---
🔗 **Author**: [Adithya K]()  
📧 **Contact**:adhichiru634@gmail.com

