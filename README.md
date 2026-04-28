# hosting-affiliate-machine
SpeedCheck Pro: Hosting Affiliate Machine - Integration Kit
# SpeedCheck Pro: Hosting Affiliate Machine - Integration Kit

Welcome to the official integration and documentation repository for **SpeedCheck Pro**. 

SpeedCheck Pro is a lightweight, No-Database PHP/JS application designed for web agencies and affiliate marketers. It transforms real-time Core Web Vitals audits (via Google PageSpeed Insights API) into professional lead magnets and automated hosting commissions.

## 🚀 The Architecture

This tool was built with a "Performance-First" and "Zero-Friction" mindset. Unlike heavy CMS plugins, SpeedCheck Pro is a standalone engine.

- **No-Database Engine:** All logic is handled via PHP file-based systems and Vanilla JavaScript.
- **Smart API Proxying:** The PHP backend handles Google API requests to protect your API keys and manage rate limits.
- **High-Performance Caching:** Includes a local JSON caching system to ensure instantaneous repeated audit loads.
- **Client-Side Rendering:** Uses `html2pdf.js` for on-the-fly professional PDF generation without taxing your server.

## 🛠 What's in this Repository?

This repository contains the public-facing components and integration guides for the SpeedCheck Pro ecosystem:

- `config.sample.js`: The structure for your affiliate routing and API configuration.
- `style.css`: The core responsive layout templates.
- `SEO-Guidelines.md`: Best practices for ranking your audit tool on search engines.

## 📦 Getting the Full Engine

To maintain the security of the proprietary PHP proxy and the advanced PDF generation logic, the core engine is distributed as a plug-and-play package.

The full package includes:
- The `api.php` secure proxy engine.
- The smart caching system.
- The full interactive quiz & affiliate routing logic.
- The Markdown-based SEO injection system.

**[Get the Full Engine & Lifetime License on Gumroad](https://hitpresence.gumroad.com/l/hosting-affiliate-machine)**

## 🔧 Installation Overview

1. Upload the files to any server running PHP 7.4+.
2. Rename `config.sample.js` to `config.js` and add your Google API Key.
3. Add your affiliate links (Cloudways, Hostinger, etc.) in the routing object.
4. Your machine is live!

---
*Developed for professionals who value speed, privacy, and ROI.*
