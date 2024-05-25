CNM Group 12 Project Zalo
Team Members:
Nguyễn Hữu Huy - ID: 20102781
Hồ Hoàng Vân Anh - ID: 20098521
Trần Quốc Vịnh - ID: 20001375
Trần Anh Tuấn - ID: 20001801
Phạm Trung Vĩnh - ID: 20119821
Project Overview
This repository hosts the project for CNM Group 12, encompassing a comprehensive communication platform similar to Zalo. The project is split into three main parts:

zalo-mobile: The mobile application built with a focus on user experience and accessibility.
zalo-server: The backend server responsible for handling API requests, data storage, and business logic.
zalo-web: The web application providing a robust and responsive user interface for desktop users.
Technologies Used
Frontend: JavaScript, SCSS, HTML
Backend: Java, Starlark
Mobile: Objective-C
Project Structure
css
Sao chép mã
cnm-group12/
├── zalo-mobile/
│   ├── src/
│   ├── assets/
│   └── README.md
├── zalo-server/
│   ├── src/
│   ├── config/
│   └── README.md
├── zalo-web/
│   ├── src/
│   ├── public/
│   └── README.md
└── README.md
Getting Started
Prerequisites
Node.js (for web and mobile)
Java Development Kit (JDK) (for server)
Android/iOS development environment (for mobile)
Installation
Clone the repository

bash
Sao chép mã
git clone https://github.com/ChungZinh/cnm-group12.git
cd cnm-group12
Setup zalo-mobile

Navigate to the zalo-mobile directory
Install dependencies and run the application
bash
Sao chép mã
cd zalo-mobile
npm install
npm start
Setup zalo-server

Navigate to the zalo-server directory
Build and run the server
bash
Sao chép mã
cd zalo-server
./gradlew build
./gradlew run
Setup zalo-web

Navigate to the zalo-web directory
Install dependencies and run the application
bash
Sao chép mã
cd zalo-web
npm install
npm start
Usage
Mobile App: Use an emulator or a physical device to run the mobile application.
Web App: Access the web interface via http://localhost:3000.
Server: The server runs on http://localhost:8080 by default.
Contributing
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
Please make sure to update tests as appropriate.

License
This project is licensed under the MIT License - see the LICENSE file for details.

