# FaceCheck - Facial Recognition Attendance System

FaceCheck is a modern attendance tracking system that leverages facial recognition technology to capture and record attendance. This project aims to provide a fast, accurate, and efficient way of tracking attendance, reducing errors, and eliminating the need for manual processes. Developed in collaboration with my co-coder and teammate Masam Sanjana, FaceCheck offers a seamless solution for various settings, including educational institutions and workplaces.

## Project Overview

**FaceCheck** utilizes a camera to capture an image of the user's face and compares it to a pre-existing database of images to confirm identity. If the face matches, the attendance is recorded automatically. This system enhances traditional attendance tracking methods by offering faster and more accurate results, reducing human error, and saving time.

## Features

- **Automated Attendance Tracking**: Uses facial recognition to record attendance without manual intervention.
- **High Accuracy and Speed**: Provides quick and precise attendance marking, improving overall efficiency.
- **Integration with HR Systems**: Can be integrated with payroll processing, leave management, and employee performance evaluation systems.
- **Real-Time Monitoring**: Offers real-time data tracking and monitoring for administrators.
- **Versatile Applications**: Suitable for schools, universities, government offices, hospitals, and businesses.

## Technical Stack

- **Front-End**: HTML5, CSS3, JavaScript, React.js
- **Back-End**: Node.js, Express.js
- **Database**: MongoDB
- **Facial Recognition**: OpenCV, dlib, face_recognition library
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **Version Control**: Git, GitHub

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/facecheck.git
   cd facecheck
   ```

2. **Install dependencies**:
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following variables:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the application**:
   ```bash
   npm run dev
   ```

   This will start both the server and the client concurrently.

## Usage

1. **User Registration**: Register users by capturing their facial images and storing them in the database.
2. **Attendance Marking**: Users stand in front of the camera, and the system automatically records their attendance if a match is found.
3. **Admin Dashboard**: Administrators can view and manage attendance records, generate reports, and monitor real-time data.

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request with your enhancements, bug fixes, or ideas to improve the project.

## Acknowledgements

I would like to extend my gratitude to my teammates Masam Sanjana and Satvika Devara for their invaluable contributions to the project. Special thanks to our mentors and supporters for their guidance and encouragement throughout the development of FaceCheck.

---

FaceCheck represents a significant advancement in attendance tracking technology, providing practical experience and deepening our understanding of facial recognition and its applications. We look forward to further enhancing the system and exploring new features to make attendance tracking even more efficient and reliable.

**Keywords**: Face recognition, Machine Learning, Attendance Tracking System, Real-time monitoring, Authentication.
