# Smart-Face-Recognition-Attendance-System
Smart Face Attendance System ek Python-based computer vision project hai jo webcam ke through students ke faces detect aur recognize karta hai.

🔹 Project kaise kaam karta hai?
Webcam
   ↓
Face Detection
   ↓
Face Recognition
   ↓
Student Database
   ↓
Name + ID + Department
   ↓
Attendance
   ↓
Date + Time
1. 📷 Webcam

System laptop/PC ka webcam open karta hai aur continuously video frames capture karta hai.

2. 👤 Face Detection

OpenCV Haar Cascade camera frame mein human face detect karta hai aur face ke around rectangle draw karta hai.

3. 🧠 Face Recognition

Registered students ki face information database mein save hoti hai. Camera ke saamne koi registered student aaye to system uske face ko stored face se compare karta hai.

4. 🧑 Student Information

Successful match ke baad system database se:

Name
Student ID
Department

retrieve karta hai.

Example:

Name: Ali
ID: ST-101
Department: Computer Science
5. 📅 Attendance

Recognized student ki attendance automatically record hoti hai:

Name: Ali
ID: ST-101
Department: Computer Science
Date: 2026-08-12
Time: 08:30:15
Status: Present
6. 📁 Attendance File

Attendance ko CSV file mein save kiya ja sakta hai, jise Excel mein bhi open kiya ja sakta hai.

7. ❓ Unknown Person

Agar face database mein registered nahi hai, system usko:

Name: Unknown
ID: Unknown
Department: Unknown
Status: Not Registered

show karega.

🛠️ Technologies
Python — main programming language
OpenCV — webcam aur face detection
Haar Cascade — face detection model
Face Recognition — registered face matching
CSV/JSON — student aur attendance records
Webcam — real-time video input
🎯 Project ka purpose

Ye project educational computer-vision demonstration ke liye useful hai aur manual attendance ko automate karne ka concept demonstrate karta hai. Student information sirf aapke local registered database se retrieve hoti hai; system automatically kisi external/private database se personal information nahi nikalta.
