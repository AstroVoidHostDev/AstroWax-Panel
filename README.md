<h1 align="center">🚀 AstroWax Panel</h1>
<p align="center">
  ⚡ A Modern, Fast & Advanced Hosting Panel Inspired by Pterodactyl  
  💻 Built with Node.js, TailwindCSS & Performance in Mind  
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-20.x-green?style=flat-square">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square">
  <img src="https://img.shields.io/badge/License-Custom-blue?style=flat-square">
</p>
---
✨ Features
⚡ Modern UI (Pterodactyl Style)
🔌 Plugin System Support
👥 User & Admin Dashboard
🛠️ API System
🔐 Secure Authentication
📦 Lightweight & Fast
🎨 Fully Customizable Panel
---
📦 Requirements
Node.js v20.x
npm v9+
Git
Linux VPS / Ubuntu
---
⚙️ Installation Guide
Clone Repository
git clone https://github.com/AstroVoidHostDev/AstroWax-Panel
cd AstroWax-Panel
Install Node.js
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
Install Dependencies
npm install --legacy-peer-deps
Setup Panel
npm run seed
npm run createUser
Start Panel
node .
---
🧠 Common Fixes
Fix Modules Error
rm -rf node_modules package-lock.json
npm cache clean --force
npm install --legacy-peer-deps
Fix Database
rm -rf storage/skyport.db
mkdir -p storage
chmod -R 755 storage
---
🚀 Production (PM2)
npm install -g pm2
pm2 start index.js --name astrowax
pm2 save
pm2 startup
---
📜 License
(c) 2025 ITZ_YT_ANSH
All rights reserved.
---
❤️ Credits
Made by AstroVoid Host
