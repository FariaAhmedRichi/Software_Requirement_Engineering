# 📘 Online Platform for Local Informal Skilled People – SRE Report  

This repository contains the **Software Requirements Specification (SRS) and SRE analysis** for a conceptual online platform that connects local informal skilled workers (such as electricians, plumbers, and tailors) with clients.  

The platform is designed to address **language and accessibility barriers** faced by workers in Bangladesh by allowing them to **upload voice recordings** in regional dialects (Sylheti, Chittagonian, Bangla, English) to showcase their skills.  

⚠️ Note: This was an **academic design project**. No software implementation was carried out.  

---

## 🎯 Purpose  
- Provide job opportunities to informal workers.  
- Overcome literacy and language barriers through **voice-based profiles**.  
- Enable efficient worker–client connections using **location-based search**.  

---

## 📊 Project Scope  
The platform aims to:  
- Create worker profiles with voice uploads.  
- Allow clients to post jobs with details and wage ranges.  
- Match workers to jobs based on skills, location, and availability.  
- Provide clients with **location-based worker search**.  
- Build trust with **reviews and ratings**.  

---

## 🏗️ System Features  

### Worker Registration & Profile Management  
- Register with mobile number (OTP verification).  
- Add skills, availability, photo, and **voice sample**.  

### Job Posting & Matching  
- Clients post job details and expected wages.  
- Workers receive notifications and can apply.  

### Voice-Based Skill Showcase  
- Workers can record a **30-second voice sample**.  
- Clients can listen to samples when browsing workers.  

### Location-Based Search & Filtering  
- Clients search for workers within a chosen radius.  
- Results filtered by skill type and availability.  

---

## 🔧 Non-Functional Requirements  

- **Performance**:  
  - Support **10,000+ concurrent users**.  
  - Job matches processed within **3 seconds**.  

- **Safety**:  
  - End-to-end encrypted messaging.  

- **Security**:  
  - OTP-based user authentication.  
  - Content moderation to prevent misuse.  

- **Quality Attributes**:  
  - Data privacy, compliance with local labor laws.  
  - Regular **database backup policy**.  

---

## 🛠️ Operating Environment  

- **Platform**: Mobile (Android, iOS).  
- **Frontend**: React.js / Flutter.  
- **Backend**: Node.js / Python.  
- **Database**: Firebase / MySQL.  
- **APIs**: Google Maps API for location services.  
- **Language Support**: Bangla, Sylheti, Chittagonian, English.  

---

## 📘 Deliverables in this Repo  

- **Report** → [SRE Report PDF](report/SRE_Report.pdf)  
- **Diagrams** → [System & Use Case Diagrams](design/)  

---

## 👥 Contributors  

- Farhanaz Kamrun  
- Faria Ahmed Richi  
- Eshita Rani Acharjee  

---

## 📌 Summary  

This project demonstrates how an online job platform can be designed to:  
- **Support informal workers** through inclusive features like voice-based profiles.  
- **Ensure scalability and reliability** through SRE-focused requirements (performance targets, safety, security).  
- **Bridge accessibility gaps** by addressing language and literacy barriers common in rural Bangladesh.  

---
