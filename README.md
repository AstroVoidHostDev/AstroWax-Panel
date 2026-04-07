<h1 align="center">🚀 AstroWax Panel</h1>

<p align="center">
  <strong>⚡ Ultra Advanced Hosting Panel • Inspired by Pterodactyl</strong><br>
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

---

## ⚡ Quick Install

> [!TIP]
> **One-Line Magic**  
> Get up and running instantly with this single command. Ideal for testing or rapid deployment.

```bash
sudo apt-get update && sudo apt-get install -y python3 python3-pip python3-dev build-essential libssl-dev && curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt-get install -y nodejs && rm -rf node_modules package-lock.json && npm cache clean --force && npm install --legacy-peer-deps --force && chmod -R 755 storage && npm rebuild && 
git clone https://github.com/AstroVoidHostDev/AstroWax-Panel && \
cd AstroWax-Panel && \
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && \
sudo apt-get install -y nodejs git unzip && \
cd panel && \
npm install --legacy-peer-deps && \
npm run seed && \
npm run createUser && \ 

# To Start Panel
node.

