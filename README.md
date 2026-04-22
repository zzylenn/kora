# Kora
A streamlined, high-performance tool for Discord Webhook and Bot management.

> [!CAUTION]
> **Disclaimer:** This tool is for educational and administrative purposes only. The developers assume **no responsibility** for any misuse, server damage, or violations of the Discord Terms of Service. Use at your own risk.

## Features
Kora provides a comprehensive suite of tools for rapid interaction with the Discord API.

### Webhook Management
* **Message Control:** Send, edit, and delete messages individually or in bulk.
* **Rich Embeds:** Full support for custom embedded messages and mass-embed broadcasting.
* **Identity Spoofing:** Send messages with custom profiles or permanently modify webhook metadata.
* **Destruction:** Single-click deletion or full webhook nuking.

### Bot Power-Tools
* **Channel & Role Manipulation:** Mass creation, deletion, and flooding of server structures.
* **Member Management:** Automated mass ban, kick, prune, and nickname synchronization.
* **Asset Cleanup:** Instantly wipe emojis, stickers, and existing webhooks.
* **Nuke Capabilities:** 
  * Full-spectrum server nuke with adjustable speed.
  * Selective modes for targeted cleanup.
* **Spam Automation:** Mass `@everyone` pings and DM-all functionality.

## Installation

### Prebuilt Binaries
For a plug-and-play experience, download the latest stable builds:
* **[Official Website](https://koratool.pages.dev)**
* **[GitHub Releases](https://github.com/zzylenn/kora/releases)**

### Manual Build (Windows)
If you prefer to compile from source, ensure you have Python installed and run the following:
```cmd
git clone [https://github.com/zzylenn/kora.git](https://github.com/zzylenn/kora.git)
cd kora/src
pip install -r requirements.txt
pyinstaller kora.spec
```
