<h1 align="center" style="font-size: 120px;"><strong>Team: Space Cipher</strong></h1>

---

## Contents:

- [Introduction](#introduction)
- [Team](#team)
  - [Members](#members)
  - [Mentors](#mentors)
  - [Special Thanks](#special-thanks)
- [Challenge](#challenge-pace-in-the-classroom)
  - [Challenge Overview](#challenge-overview)
- [Impact](#impact)
- [Challenge Faced & Solution](#challenge-faced--solution)
- [Tools We Use](#tools-we-use)
- [Features](#features)
- [Installation & Set up](#installation--setup)
- [Project Demo](#project-demo)
  - [Home Page](#home-page)
  - [Explore Page](#explore-page)
  - [Lesson Page](#lesson-page)

---

## Introduction

This project aims to bridge the gap between complex satellite data from NASA’s PACE mission and educational resources, making oceanic and atmospheric data more accessible to students of various age groups. Through engaging tools and lessons, we hope to spark curiosity and foster a deeper understanding of ocean literacy.

---

## Team

### Members:

- Devanshu Mangal
- Ronit Rathod
- Dhairya Prajapati
- Manan Tarsariya
- Jit Prajapati
- Jainex Pumbhadiya

We are group of 2nd Year, Computer Engineering Student, SCET

### Mentors:

- **Mr. Nishant Painter** - CEO & Founder, Shivantra.
- **Prof. (Dr.) Bintu Kadhiwala** - Assistant Professor, Computer Department, SCET.

### Special Thanks:

- Special thanks to **Prof. Dhatri Pandya** for her guidance - Assistant Professor, SCET.
- Thanks to **NASA** for providing access to the PACE satellite data, enabling this project.

---

## Challenge: PACE IN THE CLASSROOM

We are working on the **Pace in the Classroom** challenge, which focuses on making complex data from NASA’s PACE satellite accessible and engaging for students worldwide. Our goal is to create digestible educational materials that help integrate this data into classroom curriculums, improving ocean literacy globally.

### Challenge Overview

The **Plankton, Aerosol, Cloud, ocean Ecosystem (PACE) satellite** launched on **February 8, 2024**, and has been gathering vital data about Earth’s oceans and atmosphere since **April 11, 2024**. Through NASA’s open science policy, this data is available to the public, but understanding it can be challenging for those unfamiliar with it.

Our project aims to bridge this gap by developing kid-friendly, engaging materials that teachers can use across various grade levels. We’re focusing on turning PACE’s scientific data, gathered from instruments like the **Ocean Color Instrument (OCI)**, **SPEXone polarimeter**, and **Hyper-Angular Rainbow Polarimeter #2 (HARP2)**, into resources that spark curiosity and foster ocean literacy. These materials will showcase the importance of phytoplankton, ocean-atmosphere exchanges, aerosols, and more, making complex topics accessible to young learners.

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

---

## Tools We Use

- **Frontend**: React + Vite
- **Backend**: Node.js
- **Visualization Tool**: Three.js
- **Database / Cloud Storage**: MongoDB Atlas
- **Data / Files**: [PACE Ocean Data API](https://oceandata.sci.gsfc.nasa.gov/api/file_search/)
- **AI Tools**: ChatGPT, Leonardo AI

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

## Project Demo

### Home page:

- Interactions with Earth globe.

  ![Home Page](https://github.com/user-attachments/assets/c4cc9299-7f8a-420b-9e41-669515c7413f)

 
### Explore page:

- Learn more about Ocean Colour Intrument, SPEXone Polarimeter, HARP2 Polarimeter.

  ![Explore Page](https://github.com/user-attachments/assets/df82cf2d-3585-43a4-8401-f6d79e24b797)


### Lesson page:

- Learn about PACE, Pace's Scientific Instrument, The Ocean-Atmosphere Intraction with simulation.

  ![Lesson1 Page (1)](https://github.com/user-attachments/assets/0d70d257-a0cc-4b2f-9afb-d13992c5617a)

  ![Lesson2 Page](https://github.com/user-attachments/assets/26a2a2fd-89b2-4d06-8372-f447db773bc5)

  ![Lesson3 Page](https://github.com/user-attachments/assets/38e20309-395b-4e0c-a4b9-4f68857219a5)
