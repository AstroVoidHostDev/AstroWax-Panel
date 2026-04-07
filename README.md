<h1 align="center">🚀 AstroWax Panel</h1>
<p align="center">
⚡ Ultra Advanced Hosting Panel • Inspired by Pterodactyl  
💻 Fast • Secure • Developer Friendly
</p>
<p align="center">
<img src="https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Build-Stable-success?style=for-the-badge">
<img src="https://img.shields.io/badge/UI-Modern-blueviolet?style=for-the-badge">
</p>
---
🧠 Overview
AstroWax Panel is a modern, powerful hosting panel designed for performance and customization.
---
⚡ One-Line Install (Quick Setup)
```bash
git clone https://github.com/AstroVoidHostDev/AstroWax-Panel && cd AstroWax-Panel && curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt-get install -y nodejs git unzip && npm install --legacy-peer-deps && npm run seed && npm run createUser && node .
```
---
⚙️ Full Installation Guide
1. Clone Repo
```bash
git clone https://github.com/AstroVoidHostDev/AstroWax-Panel
cd AstroWax-Panel
```
2. Install Node.js
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
```
3. Install Dependencies
```bash
npm install --legacy-peer-deps
```
4. Setup Panel
```bash
npm run seed
npm run createUser
```
5. Start Panel
```bash
node .
```
---
🚀 Production Setup (PM2)
```bash
npm install -g pm2
pm2 start index.js --name astrowax
pm2 save
pm2 startup
```
---
🛠️ Fix Common Errors
Fix Modules
```bash
rm -rf node_modules package-lock.json
npm cache clean --force
npm install --legacy-peer-deps
```
Fix Database
```bash
rm -rf storage/skyport.db
mkdir -p storage
chmod -R 755 storage
```
Fix Permissions
```bash
sudo chown -R $USER:$USER node_modules
sudo chown -R $USER:$USER ~/.npm
```
---
🔥 Features
⚡ Blazing Fast UI
🔌 Plugin System
🔐 Secure Auth
📊 Admin Dashboard
🎨 Custom Themes
---
🧩 Plugin System
Drop plugins in `/plugins`
Enable/Disable via panel
Hot reload support
---
🔐 Security Tips
Use NGINX reverse proxy
Enable HTTPS
Use PM2 for uptime
Avoid running as root
---
🤝 Contributing
Fork → Edit → PR 🚀
---
📜 License
(c) 2025 ITZ_YT_ANSH
---
❤️ Credits
Made with ❤️ by AstroVoid Host
---
<p align="center">⭐ Star the repo if you like it</p>
