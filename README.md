🚗 CovoitX - Community Carpooling Platform
📌 Project Description

CovoitX is a web and mobile carpooling application designed for private communities such as universities and companies.
It allows members to offer, search, and book rides easily and securely, while encouraging sustainable mobility.

This project is part of my final year graduation project (PFE).

⚙️ Tech Stack

Backend: Laravel (REST API), MySQL

Frontend Web: Vue.js

Frontend Mobile: Flutter

Services: Firebase, Google Maps API

📂 Project Structure
CovoitX/
│
├── Backend/      # Backend source code (API & database)
│
├── Frontend/     # Frontend source code (Web & Mobile)
│
├── DeepFace-verification/   # Experimental module for identity verification using AI
│
└── README.md     # Project documentation

🚀 Installation
1️⃣ Clone the repository
git clone https://github.com/azza5/CovoitX.git
cd CovoitX

2️⃣ Backend setup (Laravel + MySQL)
cd Backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve

3️⃣ Frontend setup (Vue.js)
cd Frontend
npm install
npm run serve

4️⃣ Mobile app (Flutter)
cd Frontend/flutter_app
flutter pub get
flutter run

🔐 Features

✅ User authentication & community membership

✅ Ride creation and booking system

✅ Real-time notifications (Firebase)

✅ Location tracking & route display (Google Maps API)

✅ Identity verification with AI (DeepFace module)

🧑‍💻 Author

👤 Azza Tilouche
Final year student – Information Systems Development
