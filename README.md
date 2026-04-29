# WordPress Advanced Dorks Arsenal

> **A curated collection of 5000+ high‑precision Google dorks for uncovering sensitive information in WordPress sites.**  
> *Designed for authorized security testing, CTF challenges, and hardening your own web assets.*

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![WordPress](https://img.shields.io/badge/Target-WordPress-21759b?logo=wordpress)
![Version](https://img.shields.io/badge/version-2.0-red)

---

## ⚠️ LEGAL & ETHICAL NOTICE

**This repository is provided for educational and defensive purposes only.**  
Using these dorks against any website without explicit written permission from the owner is **illegal** and violates:
- Computer Fraud and Abuse Act (CFAA) in the US  
- GDPR and national cybercrime laws in Europe  
- Similar regulations worldwide  

**By using this material you agree:**
1. To test **only your own WordPress sites** or those you are authorized to audit.
2. To never use automated scanning tools without permission.
3. To responsibly disclose any findings.

> The author (`@Nobody-555-111`) assumes **zero liability** for misuse. You have been warned.

---

## What are these dorks?

Google dorks are advanced search operators (`site:`, `inurl:`, `intitle:`, `filetype:`, etc.) that reveal data not meant to be public. This arsenal focuses **exclusively on WordPress** – the world’s most popular CMS (43% of all websites).

Each dork is crafted to find:

| Category | Examples of discovered data |
|----------|-----------------------------|
|  **Configuration** | `wp-config.php`, `.env`, `phpinfo()`, database credentials |
|  **Backups** | `.sql`, `.zip`, `.tar.gz`, `.wpress`, `.bak` files |
|  **Logs & Debug** | `debug.log`, `error_log`, PHP fatal errors, SQL syntax leaks |
|  **Database dumps** | Full `wp_users`, `wp_options`, WooCommerce orders |
|  **API keys & secrets** | Stripe, AWS, Mailgun, SMTP passwords, JWT secrets |
|  **Open directories** | Index of `/uploads/`, `/cache/`, `/backup/`, `/logs/` |
|  **Plugin/Theme leaks** | Version disclosure, config files, license keys (Yoast, Elementor, Jetpack, etc.) |
|  **REST & XML‑RPC** | User enumeration, post metadata exposure |

---

## 🚀 How to use

1. **Replace `target`** with the domain you are testing (e.g., `mysite.com`).
2. Execute the dork in **Google Search** (or Bing, DuckDuckGo – operators may vary).
3. Analyse the results **manually** – do not use automated scrapers without permission.

### Example

Search for exposed `wp-config.php` backups:
