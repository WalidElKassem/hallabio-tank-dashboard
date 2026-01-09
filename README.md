# HallabIO Tank Dashboard

This repository hosts the **production dashboard UI** for the HallabIO tank monitoring system.

It is deployed using **GitHub Pages** and provides a **stable, read-only interface** for viewing tank levels and alerts.

---

## 🎯 Purpose

- Display current tank level (%)
- Show historical data (last 5 days)
- Show low-level alerts (<20%)
- Allow on-demand “Read now” requests

This UI is intended for **real operational use**.

---

## 🔌 Backend Connection

Production API endpoint (planned):
https://tank-api.hallabio.com/api


During early testing, this repository may temporarily point to the DEV API.

---

## 🔐 Security

- UI is static and publicly hosted
- All API access is protected by backend authentication
- No credentials or device keys are stored here

---

## 📦 Repository Contents

hallabio-tank-dashboard/
├─ index.html
├─ config.json
├─ assets/
└─ README.md


---

## 🚦 Release Policy

- Only validated changes from DEV are promoted here
- This repository should remain stable
- Rollbacks are handled by reverting Git commits

---

## 🛠 Maintenance Philosophy

- No backend logic lives here
- No device logic lives here
- This UI should be simple, predictable, and boring

---

## 🏷 License
TBD
