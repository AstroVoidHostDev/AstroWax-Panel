<h1 align="center">🚀 AstroWax Panel</h1>

<p align="center">
  <strong>⚡ Ultra Advanced Hosting Panel • Inspired by Teryx</strong><br>
  💻 Fast • Secure • Developer Friendly
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js" alt="Node.js">
  <img src="https://img.shields.io/badge/Build-Stable-success?style=for-the-badge" alt="Build Status">
  <img src="https://img.shields.io/badge/UI-Modern-blueviolet?style=for-the-badge" alt="UI">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Docker-orange?style=for-the-badge" alt="Platform">
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-quick-install">Quick Install</a> •
  <a href="#-manual-installation">Manual Install</a> •
  <a href="#-production-setup">Production</a> •
  <a href="#-troubleshooting">Troubleshooting</a> •
  <a href="#-features">Features</a> •
  <a href="#-plugin-system">Plugins</a> •
  <a href="#-security">Security</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## 🧠 Overview

**AstroWax Panel** is a modern, powerful hosting panel designed for performance, extensibility, and customization. Inspired by Pterodactyl but built for the next generation of server management, it combines a blazing-fast UI with a robust plugin architecture.

> **Philosophy:** Fast • Secure • Developer Friendly

**POWERED BY TERYX**

---

## ⚡ Quick Install

> [!TIP]
> **One-Line Magic**  
> Get up and running instantly with this single command. Ideal for testing or rapid deployment.

```bash
rm -rf panel && mkdir panel && cd panel && sudo apt-get update -y && sudo apt-get install -y software-properties-common build-essential curl git unzip libssl-dev python3 python3-dev python3-setuptools && nvm install 20 && nvm use 20 && export PYTHON=python3 && export npm_config_python=python3 && cd ~ && rm -rf AstroWax-Panel && git clone https://github.com/AstroVoidHostDev/AstroWax-Panel && cd AstroWax-Panel && unzip -o panel.zip && cd panel && rm -rf node_modules package-lock.json && npm cache clean --force && npm install --legacy-peer-deps && npm install connect-sqlite3 sqlite3@5.1.6 --build-from-source && npm run seed && npm run createUser && node .

