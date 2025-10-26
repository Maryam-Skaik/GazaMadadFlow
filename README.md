# Gaza Madad Flow 🌍

A Web Automation Model for Humanitarian Aid Registration in Gaza

Gaza Madad Flow is an open-source Laravel-based system designed to **automate humanitarian aid registration** during crisis conditions such as the 2023 Gaza war.  
The system allows citizens to **register once** and automatically sends their validated data to multiple aid platforms using n8n workflow automation — reducing manual work, data duplication, and access barriers.

---

## 🚨 Problem

After the 2023 war in Gaza, families faced:
- Power outages and unstable internet access.
- Repetitive and confusing registration processes across many aid links.
- Fake and unsafe registration sites.

This made it nearly impossible for vulnerable families to register for essential assistance.

---

## 🎯 Objectives

- Build a one-time registration system for all aid programs.
- Automate data delivery to multiple humanitarian platforms.
- Use web automation and integration tools that work even under weak connectivity.
- Demonstrate how technology can make a difference in humanitarian crises.

---

## ⚙️ Tech Stack

| Category | Tools Used |
|-----------|------------|
| Backend | Laravel (PHP Framework) |
| Database | PostgreSQL |
| Automation | n8n (Cloud Workflow Automation) |
| Data Sync | Google Sheets + API |
| Hosting | Render |
| Scheduler | UptimeRobot (Free Cron Alternative) |
| Frontend | HTML, CSS, TailwindCSS, JavaScript |
| Version Control | GitHub |
| IDE | Visual Studio Code |

---

## 🧩 Workflow Overview

The automation workflow performs:

1. Read citizen data from Google Sheets.
2. Extract HTML forms from multiple aid links.
3. Normalize and map fields (name, ID, family, housing data, etc.).
4. Submit forms automatically using authenticated HTTP requests.
5. Log and update status for each processed record.

> This workflow demonstrates multi-platform submission using `n8n`’s Google Sheets and HTTP Request nodes, supporting both Arabic and English aid sites.

---

## 🧪 Features

- ✅ One-time validated registration (no repeated entries)
- 🔄 Automated data transfer to multiple platforms
- 💾 Real-time synchronization with Google Sheets
- ☁️ Deployed online using Render
- 🕒 Hourly auto-sync via UptimeRobot
- 🧱 Scalable for integration with official humanitarian systems

---

## 🎥 Demo Video

You can watch a **5-minute recorded demo** showing how Gaza Madad Flow works — from user registration to automated aid submission.

👉 [Watch the demo video on Google Drive](https://drive.google.com/file/d/1ZreM2pKKVkd-3sbBusxV4m_aCDzeRyRs/view)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Maryam-Skaik/Gaza_Madad_FLow.git
   cd Gaza_Madad_FLow
2. Install dependencies:
    ```bash
    composer install
    npm install
3. Configure .env with your database and API keys.
4. Run migrations:
    ```bash
    php artisan migrate
5. Start the server:
    ```bash
    php artisan serve
6. Import or rebuild the workflow inside your n8n Cloud or local instance if you wish to automate data flow.

---

## 📊 Results

Testing showed:

- 80% reduction in manual data entry time.
- Seamless multi-platform submission even under weak connectivity.
- Reliable synchronization and data integrity verified through Google Sheets logs.

---

## 🤝 Team

- Maryam Refaa Skaik
- Rania Raid Kashkask
- Aya Nabil Alharazin
- Misk Saad Ashour
- Alaa Shareef Yousef

Supervisor: Eng. Mohammed El-Agha
Faculty of Information Technology – Islamic University of Gaza (2025)

---

## 📜 License

Released under the MIT License — feel free to use, modify, and improve with credit.

---

## ❤️ Acknowledgment

This project was developed during the ongoing crisis in Gaza, with the hope that technology can make a real difference in people’s lives.

> “Technology can be a bridge to humanity when everything else falls apart.”
