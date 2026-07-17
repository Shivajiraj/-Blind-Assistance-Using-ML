# Blind Assistance Using ML

> An AI-powered assistive system that helps visually impaired people understand their surroundings by detecting objects in real time and providing voice guidance.

---

# 📌 Overview

Blind Assistance Using ML is a computer vision-based application developed to assist visually impaired individuals in navigating their environment safely and independently.

The application uses a live camera feed to detect surrounding objects using the YOLO (You Only Look Once) object detection model. Whenever an object is detected, the system converts the object name into speech using Google's Text-to-Speech (gTTS) engine, allowing the user to understand what is around them without needing visual input.

The project also supports voice commands using Speech Recognition, enabling hands-free interaction with the system.

The goal of this project is to bridge the gap between computer vision and accessibility by providing an affordable, easy-to-use, and intelligent assistance tool.

---

# 🎯 Problem Statement

Millions of visually impaired people rely on canes, guide dogs, or assistance from others to navigate unfamiliar places.

These traditional methods have limitations such as:

- Unable to identify surrounding objects
- Cannot describe the environment
- Limited awareness of obstacles
- Dependence on other people
- High cost of advanced assistive devices

This project aims to solve these problems by using Artificial Intelligence and Computer Vision.

---

# 💡 Solution

The system captures live video through a webcam.

Every frame is analyzed using a YOLO object detection model.

Whenever an object is detected:

- The object name is identified.
- The confidence score is calculated.
- The detected object is displayed on the screen.
- The object name is converted into speech.
- The user hears the object through speakers/headphones.

Example:

```
Person detected
Bottle detected
Chair detected
Laptop detected
```

Instead of reading text on the screen, the user hears

> "Person ahead"

> "Bottle detected"

> "Chair on your left"

making navigation much easier.

---

# 🚀 Features

- Real-time object detection
- Voice guidance using Text-to-Speech
- Voice command support
- Live webcam processing
- Multiple object detection
- Bounding boxes with confidence score
- Easy to use interface
- Lightweight implementation
- AI-powered accessibility solution

---

# 🛠 Technologies Used

## Programming Language

- Python

## Computer Vision

- OpenCV

## Object Detection

- YOLO

## Machine Learning

- Deep Learning

## Speech

- gTTS (Google Text-to-Speech)
- SpeechRecognition

## Numerical Computing

- NumPy

## Development Tools

- VS Code
- Git
- GitHub

---

# 📂 Project Structure

```
Blind-Assistance/
│
├── dataset/
├── models/
├── images/
├── outputs/
├── main.py
├── detect.py
├── requirements.txt
├── README.md
└── yolov8n.pt
```

---

# 🖥 System Requirements

Minimum Requirements

- Windows 10 / Windows 11
- Python 3.10+
- 8 GB RAM
- Intel i5 Processor
- Webcam
- Internet (only for first-time dependency installation)

Recommended

- Python 3.11
- 16 GB RAM
- Dedicated GPU (optional)
- NVIDIA CUDA (optional for faster inference)

---

# 🧩 Required Python Libraries

Install all dependencies using

```bash
pip install -r requirements.txt
```

or

```bash
pip install ultralytics
pip install opencv-python
pip install numpy
pip install gtts
pip install SpeechRecognition
pip install playsound
pip install pyttsx3
pip install pyaudio
```

---

# 📦 Dataset Used

The project uses the **COCO (Common Objects in Context)** dataset through the pretrained YOLO model.

Dataset includes more than

- 80 object classes
- 200,000+ labeled images
- Millions of annotated objects

Examples of detectable objects

- Person
- Bicycle
- Car
- Bus
- Dog
- Cat
- Bottle
- Chair
- Laptop
- Mobile Phone
- Backpack
- Traffic Light
- Keyboard
- Cup
- Book

No custom dataset training is required because the pretrained YOLO model already provides high detection accuracy for common objects.

---

# 🤖 YOLO Model Used

The project uses

```
YOLOv8 Nano (yolov8n.pt)
```

Advantages

- Fast inference
- Lightweight
- High accuracy
- Suitable for real-time applications
- Optimized for CPU

---

# ⚙ Development Environment

Developed on

- Windows 11
- Python 3.11
- VS Code

Version Control

- Git
- GitHub

---

# 💻 VS Code Extensions

Install these extensions before running the project.

### Required

- Python
- Pylance
- Jupyter (optional)

### Recommended

- GitLens
- Code Runner
- Error Lens
- IntelliCode
- Material Icon Theme
- Prettier

---

# ▶ How to Run the Project

## Clone Repository

```bash
git clone https://github.com/yourusername/Blind-Assistance-Using-ML.git
```

---

## Move into project folder

```bash
cd Blind-Assistance-Using-ML
```

---

## Create Virtual Environment

Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python main.py
```

---

## Allow Camera Permission

When prompted

Allow

```
Camera Access
Microphone Access
```

---

# 📊 Workflow

```
Start

↓

Open Webcam

↓

Capture Frame

↓

YOLO Object Detection

↓

Identify Objects

↓

Convert Object Name into Speech

↓

Play Audio

↓

Repeat Until Exit
```

---

# 📈 Applications

- Blind Assistance
- Smart Navigation
- Indoor Navigation
- Educational Projects
- AI Accessibility Research
- Healthcare
- Smart Wearables
- Assistive Robotics

---

# 🌍 Future Improvements

- Currency Detection
- Face Recognition
- Traffic Signal Detection
- OCR Text Reading
- GPS Navigation
- Emergency SOS Feature
- Obstacle Distance Measurement
- Mobile Application
- Raspberry Pi Integration
- Smart Glasses Support

---

# 📚 Skills Demonstrated

- Python Programming
- Machine Learning
- Deep Learning
- Computer Vision
- Object Detection
- Speech Processing
- OpenCV
- YOLO
- Git & GitHub
- Software Development
- Problem Solving

---

# 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

If you find any bugs or have ideas for new features, feel free to fork the repository, create a new branch, and submit a pull request.

---

# 👨‍💻 Author

**Gujja Shivaji Raj**

B.Tech – Computer Science & Engineering (AI & ML)

Java Developer | Python Enthusiast | AI & ML Learner

GitHub: https://github.com/Shivajiraj

LinkedIn: www.linkedin.com/in/shivajiraj333

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support motivates me to build more AI and software development projects that create real-world impact.

Thank you for visiting this repository! 😊
