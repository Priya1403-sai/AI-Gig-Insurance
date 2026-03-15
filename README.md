
# 🚀 GigShield AI
### AI-Powered Parametric Insurance for Gig Delivery Workers

![AI Powered](https://img.shields.io/badge/AI-Powered-blue)
![Hackathon](https://img.shields.io/badge/DEVTrails-2026-green)
![Platform](https://img.shields.io/badge/Platform-Mobile%20App-orange)

GigShield AI is an **AI-powered parametric insurance platform** designed to protect gig delivery workers from **income loss caused by external disruptions** such as heavy rain, extreme heat, air pollution, and sudden curfews.

---

# 📌 Problem Statement

India’s gig economy includes thousands of delivery partners working for platforms such as **Swiggy, Zomato, Amazon, Flipkart, and Zepto**. These workers depend on daily deliveries to earn their income.

However, several **uncontrollable external disruptions** can reduce their working hours and cause income loss.

Examples of disruptions include:

- 🌧 Heavy rain
- 🌡 Extreme heat
- 🌫 Severe air pollution
- 🚫 Curfews or sudden zone closures

Currently, gig workers have **no financial protection against these disruptions**, and they must bear the entire income loss.

Our solution introduces an **AI-powered insurance system that automatically compensates workers when such disruptions occur.**

---

# 💡 Proposed Solution

GigShield AI is a **parametric insurance platform** that uses real-time environmental data and artificial intelligence to detect disruptions and trigger automated payouts.

Key features of the system include:

✔ AI-based risk assessment  
✔ Weekly insurance premium model  
✔ Automatic claim triggering  
✔ Intelligent fraud detection  
✔ Instant payout simulation  

This ensures gig workers receive financial protection without complex claim processes.

---

# 👨‍🍳 Target Persona

### Food Delivery Partner (Swiggy / Zomato)

#### Characteristics

- Works outdoors for long hours
- Depends on number of deliveries for income
- Uses smartphone for navigation and work
- Highly affected by weather and environmental conditions
- Weekly income cycle

#### Example Scenario

A Swiggy delivery partner normally earns **₹600 per day**.

If heavy rain occurs for several hours:

- Deliveries reduce significantly
- Worker loses daily income

GigShield AI automatically **detects the disruption and compensates the worker.**

---

# ⚠ Disruption Triggers

The platform uses **parametric triggers** to determine when insurance payouts should occur.

| Disruption | Parameter | Threshold | Impact |
|---|---|---|---|
| Heavy Rain | Rainfall | > 40 mm | Deliveries halted |
| Extreme Heat | Temperature | > 42°C | Unsafe working conditions |
| Air Pollution | AQI | > 350 | Outdoor work restricted |
| Curfew | Government restriction | Zone closed | Worker cannot operate |

These triggers are monitored through **real-time external APIs**.

---

# 💰 Weekly Insurance Premium Model

Gig workers operate on **weekly earnings cycles**, so the insurance model follows a weekly pricing structure.

### Example Pricing Plans

| Plan | Weekly Premium | Weekly Coverage |
|---|---|---|
| Basic Plan | ₹30 | ₹500 payout |
| Standard Plan | ₹50 | ₹1000 payout |
| Premium Plan | ₹70 | ₹1500 payout |

Workers can select plans depending on their income and risk exposure.

---

# 🤖 AI Integration

Artificial Intelligence plays a key role in this platform.

## 1️⃣ Risk Assessment

AI analyzes environmental and geographic data to estimate disruption risks.

Input factors include:

- Historical weather data
- Flood-prone zones
- Pollution levels
- Location-based risk scores

The model generates a **risk score** that helps determine the weekly premium.

---

## 2️⃣ Dynamic Premium Calculation

Premiums are dynamically adjusted based on predicted risk levels.

Example:

| Location | Risk Level | Weekly Premium |
|---|---|---|
| High rainfall zone | High | ₹60 |
| Moderate risk zone | Medium | ₹45 |
| Low risk zone | Low | ₹35 |

This ensures fair pricing for workers.

---

## 3️⃣ Fraud Detection

The platform includes an **AI-powered fraud detection system**.

Fraud detection methods include:

- GPS location verification
- Weather API validation
- Duplicate claim detection
- Activity monitoring

Example:

Worker claims heavy rain → Weather API shows no rain → Claim flagged as suspicious.

---
# 🔄 System Workflow

The overall workflow of the system is as follows:

```
Worker Registers on Platform
        ↓
Selects Weekly Insurance Plan
        ↓
Pays Weekly Premium
        ↓
System Monitors External APIs
(Weather / Pollution / Alerts)
        ↓
Disruption Threshold Detected
        ↓
AI Fraud Detection Validation
        ↓
Automatic Claim Initiated
        ↓
Payout Sent to Worker
```

This **automated process ensures quick compensation without manual claims.**

---

# 📱 Platform Choice

### Mobile Application

A mobile platform is chosen because delivery workers primarily rely on smartphones.

Advantages include:

- Real-time notifications
- GPS-based monitoring
- Easy claim tracking
- User-friendly interface

---

# 🛠 Technology Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Spring Boot (Java REST APIs)

### Database
- MySQL / PostgreSQL

### Artificial Intelligence
- Python
- Scikit-learn / TensorFlow

### APIs
- OpenWeatherMap API
- Air Quality APIs

### Payment Integration
- Razorpay Sandbox / UPI Simulator

---

# 📱 Prototype Screens (Phase 1)

The Phase-1 prototype will demonstrate the following screens:

1. User Registration / Login  
2. Insurance Plan Selection  
3. Weekly Premium Dashboard  
4. Disruption Monitoring Page  
5. Claim Status Page  

These screens will show how the system works from a user perspective.

---

# 🏗 Development Plan

## Phase 1 – Ideation & Planning
- Define persona and disruption triggers
- Design system workflow
- Create GitHub repository
- Document project idea
- Design prototype UI

## Phase 2 – Automation & Protection
- User registration system
- Insurance policy management
- AI-based premium calculation
- Automated claims management

## Phase 3 – Scale & Optimization
- Advanced fraud detection
- Instant payout simulation
- Analytics dashboard
- Predictive disruption models

---

# 🚀 Future Enhancements

Future improvements may include:

- Hyperlocal weather prediction
- Integration with delivery platforms
- Real-time worker activity analytics
- Advanced machine learning models
- Predictive disruption alerts

---

# 🎯 Project Goal

The goal of GigShield AI is to create a **financial safety net for gig delivery workers** by protecting them from sudden income loss caused by environmental disruptions.

By combining **AI-driven risk prediction, automated claim processing, and real-time disruption monitoring**, the platform aims to build a **simple, transparent, and reliable insurance system for the gig economy**.
---

# 📂 Repository Structure

```
AI-Gig-Insurance
│
├── README.md
├── docs
│   └── architecture-diagram.png
├── frontend (planned React application)
├── backend (planned Spring Boot APIs)
└── prototype (UI mockups or designs)
```
