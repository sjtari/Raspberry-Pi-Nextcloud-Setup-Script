# Raspberry Pi Nextcloud Setup Script

This repository provides a fully automated script to install **Nextcloud** on a **Raspberry Pi 5**, complete with:

- Apache, MariaDB, PHP (LAMP stack)
- HTTPS support via Let's Encrypt
- Dynamic DNS via DuckDNS
- Automatic cron updates for DuckDNS IP resolution

## 🔧 Requirements

- Raspberry Pi 5 with Raspberry Pi OS (Lite or Full)
- Internet connection
- DuckDNS domain + token
- Open ports 80 and 443 (for HTTPS)

## 🚀 How to Use

1. Clone this repo or download the script:
   ```bash
   git clone https://github.com/salar-rpi/raspberrypi-nextcloud.git
   cd raspberrypi-nextcloud
   ```

2. Make it executable and run:
   ```bash
   chmod +x nextcloud_secure_duckdns.sh
   ./nextcloud_secure_duckdns.sh
   ```

3. Follow the prompts to enter your DuckDNS info and complete the setup.

## 📬 Contact

Created by **Salar** – feel free to contribute or suggest improvements.
