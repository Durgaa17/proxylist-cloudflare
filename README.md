# proxylist-cloudflare
fetch working or online proxy list for cloudflare tunnels

https://cf-proxy.netlify.app/

# Proxy List Web App

A simple, client-side web application that displays a list of proxies fetched from a GitHub-hosted proxy list, with a focus on Malaysia (MY) and Singapore (SG) proxies by default. Built with HTML, CSS, and JavaScript, this app is designed to be lightweight, responsive, and easy to deploy on static hosting platforms like Netlify, Vercel, or Cloudflare Pages.

Live demo: [https://cf-proxy.netlify.app/](https://cf-proxy.netlify.app/)

## Features

- **Dynamic Proxy List**: Fetches proxies from a public GitHub repository (`https://raw.githubusercontent.com/FoolVPN-ID/Nautica/refs/heads/main/proxyList.txt`).
- **Malaysia & Singapore Focus**: Displays MY and SG proxies by default, with an option to filter by other countries via a dropdown.
- **Proxy Status Check**: Automatically checks each proxy's status and response time (ms) using an external API (`https://check.proxyip.cmliussss.net/check?proxyip=IP:PORT`).
  - Shows "Working: Xms" (green) for active proxies or "Failed: message" (red) for inactive ones.
- **Hourly Auto-Refresh**: Updates the proxy list every hour to reflect changes in the source data.
- **Manual Refresh**: Includes a "Refresh Now" button to manually reload and re-check proxies.
- **Responsive Design**: Mobile-friendly layout with a scrollable table and adjusted font sizes for screens ≤600px.
- **Error Handling**: Displays user-friendly messages if the proxy list or API checks fail.

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari) to view or test the app.
- No server-side setup required—runs entirely client-side via JavaScript.
- Internet access to fetch the proxy list and check statuses via API.

## Deployment

You can deploy this project in seconds using one-click deploy buttons or manually by cloning the repository. The app is a single `index.html` file, making it ideal for static hosting.

### One-Click Deploy

Click a button below to deploy the app to your preferred platform. You'll need a GitHub account to connect the repository.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Durgaa17/proxylist-cloudflare)
[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Durgaa17/proxylist-cloudflare)
[![Deploy to Cloudflare Pages](https://deploy.workers.cloudflare.com/button)](https://dash.cloudflare.com/?to=/:account/pages/new/provider/github?repository=https://github.com/Durgaa17/proxylist-cloudflare)

############№##############
