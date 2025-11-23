# 👋 Hi, I'm Mark  

Documenting my **homelab journey**, server builds, and self-hosted services.  
Learning **DevOps fundamentals** by running real infrastructure on my own hardware.

---

# 🧩 What I'm Working On

## 🖥️ Self-Hosted Home Server (Debian)
Running:

- **Nextcloud** (private cloud)  
- **Immich** (photo backup)  
- **Nginx reverse proxy**  
- **Cloudflare SSL / DNS**  
- **Custom Telegram monitoring** (Bash + systemd)

Everything deployed with **Docker & Docker Compose**, hardened with firewall rules, and automated with scripts.

---

# 🛠️ Technologies & Tools

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?logo=debian&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Compose](https://img.shields.io/badge/Docker_Compose-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Networking](https://img.shields.io/badge/Networking-0066CC)

---

# 🏗️ Homelab Architecture

```
                    Internet
                        │
                🌐 Cloudflare Proxy
                        │
                ┌───────▼───────┐
                │   Nginx Proxy  │
                └───────┬───────┘
        ┌───────────────┼────────────────┐
        │               │                │
   Nextcloud        Immich       Telegram Monitor
  (Docker)         (Docker)      (Bash + systemd)
```

---

# 🧰 Hardware

- **OS:** Debian 12  
- **Reverse proxy:** Nginx  
- **DNS & SSL:** Cloudflare  
- **Monitoring:** Telegram bot + systemd timer  
- **Deployment:** Docker & Docker Compose  

---

# 📌 Featured Projects

- **Home-Server-Debian** — main homelab setup  
- **docker-compose-immich** — Immich deployment  
- **docker-compose-nextcloud** — Nextcloud deployment  
- **telegram-server-monitor** — Bash monitoring script  

(These are pinned on my profile.)

---

# 🎯 Why I'm Doing This

To learn real DevOps skills by managing my own infrastructure:

- Docker  
- Linux  
- Networking  
- Reverse proxy  
- SSL  
- Automation  
- Monitoring  

Instead of just reading theory.
