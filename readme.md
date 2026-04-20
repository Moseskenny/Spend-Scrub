<p align="center">
  <img width="200" height="200" alt="Remove background project" src="https://github.com/user-attachments/assets/ce2ed3d6-d49e-44f5-a50f-461ba1bc12a5" />

</p>

<p align="center">
  <strong>The high-performance, local-first finance engine.</strong><br />
  <em>Minimalist Design. Maximum Privacy. No Cloud Required.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active_Development-emerald?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Platform-Windows_%7C_macOS-white?style=for-the-badge&logo=windows" alt="Platforms" />
  <img src="https://img.shields.io/badge/Stack-React_|_Tauri_|_Rust-orange?style=for-the-badge" alt="Stack" />
</p>

---

## 🛡️ Identity & Philosophy
SpendScrub is built for those who demand a premium aesthetic without compromising their financial privacy. Inspired by the sharp, high-contrast design language of brands like **Nike** and **Puma**, SpendScrub treats money tracking like a performance sport—fast, precise, and sleek.

Unlike traditional finance apps, SpendScrub is **Local-First**. Your data never hits a central server. Everything stays on your device, encrypted and under your control.

## 🚀 Key Features

### 1. The MagicBar (NLP Engine)
Stop filling out tedious forms. SpendScrub features a custom-built Natural Language Processing engine. Just type and enter:
* **"100 coffee"** → Logs $100 under Food/Drinks.
* **"Salary 5000 into SBI"** → Instantly credits your bank account and updates liquidity.
* **"Rent 1200 tomorrow"** → Schedules a pending transaction.

### 2. Privacy Vault
A comprehensive, high-speed ledger that allows you to scrub your data with ease. Includes advanced filtering by date, category, and account, with bulk-deletion logic designed for high-volume users.

### 3. Liquidity Management
Real-time tracking across multiple accounts (Cash, Digital Wallets, Bank). The app maintains a multi-versioned Dexie.js schema to ensure balance accuracy and mathematical integrity during transaction reversals.

### 4. Analytics & AI Pulse
* **Weekly Momentum:** High-contrast bar charts powered by Recharts.
* **Category Distribution:** Visual breakdown of where your capital is flowing.
* **The Pulse:** An on-device insight engine that alerts you to spending anomalies without ever sending data to the cloud.

---

## 🛠️ Technical Architecture
SpendScrub is a showcase of modern, cross-platform engineering:

* **Frontend:** React (Vite) + TypeScript.
* **Styling:** TailwindCSS 
* **Core:** Tauri (Rust-based bridge for native performance and security).
* **Persistence:** Dexie.js (IndexedDB) with a custom multi-versioned schema.
* **Deployment:** CI/CD via GitHub Actions with a multi-platform build matrix (Windows/macOS/Linux).

---

## 🗺️ Roadmap: The "Pro" Evolution
While the core experience is focused on individual tracking, the following features are currently in development for the **SpendScrub Pro** release:

* **PeerSplit:** A P2P debt-tracking system using QR-based "Delta" sync. Track group expenses with zero servers.
* **VisionScrub:** On-device OCR via Tesseract.js/WASM. Scan a receipt, and the MagicBar auto-populates.
* **Zero-Knowledge Sync:** Encrypted file-based handshakes between your desktop and mobile devices.

---

## 🔒 License & Usage
Copyright © 2026 Moses Kenny.

**SpendScrub is a proprietary application.** This repository serves as a portfolio showcase of the application's architecture, design, and development progress. The source code is not available for public distribution, modification, or commercial use at this time.

*SpendScrub is targeted for a Microsoft Store release following the successful launch of ToolSuite.*
