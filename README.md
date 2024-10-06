<h1 align="center" style="font-size: 120px;"><strong>Team: Space Cipher</strong></h1>

---

## Contents:

- [Introduction](#introduction)
- [Challenge](#challenge-pace-in-the-classroom)
  - [Challenge Overview](#challenge-overview)
  - [Summary](#summary)
- [Impact](#impact)
- [Challenge Faced & Solution](#challenge-faced--solution)
- [Tools We Use](#tools-we-use)
- [Features](#features)
- [Installation & Set up](#installation--setup)
- [Application](#application)
  - [Home Page](#home-page)
  - [Explore Page](#explore-page)
  - [Lesson Page](#lesson-page)
  - [Map](#maps)
  - [Community Page](#community-page)
- [Team](#team)
  - [Members](#members)
  - [Mentors](#mentors)
  - [Special Thanks](#special-thanks)

---

## Introduction

This project aims to bridge the gap between complex satellite data from NASA’s PACE mission and educational resources, making oceanic and atmospheric data more accessible to students of various age groups. Through engaging tools and lessons, we hope to spark curiosity and foster a deeper understanding of ocean literacy.

---

## Challenge: PACE IN THE CLASSROOM

We are working on the **Pace in the Classroom** challenge, which focuses on making complex data from NASA’s PACE satellite accessible and engaging for students worldwide. Our goal is to create digestible educational materials that help integrate this data into classroom curriculums, improving ocean literacy globally.

### Challenge Overview

The **Plankton, Aerosol, Cloud, ocean Ecosystem (PACE) satellite** launched on **February 8, 2024**, and has been gathering vital data about Earth’s oceans and atmosphere since **April 11, 2024**. Through NASA’s open science policy, this data is available to the public, but understanding it can be challenging for those unfamiliar with it.

Our project aims to bridge this gap by developing kid-friendly, engaging materials that teachers can use across various grade levels. We’re focusing on turning PACE’s scientific data, gathered from instruments like the **Ocean Color Instrument (OCI)**, **SPEXone polarimeter**, and **Hyper-Angular Rainbow Polarimeter #2 (HARP2)**, into resources that spark curiosity and foster ocean literacy. These materials will showcase the importance of phytoplankton, ocean-atmosphere exchanges, aerosols, and more, making complex topics accessible to young learners.

### Summary

The Plankton, Aerosol, Cloud, ocean Ecosystem (PACE) satellite, launched by NASA, is designed to collect critical data about Earth's oceans and atmosphere. PACE is a cutting-edge mission aimed at advancing our understanding of the role that ocean ecosystems and atmospheric particles (like aerosols and clouds) play in regulating Earth's climate.

With NASA's open science policy, all of the data collected by the PACE satellite is publicly available. However, the highly technical nature of this data makes it difficult for those outside the scientific community, especially students, to grasp its full significance. This is where our project comes in.

Our challenge is to create accessible, digestible educational materials that bring this complex data to life. We aim to transform the scientific information gathered by PACE into kid-friendly, interactive content that can be seamlessly integrated into classroom curriculums worldwide. By doing so, we hope to:

- Improve ocean literacy and climate science education globally.
- Inspire the next generation of students to explore Earth sciences.
- Provide teachers with powerful tools to explain the importance of ocean-atmosphere interactions, the impact of phytoplankton, and other key components of our planet's ecosystems.
  
Through interactive visualizations, simplified lessons, and engaging content, our project will help students of all ages understand the significance of the data PACE is collecting, sparking curiosity and promoting a deeper understanding of how the Earth’s oceans and atmosphere work together to sustain life.

---

## Impact

By providing educators with these interactive, easy-to-use tools, we aim to:
- Increase ocean literacy in classrooms worldwide.
- Inspire curiosity about Earth sciences and climate change among students.
- Enable students to explore real-time data in a way that’s approachable and fun.

---

## Challenge Faced & Solution

- **Challenge**: Making NASA's complex PACE data engaging for younger audiences.
  
  **Solution**: Simplified visualizations and lesson materials tailored for different age groups, ensuring concepts are both fun and educational.

- **Challenge**: Data is too huge to store in limited cloud storage of all free platform.
  
  **Solution**: Down Sample the data for reducing its size.

- **Challenge**: Taking time to rendering the globe of concentration.
  
  **Solution**:  Added caching that reduced rendering time.

- **Challenge**: Reloading problem when switching from three.js model tab to other tab
  
  **Solution**: Removed the dom element manipulating function and added a proper disposal function.

- **Challenge**: During the development of the PACE web app, I faced a significant challenge while rendering data on a globe using Three.js. I encountered a "stack size exceeded" error, which stemmed from improperly handled data values that resulted in excessive memory consumption during the rendering process.

  **Solution**: To address this issue, I utilized the maximum and minimum values specified in the metadata for each data type, including chlorophyll concentration, sea surface temperature, and carbon concentration. By hardcoding these valid ranges into my code, I ensured that all data values remained within these limits. This approach effectively mitigated the stack overflow error, allowing for successful rendering of the globe and a smoother user experience.

---

## Tools We Use

- **Frontend**: React + Vite, Three.js, Node.js
- **Backend**: Python-Flask
- **Database / Cloud Storage**: MongoDB Atlas
- **Data / Files**: [PACE Ocean Data API](https://oceandata.sci.gsfc.nasa.gov/api/file_search/)
- **AI Tools**: ChatGPT, Leonardo AI
- **Frontend Honsing**: Vercel
- **Bakcend Hosting**: GCP
- **Domain managere**: Porkbun.com

---

## Features

- Interactive 3D Earth visualization using Three.js
- Videos for understanding how PACE is collecting data
- Explore detailed information on PACE's scientific instruments
- Kid-friendly lesson pages with engaging materials
- Easy navigation through data visualizations
- Simulation for understanding marine life in different atmosphere

---

## Installation & Setup

- **Clone the Repository:** 

```bash
git clone [repository link]
```

- **Backend:** 

```bash
cd path_to_folder\Hackathon-Team-Cipher\my-app\backend
```

```bash
pip install flask pymongo flask_cors
```

```bash
python .\app.py
```

 - **Frontend:** 

```bash
cd path_to_folder\Hackathon-Team-Cipher\my-app\frontend\pace-in-the-classroom
```

```bash
npm install
```

```bash
npm run dev
```

---

## Application

### Home page:

- Interactions with Earth globe.

  ![Home Page (1)](https://github.com/user-attachments/assets/9d1af1c4-691b-4bb6-90ae-9c5aa4c2258a)

  ![Home Page (3)](https://github.com/user-attachments/assets/f0198700-5575-4e7a-a408-f732bdcc732f)


### Explore page:

- Learn more about Ocean Colour Intrument, SPEXone Polarimeter, HARP2 Polarimeter.

  ![Explore Page](https://github.com/user-attachments/assets/df82cf2d-3585-43a4-8401-f6d79e24b797)


### Lesson page:

- Learn about PACE, Pace's Scientific Instrument, The Ocean-Atmosphere Intraction with simulation.

  ![Lessons Page](https://github.com/user-attachments/assets/990a2d3b-73f8-48c3-82e3-f404717aa329)

  ![Lesson1 Page (1)](https://github.com/user-attachments/assets/0d70d257-a0cc-4b2f-9afb-d13992c5617a)

  ![Lesson2 Page](https://github.com/user-attachments/assets/26a2a2fd-89b2-4d06-8372-f447db773bc5)

  ![Lesson3 Page](https://github.com/user-attachments/assets/38e20309-395b-4e0c-a4b9-4f68857219a5)

### Maps:

- 2D Map & 3D Interactive Globe, which will show the concentration of Chlorophyll, Carbon & Sea Surface Temperature.

  ![Map Page](https://github.com/user-attachments/assets/8f760cb1-95e6-472e-9ad5-8d20cc8f4219)

### Community Page:

- You can commit and see what other has commited.

  ![Community Page](https://github.com/user-attachments/assets/37bf811c-2685-4c3f-a2c4-873105f5e801)

---

## Team

### Members:

- **Devanshu Mangal** - Frontend + Backend
- **Ronit Rathod** - Backend + Database, Video Editor
- **Dhairya Prajapati** - Frontend
- **Manan Tarsariya** - Backend + Literature Survey
- **Jit Prajapati** - Website Deployment
- **Jainex Pumbhadiya** - Website Deployment

### Mentors:

- **Mr. Nishant Painter** - CEO & Founder, Shivantra.
- **Prof. (Dr.) Bintu Kadhiwala** - Assistant Professor, Computer Department, SCET.

### Special Thanks:

- Special thanks to **Prof. Dhatri Pandya** for her guidance - Assistant Professor, Computer Department, SCET.
- Thanks to **NASA** for providing access to the PACE satellite data, enabling this project.

---

