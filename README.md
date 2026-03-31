\# 🚗 Traffic Prediction System



A full-stack traffic prediction system using:



\- Spring Boot (Backend)

\- FastAPI (ML Service)

\- XGBoost Model

\- Google Maps API

\- MySQL + Redis

\- JWT Authentication



\---



\## 🧠 Architecture



User → Spring Boot → FastAPI → ML + Google Maps

&#x20;                        ↓

&#x20;                  Redis + MySQL



\---



\## 📁 Project Structure

traffic-prediction-system/

├── backend-springboot/

├── ml-fastapi/





\---



\## 🚀 How to Run



\### 1. Start FastAPI



cd ml-fastapi

uvicorn main:app --reload





\### 2. Start Spring Boot



cd backend-springboot

mvn spring-boot:run





\---



\## 🔐 Features



\- JWT Authentication

\- Role-based access (USER / ADMIN)

\- Redis token caching

\- Route optimization using ML + Google Maps



\---



\## 💎 Highlights



\- Microservices architecture

\- Real-time prediction system

\- Cloud-ready deployment



\---



\## 👨‍💻 Author



Love Yadav

