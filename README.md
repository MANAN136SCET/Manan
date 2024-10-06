<h1 align="center" style="font-size: 100px; font-family: 'Arial';"><strong>🚀 Team: Space Cipher 🌍</strong></h1>

---

## 🗂️ Contents:

- [🌍 Introduction](#-introduction)
- [🚀 Challenge: Pace in the Classroom](#-challenge-pace-in-the-classroom)
  - [🛰️ Challenge Overview](#-challenge-overview)
  - [📜 Summary](#-summary)
- [🌊 Impact](#-impact)
- [💡 Challenge Faced & Solutions](#-challenge-faced--solutions)
- [🛠️ Tools We Use](#-tools-we-use)
- [📑 Features](#-features)
- [⚙️ Installation & Setup](#%EF%B8%8F-installation--setup)
- [🌐 Application](#-application)
  - [🏠 Home Page](#-home-page)
  - [🔍 Explore Page](#-explore-page)
  - [📚 Lesson Page](#-lesson-page)
  - [🗺️ Map](#-maps)
  - [👥 Community Page](#-community-page)
- [👥 Team](#-team)
  - [👨‍💻 Members](#-members)
  - [🎓 Mentors](#-mentors)
  - [🙏 Special Thanks](#-special-thanks)

---

## 🌍 Introduction

This project bridges the gap between NASA’s PACE mission satellite data and educational resources. We aim to make oceanic and atmospheric data accessible and engaging for students of all age groups. Through interactive tools and lessons, we foster curiosity and encourage a deeper understanding of ocean literacy.

---

## 🚀 Challenge: PACE IN THE CLASSROOM

We are participating in the **Pace in the Classroom** challenge, which focuses on transforming complex data from NASA’s PACE satellite into engaging and digestible educational content for students worldwide.

### 🛰️ Challenge Overview

The **Plankton, Aerosol, Cloud, ocean Ecosystem (PACE) satellite** was launched on **February 8, 2024**, and has been gathering critical data about Earth’s oceans and atmosphere. This data, made publicly available by NASA, is often too technical for students and non-experts to grasp.

Our goal is to bridge this gap by developing engaging, kid-friendly educational materials that turn PACE’s scientific data into lessons for classrooms worldwide, promoting ocean literacy and inspiring curiosity.

### 📜 Summary

NASA’s PACE satellite collects essential data on Earth’s atmosphere and oceans, helping scientists understand phytoplankton and ocean-atmosphere interactions. However, the complexity of this data presents a barrier for students. 

Our project aims to convert this intricate data into interactive, engaging content that teachers can integrate into their curriculums, improving ocean literacy and inspiring the next generation to explore Earth sciences.

---

## 🌊 Impact

With our interactive, easy-to-use tools, we aim to:

- **Increase ocean literacy** among students globally.
- **Inspire curiosity** about Earth sciences and climate change.
- **Empower students** to explore real-time satellite data in a fun and approachable way.

---

## 💡 Challenge Faced & Solutions

- **Challenge**: Making NASA’s complex PACE data accessible for younger audiences.
  - **Solution**: Simplified visualizations and tailored lesson materials to make the data engaging.

- **Challenge**: Managing large datasets with limited cloud storage.
  - **Solution**: Down-sampled the data to reduce size.

- **Challenge**: Slow rendering times when displaying the Earth globe data.
  - **Solution**: Added caching to speed up rendering.

- **Challenge**: Stack size exceeded error during data rendering.
  - **Solution**: Implemented data range limits based on metadata to prevent overflow errors.

---

## 🛠️ Tools We Use

- **Frontend**: React, Vite, Three.js, Node.js
- **Backend**: Python-Flask
- **Database/Cloud Storage**: MongoDB Atlas
- **Data Source**: [PACE Ocean Data API](https://oceandata.sci.gsfc.nasa.gov/api/file_search/)
- **AI Tools**: ChatGPT, Leonardo AI
- **Hosting**: Vercel (Frontend), GCP (Backend)
- **Domain**: Porkbun.com

---

## 📑 Features

- **Interactive 3D Globe Visualization** using Three.js
- Educational **videos** explaining how PACE collects data.
- Detailed exploration of PACE’s **scientific instruments**.
- **Kid-friendly lessons** and engaging materials.
- Easy-to-navigate **data visualizations**.
- **Simulations** for understanding marine life and atmosphere interactions.

---

## ⚙️ Installation & Setup

### Clone the Repository

```bash
git clone [repository-link]
