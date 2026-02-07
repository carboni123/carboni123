# Diego Carboni

Full-stack engineer. I build AI-powered products, embedded systems, and way too many side projects.

Python, TypeScript, FastAPI, React, Docker, Raspberry Pi, ESP32 — whatever gets the job done.

Currently working on: **Meu Assistente IA**, **Tyxter Studio**, **LLM Factory Toolkit**, **MyVirtualCompany**

## Private Projects (rated by Claude Opus 4.6)

### Flagships

| Project | What it does | Stack | Rating |
|---------|-------------|-------|--------|
| **Meu Assistente IA** | Multi-tenant WhatsApp CRM platform with AI assistants, automations, campaigns, deals pipeline, billing, copilot chat, LLM agents, and 60+ feature modules. My biggest project. | FastAPI, React 19, PostgreSQL, Redis, Celery, Twilio, Stripe | 9/10 |
| **Tyxter Studio** | Platform for creating AI-powered WhatsApp apps from natural language descriptions. Template catalog, sandbox testing with phone-frame UI, multi-agent routing, Stripe billing, publish lifecycle. | FastAPI, React 19, Vite, Tailwind 4, OpenAI, Twilio, Redis | 9/10 |
| **RentalAI Concierge** | SaaS for rental property mediation. AI conversational agent + human ops dashboard with omnichannel support (WhatsApp, email, web), RAG knowledge base, tri-party mediation, and LGPD compliance. | FastAPI, PostgreSQL, pgvector, React, Kubernetes | 8/10 |

### AI & LLM Tools

| Project | What it does | Stack | Rating |
|---------|-------------|-------|--------|
| **LLM Factory Toolkit** | Published Python package for 100+ LLM providers through a unified interface. Dynamic tool loading, context injection, nested tool execution, mock mode, intent planning. | Python, LiteLLM, asyncio | 8/10 |
| **AI Book Generator** | Autonomous book writing system with writer and reviewer agents in a feedback loop. The writer generates content, the reviewer scores and critiques it, and the cycle repeats until quality gates pass. | Python, OpenAI, Deepseek, Pydantic | 7/10 |

### WhatsApp Infrastructure

| Project | What it does | Stack | Rating |
|---------|-------------|-------|--------|
| **WW.js Adapter** | Multi-session WhatsApp API gateway. Manages multiple WhatsApp accounts simultaneously with persistent sessions in PostgreSQL, REST endpoints, and webhook event streaming. | Node.js, TypeScript, Express, PostgreSQL, Docker, Drizzle | 8/10 |
| **Meu Assistente IA Retail** | Retail integrations microservice that polls Shopify and Yampi, pushes customer/lead events into the CRM via webhooks, with M2M JWT auth and RSA-encrypted credential handling. | FastAPI, Shopify API, Yampi API, PostgreSQL, Docker | 7/10 |

### Infrastructure & Security

| Project | What it does | Stack | Rating |
|---------|-------------|-------|--------|
| **VPS Encrypted Server** | Full provisioning toolkit for hardened, encrypted-at-rest VPS from bare Debian. LUKS encryption, Dropbear SSH remote unlock, Clevis/Tang auto-unlock, UFW, Fail2Ban, Tailscale VPN, Docker. | Debian, LUKS, Dropbear, Clevis/Tang, Tailscale | 8/10 |
| **Pi Encrypted Server** | Raspberry Pi 5 hybrid boot: SD card kernel + LUKS-encrypted SSD root filesystem. Email alerts on reboot, debootstrap guest chroot, Docker in encrypted environment. | LUKS, debootstrap, rsync, Docker, msmtp | 7/10 |

### IoT & Embedded

| Project | What it does | Stack | Rating |
|---------|-------------|-------|--------|
| **WiFi Presence** | Indoor presence detection using ESP32 WiFi Channel State Information (CSI). Moved past RSSI to per-subcarrier amplitude/phase analysis for reliable human detection without cameras. | C (ESP-IDF), Python, MQTT | 6/10 |

### Other ideas

| Project | What it does | Stack | Rating |
|---------|-------------|-------|--------|
| **OrderFlow** | Order management platform for service-based businesses. Quotes, receipts, customer notifications, and manager dashboards with analytics. | TypeScript, React, Node.js | 6/10 |

---

## Previous Work — Savefarm (2022-2025)

One-man-army at [Savefarm](https://github.com/eirenesolutions) (agtech). Built features and maintained the entire
embedded software stack for precision agriculture spraying sensors running on Raspberry Pi. Computer
vision, CAN bus communication, valve control, encrypted OS images — all of it.

| Project | What it does | Stack |
|---------|-------------|-------|
| **Savefarm Main** | Firmware for precision spraying sensors. Green detection via OpenCV (HLS segmentation), multi-nozzle valve control over GPIO, CAN bus comms with the vehicle, PiCamera streaming, curve compensation. Runs on Raspberry Pi mounted on agricultural equipment. | Python, OpenCV, PiCamera, CAN bus, GPIO |
| **SavefarmOS** | Encrypted Debian image for field sensors. LUKS root partition with hardware-bound auto-unlock, firmware compiled to `.so` for IP protection, USB/HDMI disabled. The kind of thing you build when your client wants copy protection but won't pay for proper hardware security. | Debian, LUKS, initramfs |
| **Savefarm Watering** | Fork adapted for precision irrigation. Detects seedlings and triggers watering via GPIO. Timer-based valve control, PID saturation tuning. | Python, OpenCV, PiCamera, CAN bus, GPIO |

---

*Most of these are private repos. If something interests you, reach out.*

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=carboni123&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true" alt="Stats" />
</p>
