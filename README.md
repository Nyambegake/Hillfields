# Hillfields Premier Academy & Junior School Website

A production-ready Flask web application built for Hillfields Premier Academy & Junior School, Kisii, Kenya.

This platform is designed to align with Kenya’s Competency-Based Curriculum (CBC) and Competency-Based Education (CBE) frameworks as guided by KICD and the Ministry of Education.

---

## Features

- Responsive institutional website
- CBC compliance hub
- Faculty governance portal
- Student admissions system
- Competency-based assessment interface
- Interactive rubric modal system

---

## Project Structure

```bash
hillfields-academy/
│
├── app.py
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── cbc_framework.html
│   ├── faculty.html
│   └── enroll.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
```

---

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/hillfields-academy.git
cd hillfields-academy
```

### 2. Create Virtual Environment

Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install flask
```

or

```bash
pip install -r requirements.txt
```

---

## Running the Application

```bash
python app.py
```

Application runs on:

```bash
http://127.0.0.1:5000/
```

---

## Routes

| Route | Description |
|-------|-------------|
| `/` | Home Page |
| `/cbc-framework` | CBC Compliance Hub |
| `/faculty` | Faculty & Governance |
| `/enroll` | Admissions Portal |

---

## Core Technologies

### Backend
- Flask
- Python

### Frontend
- HTML5
- CSS3
- Tailwind CSS
- JavaScript

---

## CBC Alignment

This project supports the 7 core CBC competencies:

- Communication & Collaboration
- Critical Thinking & Problem Solving
- Creativity & Imagination
- Citizenship
- Digital Literacy
- Learning to Learn
- Self-Efficacy

---

## Future Improvements

- Admin dashboard
- Learner digital portfolio system
- Teacher assessment uploads
- CBC reporting analytics
- Parent portal login

---

## Compliance

This system aligns with:
- Ministry of Education, Kenya
- Kenya Institute of Curriculum Development (KICD)
- CBC/CBE implementation guidelines

---

## Author

Developed as a full-stack educational technology solution for:

Hillfields Premier Academy & Junior School  
Kisii, Kenya
