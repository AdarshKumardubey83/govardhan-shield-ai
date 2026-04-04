# 🛡️ Govardhan Shield AI – Parametric Insurance for Food Delivery Workers

A real-time parametric insurance simulation platform designed to protect food delivery workers from income loss caused by environmental disruptions.

**Built by Team: Vrindavan Tech**

---

## 🌟 Why Govardhan Shield AI?

Inspired by protection during adverse conditions, this system aims to provide financial security to gig workers affected by environmental risks.

---

## 🚨 Problem Overview

Delivery workers depend on daily orders for income. Environmental disruptions such as:

- Heavy rain  
- Extreme heat  
- Poor visibility  
- Strong winds  

reduce working opportunities and cause income loss.

---

## 💡 Solution

Govardhan Shield AI demonstrates a **parametric insurance model**, where:

- Environmental conditions are monitored  
- Risk is evaluated dynamically  
- Compensation is calculated automatically  

👉 No manual claim process required (simulation)

---

## ⚙️ What is Parametric Insurance?

Parametric insurance triggers payouts automatically when predefined conditions are met.

✔ No manual verification  
✔ Fast response  
✔ Transparent logic  

---

## 🚀 Live System Implementation

The current system demonstrates a **working real-time pipeline**:

- 📍 User location captured via browser geolocation  
- 🌦 Live weather fetched using OpenWeather API  
- ⚡ Triggers derived from real data:
  - HEAVY_RAIN  
  - EXTREME_HEAT  
  - HIGH_WIND  
  - LOW_VISIBILITY  
- 🧠 Risk level calculated dynamically  
- 💰 Premium adjusted based on trigger count  
- 🤖 Claim generated dynamically (simulation)

👉 Flow:

**Location → Weather → Trigger → Risk → Claim**

---

## 🧪 Demo Flow

1. User logs in using phone authentication  
2. User sets profile (name + location)  
3. Dashboard fetches real-time weather  
4. System detects environmental triggers  
5. Risk level and premium update dynamically  
6. If trigger detected → claim is auto-generated (simulated)  
7. User sees payout instantly  

---

## 🔁 Application Workflow

User → Location → Backend → Weather API → Trigger Logic → Response → UI  

---

## 💰 Insurance Model (UI Simulation)

| Plan | Weekly Premium | Coverage |
|------|--------------|----------|
| Basic | ₹25 | Up to ₹500 |
| Standard | ₹40 | Up to ₹1000 |
| Pro | ₹60 | Up to ₹1500 |

---

## ⚡ Parametric Triggers

- 🌧 Rainfall (rain > 5)  
- 🌡 Heat (temp > 40°C)  
- 💨 Wind (wind > 10 m/s)  
- ☁ Visibility (clouds > 90%)  

---

## ⚙️ System Architecture

Frontend → React (Vite)  
Backend → Node.js + Express  
Database → MongoDB  

---

## 🧠 Logic Capabilities

- Real-time environmental data processing  
- Trigger-based risk evaluation  
- Dynamic premium calculation (simulated)  
- Automated claim generation (simulated)  

---

## 🔐 Fraud Consideration (Conceptual)

- Geo-location based validation  
- API-based verification  
- No manual claims  

---

## 🌐 Deployment

- Single URL application  
- Backend serves frontend build  
- Fully integrated system  

---

## 📸 Screenshots


<img width="1115" height="860" alt="image" src="https://github.com/user-attachments/assets/eeb2594f-9968-4b3d-a6a4-6d89d275b5c5" />

---
<img width="1245" height="432" alt="image" src="https://github.com/user-attachments/assets/2ea4a757-c639-497a-82f4-036304126972" />


## 🏗 Tech Stack

- Frontend: React + Vite  
- Backend: Node.js + Express  
- Database: MongoDB  
- Authentication: Firebase + JWT  
- API: OpenWeather  

---

## 📊 Status

✔ Real-time weather integration  
✔ Dynamic trigger system  
✔ Functional dashboard  
✔ Parametric insurance simulation  

---

## ⚠️ Note

This project demonstrates a **simulation of parametric insurance logic**.  
Claim and premium calculations are simplified for demonstration purposes and are not production-grade actuarial models.

---

## 👨‍💻 Team

**Vrindavan Tech**
