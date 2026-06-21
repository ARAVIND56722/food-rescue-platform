# 🍽️ Food Rescue Platform

A role-based web application that connects **food donors, NGOs, volunteers, and orphanages** to reduce food wastage and fight hunger through efficient redistribution.

---

## 🎯 Problem Statement

Large amounts of surplus food from hotels and events go to waste, while orphanages and shelters struggle to get regular meals. There is no simple, transparent platform to connect donors with NGOs and volunteers in real time.

---

## 🚀 Project Overview

Food Rescue Platform is a web-based social impact application that connects Donors, NGOs, Volunteers, and Orphanages to reduce food wastage and ensure surplus food reaches people in need.

The platform enables donors to post excess food, NGOs to coordinate rescue operations, volunteers to manage pickups and deliveries, and orphanages to request food assistance. A real-time tracking system provides transparency throughout the food redistribution process.

Built using Python, Streamlit, and JSON-based data storage, the project focuses on simplicity, usability, transparency, and community impact.

---

## Loom video: https://www.loom.com/share/9287f54436114cb1a7a98a4a2d55a8a4

## 💡 Solution

The Food Rescue Platform provides a centralized system where:

* Donors can post surplus food
* NGOs can review and accept food donations
* Volunteers can pick up and deliver food
* Orphanages can request meals and track delivery status

All stakeholders interact through a **single live web application**.

---

## 👥 User Roles & Features

##👨‍🍳 Donor Module
- Donor Registration & Login
- Post Food Donations
- Upload Food Images
- Quantity & Expiry Tracking
- Donation History
- Real-Time Food Status Tracking
- Timeline-Based Tracking System
  
## 🏢 NGO Module
- View All Food Donations
- Accept Food Donations
- Create Volunteer Accounts
- Create Orphanage Accounts
- Monitor Volunteer Activities
- Track Food Delivery Progress
- Manage Orphanage Requests
- View Complete Delivery History
  
## 🚚 Volunteer Module
- View Accepted Food Pickup Requests
- Confirm Food Pickup
- Confirm Food Collection
- View Auto-Assigned Orphanage Details
- Accept Delivery Assignment
- Mark Food as Delivered
- Delivery Tracking with Timestamp History
  
## 🏠 Orphanage Module
- Login with NGO-Assigned Credentials
- Submit Food Requirements
- Request Quantity & Meal Type
- Track Request Status
- Receive Food Deliveries
  
## 📊 Tracking & Transparency
- Timestamp-Based Activity Tracking
- Food Status History
- Volunteer Delivery Tracking
- End-to-End Food Journey Visibility
- Real-Time Status Updates

---

## 🛠️ Tech Stack

* **Frontend & Backend:** Streamlit (Python)
* **Data Storage:** JSON (prototype stage)
* **Deployment:** Streamlit Cloud
* **Version Control:** Git & GitHub

---

## 🧩 System Architecture

```
Donor
   │
   ▼
Food Donation Module
   │
   ▼
NGO Coordination Layer
   ├─────────────┐
   ▼             ▼
Volunteer      Orphanage
Management     Management
   │             ▲
   └──────┬──────┘
          ▼
Delivery & Tracking Engine
          │
          ▼
Food Distribution Completion
```

Each role has a dedicated dashboard with controlled access and real-time status updates.

---

## ⚠️ Current Limitations

* JSON-based storage (not suitable for large-scale production)
* Authentication is basic (demo-level)

---
## Screenshot
#  Welcome page

<img width="1631" height="807" alt="image" src="https://github.com/user-attachments/assets/d8ffa4c5-f661-4e3d-a6be-92a37658d466" />

## Donor Dashboard

<img width="1505" height="827" alt="image" src="https://github.com/user-attachments/assets/ecd4b2e1-43b2-4956-a303-91f3a56a4cd0" />



<img width="691" height="687" alt="image" src="https://github.com/user-attachments/assets/192613ba-8806-457e-85c9-90638563ea39" />



## NGO Dashboard

<img width="1572" height="791" alt="image" src="https://github.com/user-attachments/assets/5192b966-6940-4d62-898b-1ef283aedfd7" />




<img width="725" height="848" alt="image" src="https://github.com/user-attachments/assets/df2564e8-2b60-4963-9e9f-c4206580ae92" />


# NGO Assigns volunteer for delivery

<img width="1737" height="851" alt="image" src="https://github.com/user-attachments/assets/9a5ca62b-7513-43ef-89c0-474f5bf26731" />


# NGO can track the activity of the volunteer

<img width="727" height="623" alt="image" src="https://github.com/user-attachments/assets/56897d08-a13e-422e-bb23-1ce5a95aa76a" />



## Orphanage Dashboad

<img width="1707" height="832" alt="image" src="https://github.com/user-attachments/assets/39e70eb4-59f3-44a1-a9e0-f799288def67" />



<img width="545" height="335" alt="image" src="https://github.com/user-attachments/assets/1798b378-1a4b-4775-87db-1f114a28d2bd" />



## Volunteer Dashboard

<img width="1670" height="848" alt="image" src="https://github.com/user-attachments/assets/86fc5469-1796-4971-8c15-22a19417bc50" />



<img width="1202" height="582" alt="image" src="https://github.com/user-attachments/assets/efcb5ffa-3eaf-45ae-9b26-a31580e3c807" />


## 🔮 Future Enhancements

* Database integration (Firebase / MongoDB / Supabase)
* Secure authentication (OAuth / JWT)
* Mobile-friendly UI
* Analytics dashboard for NGOs
* SMS / Email notifications

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 👨‍💻 Author

# About the Developer

Hi, I'm Aravindhan AK.

I am passionate about building impactful software solutions that combine technology and social good. This project demonstrates my interest in developing real-world systems that solve meaningful community problems through innovation and technology.

# Connect With Me

📧 Email: akaravind078@gmail.com

💼 LinkedIn: www.linkedin.com/in/aravind345

💻 GitHub: https://github.com/ARAVIND56722

💻 Portfolio: https://sites.google.com/view/aravindhan-portfolio

Thank you for taking the time to review this project. Feedback and collaboration opportunities are always welcome.

