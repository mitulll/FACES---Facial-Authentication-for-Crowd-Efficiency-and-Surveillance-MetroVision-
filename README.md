# FACES - Facial Authentication for Crowd Efficiency and Surveillance (MetroVision)

A Python-powered attendance management solution designed for **metro surveillance environments**. This system utilizes **real-time face recognition** to automate **employee attendance**, streamline **shift tracking**, and enhance **security and efficiency**.

---

## 🚀 Getting Started

Follow these steps to set up and run the system on your local machine:

#### 1. Clone the Repository
```bash
git clone https://github.com/Patelrahul4884/Attendance-Management-system-using-face-recognition.git
```
#### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
This will install all required Python packages.
#### 3. Project Folder Setup
Create a folder named ```TrainingImage``` inside the project directory.
This will store all captured face images of employees.
#### 4. Configure Paths
1) Open ```attendance.py``` and ```automaticAttendance.py```

2) Update file and folder paths according to your system's directory structure.
#### 5. Run the Application
```bash
python attendance.py
```



## 📝 How It Works
✅ Register a New Employee
- Launch the application and click Register New Employee

- Enter the Employee ID and Name

- Click Capture Face – the webcam will capture up to 50 images (adjustable)

- Images are stored in the ```TrainingImage``` folder

- More images = better recognition accuracy

🧠 Train the Recognition Model
- Click Train Images to process and encode captured images

- Converts faces into numerical data using OpenCV

- Training time depends on image count and system performance

🎯 Automated Shift Attendance
- Click Automated Attendance

- Select or enter the Shift (e.g., Morning Shift, Evening Shift)

- The system recognizes employees in real-time and logs attendance

- Records saved in a CSV file named after the shift

📊 View Attendance Records
- Click View Attendance

- Displays attendance logs per shift in a tabular format


## 💡 Features
- 🖥️ User-friendly GUI (Tkinter)

- 📷 Real-time face detection (OpenCV)

- 🔄 Shift-wise automated attendance (Morning/Evening)

- 🙋 Easy employee registration & image capture

- 📁 CSV export of attendance data

- 📈 Attendance report per shift





## 📚 About
Tailored for metro surveillance and security teams, this system automates and secures employee attendance tracking across multiple shifts using advanced facial recognition technology.

## 🏷️ Topics
```python``` ```opencv``` ```face-recognition``` ```tkinter``` ```attendance-management``` ```shift-management``` ```metro-surveillance```

## 👨‍💻 Authors & Contributors
- Mitul Chitkara
- Adithya Anand
- Josh Ethan N
