<div align="center">

# Temurbek Rakhimkuliev
### Backend & Edge AI Engineer

*Designing and delivering real-time systems — from embedded edge devices and computer vision pipelines to scalable backend services and production infrastructure.*

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Timurxboy)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/temurbek-rakhimkuliev-344b9b20a/)
[![Email](https://img.shields.io/badge/timurxboy%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:timurxboy@gmail.com)

📍 Tashkent, Uzbekistan &nbsp;·&nbsp; 3+ Years Backend Experience

</div>

---

## 🚀 Impact Metrics

<div align="center">

| 3–5× | ≈0% | 30–50% | 10+ |
|:---:|:---:|:---:|:---:|
| Faster GPS time-series queries | Data loss during network failures | API response time reduction | Telegram bots deployed |
| PostgreSQL time-based partitioning | MQTT batching & auto-reconnect | SQL optimisation & Redis caching | Aiogram + 3rd-party APIs |

</div>

---

## 🏗 Key Projects

<details>
<summary><b>🚦 Distributed Traffic Violation Detection System</b> — DriveLens AI</summary>

<br>

```
Edge Device (Jetson/RPi) → MQTT Broker → Kafka Pipeline → FastAPI Backend → PostgreSQL + S3 → Notifications
```

- Real-time RTSP stream processing with optimised inference on **NVIDIA Jetson** & **Raspberry Pi**
- MQTT ingestion with batching and auto-reconnect — **near-zero data loss**
- Kafka event-driven pipeline: media → detection → plate recognition → violation entity
- PostgreSQL **time-based partitioning** for GPS telemetry **(3–5× faster queries)**
- Automated S3 retention management (last N days) — reduced storage costs
- Ubuntu Server production deployment with Supervisor-based auto-recovery

</details>

<details>
<summary><b>📍 Real-Time GPS Parking Zone Monitoring (Geofencing)</b> — DriveLens AI</summary>

<br>

```
GPS Telemetry → MQTT → Geofence Service → Camera Trigger → Plate Recognition → Notification + Storage
```

- Real-time GPS coordinate monitoring and parking zone boundary detection
- Trigger-based camera activation for automatic license plate recognition
- Automated violation identification for unauthorised vehicles
- Instant notification delivery to violators

</details>

<details>
<summary><b>📊 High-Throughput GPS Telemetry Storage Layer</b> — DriveLens AI</summary>

<br>

```
Vehicle Devices → MQTT Broker → Ingestion Service → Partitioned PostgreSQL → Auto Cleanup
```

- Automatic monthly PostgreSQL partition creation for time-series GPS data
- Optimised range queries with composite indexing strategies
- Automated partition lifecycle management — **zero manual DBA maintenance**
- Stable performance under continuous high-frequency inserts

</details>

---

## 💻 Tech Stack

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-blueviolet?style=for-the-badge&logo=django&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-FF2D55?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-cccccc?style=for-the-badge&logo=sqlalchemy&logoColor=d71f27)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

**Computer Vision & Edge**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Ultralytics](https://img.shields.io/badge/Ultralytics_YOLO-111111?style=for-the-badge&logo=yolo&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📈 Career Timeline

```
Apr 2022 ──► DY                  Backend Developer       (Python, Go, Kafka, RabbitMQ)
Apr 2023 ──► Next Level Group    Backend Developer       (Django, DRF, Redis, Telegram bots)
Mar 2024 ──► UZINFOCOM           Backend Developer       (Django, DRF, Redis, PostgreSQL)
Sep 2024 ──► Freelance           Software Engineer       (FastAPI, Aiogram, Docker, Redis)
Jun 2025 ──► DriveLens AI        SW & HW Engineer  ◄──  (Edge AI, Kafka, MQTT, Jetson, FastAPI)
```

---

## ⚙️ GitHub Analytics

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Timurxboy&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=Timurxboy&show_icons=true&locale=en&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />

</div>

---

<div align="center">
<sub>📍 Tashkent, Uzbekistan · Open to remote opportunities</sub>
</div>
