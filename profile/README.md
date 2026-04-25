<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=OtakAtik%20Robotics&fontSize=60&fontAlignY=38&desc=Computer%20Engineering%20|%20AI%20|%20Robotics&descAlignY=60&descAlign=50" width="100%" />
</div>

<h1 align="center">🤖 Welcome to OtakAtik Robotics</h1>

<p align="center">
  <em>Building the Future of Education through Robotic Interaction & Artificial Intelligence</em>
</p>

<p align="center">
  <a href="https://projectidek.dev">Website</a> •
  <a href="#about-oamp">About OAMP</a> •
  <a href="#repositories">Repositories</a> •
  <a href="#tech-stack">Tech Stack</a>
</p>

---

## 💡 About Us

We are a technology initiative driven by **Computer Engineering** students, under the guidance of **Adnan Rachmat Anom Besari S.ST., M.Sc., Ph.D.** **OtakAtik Robotics** focuses on developing interactive robotic systems for education. We combine Computer Vision, Artificial Intelligence, and Gamification to create engaging learning experiences and cognitive assessments for children and students.

---

## 🚀 Featured Project: OAMP

<h3 id="about-oamp">Otak Atik Merah Putih (OAMP)</h3>

OAMP is an automated cognitive and dexterity analysis system built on top of interactive robotic gameplay. 
* **Hardware Integration:** Instant participant identification using RFID tap cards.
* **Computer Vision (Edge):** Real-time facial expression and hand gesture tracking (e.g., *Hidden Thumbs Up/Peace Sign* level skips).
* **AI Analysis:** Generates personalized development reports and health advice neatly formatted by Large Language Models (LLMs).
* **Monetization Engine:** Seamless Pay-upfront integration via Midtrans (QRIS) before gameplay begins.

---

## 📦 Our Repositories

<h3 id="repositories"></h3>

We divide our ecosystem into microservices to ensure scalability. Here is the architecture of the OAMP system:

* 🔓 **[oamp-ai](https://github.com/OtakAtik-Robotics/oamp-ai)** `[Public]`
  The Edge AI client running on the robot. Handles OpenCV camera feeds, Mediapipe hand/face tracking, offline SQLite buffering, and seamless communication with the backend.
  
* 🔒 **oamp-backend** `[Private]`
  The core Golang/Gin server. Handles REST APIs, Midtrans webhook security (SHA512), PostgreSQL databases, connection pooling, and real-time Telegram bot notifications.

* 🔒 **oamp-frontend** `[Private]`
  The modern React + Vite dashboard. Features dynamic Markdown rendering for AI reports, Midtrans Snap popups, and secure access boundaries.

<div align="center">
  <br/>
  <a href="https://github.com/OtakAtik-Robotics/oamp-ai">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=OtakAtik-Robotics&repo=oamp-ai&theme=radical&bg_color=0D1117&border_color=30363D" alt="OAMP AI Repo" />
  </a>
</div>

---

## 🛠️ Tech Stack

<div align="center">
  
  ### 🧠 Edge AI & Robotics
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
  ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

  ### ⚙️ Backend Services
  ![Golang](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
  ![Gin](https://img.shields.io/badge/Gin%20Framework-00ADD8?style=for-the-badge&logo=gin&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
  ![Midtrans](https://img.shields.io/badge/Payment-Midtrans-blue?style=for-the-badge)

  ### 🎨 Frontend Dashboard
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

  ### 🚀 DevOps
  ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
  ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
  ![Telegram](https://img.shields.io/badge/Bot_Notifier-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

</div>

---

## 📬 Contact & Demo

Interested in our architecture or want to see the robot in action?
* 🌐 **Dashboard:** [https://projectidek.dev](https://projectidek.dev)
* 📞 **Contact:** [root@ce.student.pens.ac.id](root@ce.student.pens.ac.id)

<p align="center">
  <br/>
  <em>"Why use many word when few do trick." - The Dev Team 🪨🔥</em>
</p>
