# AwareWear-Ensuring Worker Safety with IoT-Powered Smart Helmet 
A final year project developed to ensure worker safety on construction sites using IoT and AI-based technologies.

## Project Overview
Wearing helmets is important on construction sites, but it’s hard for supervisors to monitor every worker manually. **AwareWear** is a smart system that automatically detects whether a worker is wearing a helmet and marks their attendance using face recognition.
If a violation is found, the system instantly alerts the supervisor and logs the data for future reference.

## Key Features

- Automatic helmet detection using image processing
- Face recognition for worker identity verification
- Real-time alerts to supervisors on violations
- Firebase-powered dashboard for live monitoring
- Attendance and safety status logging
- Built with ESP32-CAM, Node.js, Firebase, and React

## Technologies Used

- **ESP32-CAM** – for image capture
- **Node.js** – server-side processing
- **face-api.js** – face detection and matching
- **Firebase** – real-time database and authentication
- **React.js** – responsive web dashboard

## System Flow

1. **Image Capture:** ESP32-CAM captures worker images at site.
2. **Image Transmission:** Images are sent to the Node.js server.
3. **Face + Helmet Detection:** Server analyzes the image using face-api.js.
4. **Verification:** Matches face with registered workers.
5. **Violation Detection:** Sends alert if helmet is not detected or face is unknown.
6. **Data Logging:** Firebase stores attendance and violation logs.
7. **Dashboard:** React-based dashboard displays stats and real-time updates.

Due to GitHub’s file size limits, the full project is available on Google Drive.
**[Download Full Project Folder]**(https://drive.google.com/drive/folders/1Rpih6bbXcrJ0VyM_ukEf08VwsmA6BWQH?usp=drive_link)

## 📬 Contact
For queries or collaboration:

 Email: zubaejaz1234@gmail.com 
 LinkedIn: https://www.linkedin.com/in/zubia-ejaz-a2518929b/
Thank you for checking out my project! Feel free to fork, clone, or suggest improvements.



