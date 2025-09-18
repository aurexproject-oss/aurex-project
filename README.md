# AUREX — Official Website

This repository contains the **official static website** for the AUREX project, hosted on **GitHub Pages**.  
All important project data such as the contract address, social links, and DEX links are stored in the `config.json` file, so you can **update the token and links without touching the code**.

---

## 🌐 Live Website
Your live site will be accessible at:  
> Replace `github.io/aurex-project/` with your GitHub username.

---

## 🚀 Quick Start
1. **Upload project files** directly to the root of your repository:

2. Go to **Settings → Pages** and configure:
- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/root`

3. Wait 1–3 minutes, then visit your website.

---

## 🔧 Updating Token Information
All token and link data is managed inside `config.json`.  
Simply edit this file and commit the changes.

**Fields you can update:**
- `token.address` — Smart contract address (BEP-20)
- `token.symbol`, `token.decimals`
- `dex.pancakeSwapBuy` — PancakeSwap URL for direct purchase
- `dex.dextoolsPair` — DexTools pair URL
- `socials.*` — Telegram, Facebook, Website links

The website will automatically load the updated information.

---

## 🧪 Local Testing
To test the site locally, run a simple Python HTTP server:
Then open `http://localhost:8080` in your browser.

---

## ⚠️ Disclaimer
The AUREX project is a **community experiment** and should **not be considered financial advice**.  
Cryptocurrency investments are inherently risky — **always do your own research (DYOR)** before participating.



## 📂 Project Structure
