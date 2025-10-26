<p align="center">
  <img src="https://via.placeholder.com/150x50.png?text=Proxy+List+App" alt="Proxy List Web App Logo">
</p>

<h1 align="center">🌟 Proxy List Web App 🌟</h1>

<p align="center">
  A lightweight, client-side web app to display and check proxies from a GitHub-hosted list, with a focus on Malaysia (MY) and Singapore (SG). Built with HTML, CSS, and JavaScript, it’s perfect for quick deployment on free static hosting platforms! 🚀
</p>

<p align="center">
  <a href="https://cf-proxy.netlify.app/"><strong>📺 Live Demo</strong></a> • 
  <a href="https://github.com/Durgaa17/proxylist-cloudflare"><strong>📂 GitHub Repo</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/Durgaa17/proxylist-cloudflare?style=social" alt="GitHub Stars">
  <img src="https://img.shields.io/github/license/Durgaa17/proxylist-cloudflare" alt="License">
  <img src="https://img.shields.io/badge/HTML5-CSS3-JS-blue" alt="Tech Stack">
</p>

---

## 🚀 One-Click Deploy

Get this app live in seconds with a single click! No configuration needed—just connect your GitHub account and deploy to one of these free platforms. 🎉

| Platform | Deploy Button |
|----------|---------------|
| **Netlify** | [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Durgaa17/proxylist-cloudflare) |
| **Vercel** | [![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Durgaa17/proxylist-cloudflare) |
| **Cloudflare Pages** | [![Deploy to Cloudflare Pages](https://deploy.workers.cloudflare.com/button)](https://dash.cloudflare.com/?to=/:account/pages/new/provider/github?repository=https://github.com/Durgaa17/proxylist-cloudflare) |
| **GitHub Pages** | [Enable in GitHub Settings](https://docs.github.com/en/pages/quickstart) *(Select `main` branch, root directory)* |
| **Render** | [![Deploy to Render](https://render.com/buttons/deploy-to-render.svg)](https://render.com/deploy?repo=https://github.com/Durgaa17/proxylist-cloudflare) |
| **Surge** | [Deploy via CLI](https://surge.sh/help/getting-started-with-surge) *(Run `surge ./` after cloning)* |

---

## ✨ Features

- 📡 **Dynamic Proxy List**: Fetches proxies from [FoolVPN-ID/Nautica](https://raw.githubusercontent.com/FoolVPN-ID/Nautica/refs/heads/main/proxyList.txt).
- 🇲🇾🇸🇬 **Malaysia & Singapore Focus**: Displays MY and SG proxies by default, with a dropdown for other countries.
- ✅ **Proxy Status Check**: Auto-checks proxies using `https://check.proxyip.cmliussss.net/check?proxyip=IP:PORT`.
  - 🟢 *Working: Xms* for active proxies.
  - 🔴 *Failed: message* for inactive ones.
- 🔄 **Hourly Auto-Refresh**: Updates the proxy list every hour.
- 🔄 **Manual Refresh**: “Refresh Now” button to reload and re-check proxies.
- 📱 **Responsive Design**: Mobile-friendly with a scrollable table for screens ≤600px.
- 🚨 **Error Handling**: Shows clear messages if the proxy list or API fails.

---

## 🛠️ Prerequisites

- 🌐 A modern web browser (Chrome, Firefox, Safari, etc.).
- 🧑‍💻 No server-side setup needed—runs entirely client-side.
- 📶 Internet access for fetching proxies and API checks.

---
