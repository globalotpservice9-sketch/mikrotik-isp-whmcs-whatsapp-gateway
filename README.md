# 🌐 Official WhatsApp API Gateway for ISPs, CRMs & Billing Systems

[![5MinutesAPI](https://img.shields.io/badge/Powered%20By-5MinutesAPI-25D366?style=for-the-badge&logo=whatsapp)](https://5minutesapi.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Welcome to the ultimate drop-in WhatsApp Cloud API Gateway for **ISPs, WISP Management, Web Hosting, and B2B CRM systems**. Built by [5MinutesAPI](https://5minutesapi.com), this universal bridge replaces expensive SMS gateways with official, end-to-end encrypted WhatsApp alerts.

Perfectly optimized for **MikroTik Radius**, **PHPNuBill**, **Splyn**, **WHMCS**, and **UltimatePOS** globally (Highly recommended for Saudi Arabia, UAE, Pakistan, Brazil, and Indonesia).

---

## 🔥 Why Upgrade to Official WhatsApp API?
* 💰 **Cost-Effective:** Stop paying high fees per SMS. Meta's official WhatsApp API is significantly cheaper, and 5MinutesAPI charges **Zero Markup**.
* 🚫 **No More Number Bans:** Unofficial QR-code bots (like Baileys or Fonnte) get banned constantly when sending bulk billing alerts. We use the Official Meta API with safe Utility Templates.
* ⚡ **Plug & Play:** Zero coding required! Just paste our Universal Bridge URL into your software's SMS settings.

---

## 🛠️ Supported Systems & Quick Setup Guides

### 1. 📡 ISPs & Hotspot Billing 
Send WiFi Login OTPs, Invoice Expiries, and Bandwidth Alerts directly to your customers' WhatsApp.

**How to connect:**
1. Open your billing software's SMS Gateway / Notification settings.
2. Select **HTTP / Custom URL Gateway**.
3. Paste the following Universal Bridge URL:
```text
[https://api.5minutesapi.com/v1/bridge/universal?api_key=YOUR_MASTER_API_KEY&template=isp_billing_alert&to=](https://api.5minutesapi.com/v1/bridge/universal?api_key=YOUR_MASTER_API_KEY&template=isp_billing_alert&to=){phone}&var1={message}
