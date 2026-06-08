PlanMyEvent-A_Smart_Event_Booking_WebApplication
PlanMyEvent is a smart event booking web application that allows users to plan and manage multiple events like weddings, festivals, and parties on one platform. It offers cultural ritual guidance, verified service providers, secure booking, feedback system, and AI-based features for better planning and reliability.

🎉 PlanMyEvent – A Smart Event Booking Web Application 📌 Project Description PlanMyEvent is a smart web-based application designed to simplify event planning by providing a single platform to manage and book multiple events such as weddings, festivals, birthdays, and other ceremonies. The system not only enables users to book event services but also provides cultural and ritual guidance, helping users understand traditional practices and event workflows. It ensures trust and reliability by allowing only verified service providers through an intelligent document verification system.

🚀 Key Features 👥 Role-Based Access Control (RBAC) Three roles: Customer, Service Provider, Admin Secure access using JWT authentication Each user can access only their respective functionalities

🧑‍🤝‍🧑 Customer Features Browse multiple event categories Explore rituals and cultural guidance Book services (photography, decoration, catering, etc.) Track booking status Provide ratings and feedback

🧑‍💼 Service Provider Features Create professional profile Add services and manage bookings Upload portfolio images (past work) Upload documents for verification View customer feedback and ratings

🛡️ Admin Features Verify service provider documents Approve/reject providers View verification scores Monitor platform activity View user count and provider ratings

🪔 Ritual Guidance Module Explore Marriage and Festival rituals Filter by religions: Hindu Muslim Christian View detailed descriptions including: Traditions Cultural explanations Step-by-step rituals Interactive hover-card UI

📅 Booking System Book services across multiple event categories: Weddings Festivals Birthdays Housewarming Manage bookings and schedules

⭐ Feedback & Rating System Customers provide ratings after service Providers can view feedback Admin monitors service quality

📄 Document Verification System OCR-based verification using Tesseract Extracts data from uploaded documents Generates verification score Admin approves/rejects providers

🤖 AI Features TF-IDF for analyzing provider profiles Rule-based recommendations for services OCR for document validation

🛠️ Tech Stack Frontend React.js (Vite) HTML, CSS, JavaScript Backend Python (Flask) REST APIs Database MySQL (structured data) MongoDB (unstructured data) Security JWT Authentication Role-Based Access Control AI & Tools Scikit-learn (TF-IDF) Tesseract OCR

📁 Project Structure plan-my-event/ │ ├── backend/ │ ├── routes/ │ ├── models/ │ ├── ml/ │ └── utils/ │ ├── client/ │ ├── src/ │ │ ├── components/ │ │ ├── pages/ │ │ └── services/ │ └── README.md

⚙️ Installation & Setup 🔹 Backend cd backend pip install -r requirements.txt python app.py 🔹 Frontend cd client npm install npm run dev

🌐 Application Flow User registers and logs in Customer explores events and rituals Customer books services Service provider manages bookings Admin verifies providers and monitors system Customer gives feedback after service

🎯 Objective To develop a smart, secure, and user-friendly platform that: Supports multiple events in one system Provides cultural guidance Ensures verified service providers Improves event planning efficiency

📌 Future Enhancements Online payment integration Real-time chat between users and providers Mobile application Advanced AI recommendation system

🎥 Live Demo Walkthrough This video showcases the core features, user flow, and overall functionality of the project in action. 📺 Watch here: [https://drive.google.com/drive/folders/1uQaJOfF39MXhGQdLcopJp5ORyr5Nr8kG]
