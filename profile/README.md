<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=OtakAtik%20Robotics&fontSize=60&fontAlignY=38&desc=Computer%20Engineering%20|%20AI%20|%20Robotics&descAlignY=60&descAlign=50" width="100%" />
</div>

<h1 align="center">🤖 Welcome to OtakAtik Robotics</h1>

<p align="center">
  <strong>Building the Future of Education through Robotic Interaction &amp; Artificial Intelligence</strong>
</p>

<p align="center">
  <a href="https://projectidek.dev">🌐 Website</a> &nbsp;•&nbsp;
  <a href="#-featured-project">🚀 Project</a> &nbsp;•&nbsp;
  <a href="#-repositories">📦 Repositories</a> &nbsp;•&nbsp;
  <a href="#-tech-stack">🛠️ Tech Stack</a> &nbsp;•&nbsp;
  <a href="#-contact">📬 Contact</a>
</p>

<br/>

---

## 💡 About Us

We are a technology initiative driven by **Computer Engineering** students at **Politeknik Elektronika Negeri Surabaya (PENS)**, under the guidance of **Adnan Rachmat Anom Besari S.ST., M.Sc., Ph.D.**

**OtakAtik Robotics** focuses on developing interactive robotic systems for education. We combine **Computer Vision**, **Artificial Intelligence**, and **Gamification** to create engaging learning experiences and cognitive assessments for children and students.

> 🧒 Ages 3+ &nbsp;|&nbsp; 🏫 All education levels &nbsp;|&nbsp; 🧠 YOLO + MediaPipe + LLM-powered

<br/>

---

## 🚀 Featured Project

### 🧩 Otak Atik Merah Putih (OAMP)

An automated cognitive and dexterity analysis system built on interactive robotic gameplay.

<table>
<tr>
<td width="50%">

**🎮 Block Design Test (BDT) — Desktop Client**
- CustomTkinter native GUI application
- Real-time hand detection via YOLO &amp; MediaPipe
- ESP32 physical button integration
- Multiplayer duel &amp; tournament cup mode
- Offline-capable with fire-and-forget API sync

</td>
<td width="50%">

**🌐 Web Dashboard + REST API**
- React 19 admin panel with real-time leaderboard
- Midtrans (QRIS) payment gateway
- AI-powered health reports via multi-provider LLM
- Telegram bot notifications on payment settlement
- PostgreSQL + websocket duel match spectating

</td>
</tr>
</table>

<br/>

---

## 📦 Repositories

```mermaid
graph LR
    A[BDT Desktop<br/>Python/CustomTkinter] -->|REST + WebSocket| B[Backend Server<br/>Go/Gin/PostgreSQL]
    C[Web Dashboard<br/>React/Vite/Tailwind] -->|REST API| B
    B -->|Webhook| D[Midtrans Payment]
    B -->|Notify| E[Telegram Bot]
    B -->|Analyze| F[LLM Providers]
```

<br/>

| Repo | Status | Description |
|------|--------|-------------|
| 🔓 **[oamp-bdt-dekstop-app-python](https://github.com/OtakAtik-Robotics/oamp-bdt-dekstop-app-python)** | `Public` | Desktop game client — YOLO hand detection, MediaPipe tracking, tournament cup mode |
| 🔒 **oamp-backend** | `Private` | Golang/Gin core server — CRUD, WebSocket duels, Midtrans webhooks, LLM health reports |
| 🔒 **oamp-frontend** | `Private` | React 19 + Vite 8 dashboard — leaderboard, tournaments, AI report Markdown rendering |

<br/>

<div align="center">
  <a href="https://github.com/OtakAtik-Robotics/oamp-bdt-dekstop-app-python">
    <img height="150" src="https://github-readme-stats.vercel.app/api/pin/?username=OtakAtik-Robotics&repo=oamp-bdt-dekstop-app-python&theme=radical&bg_color=0D1117&border_color=30363D" alt="BDT Desktop" />
  </a>
</div>

<br/>

---

## 🛠️ Tech Stack

<table align="center">
<tr>
<td align="center" width="25%">

### 🧠 Edge AI &amp; Robotics

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Ultralytics](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![CustomTkinter](https://img.shields.io/badge/CustomTkinter-1F6FEB?style=for-the-badge&logo=python&logoColor=white)

</td>
<td align="center" width="25%">

### ⚙️ Backend

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![GORM](https://img.shields.io/badge/GORM-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Midtrans](https://img.shields.io/badge/Payment-Midtrans-1E3A8A?style=for-the-badge)

</td>
<td align="center" width="25%">

### 🎨 Frontend

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logo=recharts&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_v7-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)

</td>
<td align="center" width="25%">

### 🚀 DevOps &amp; Infra

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Playwright](https://img.shields.io/badge/E2E-Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Telegram](https://img.shields.io/badge/Notify-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

</td>
</tr>
</table>

<br/>

---

## 📬 Contact &amp; Demo

| | |
|---|---|
| 🌐 **Dashboard** | [projectidek.dev](https://projectidek.dev) |
| 📧 **Email** | [root@ce.student.pens.ac.id](mailto:root@ce.student.pens.ac.id) |
| 🏫 **Institution** | Politeknik Elektronika Negeri Surabaya |

<br/>

<div align="center">
  <br/>
  <em>"Why use many word when few do trick." — The Dev Team 🪨🔥</em>
  <br/><br/>
  <sub>© 2026 OtakAtik Robotics — PENS Computer Engineering</sub>
</div>
