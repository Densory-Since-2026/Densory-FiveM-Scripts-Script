# Template Script — FiveM Scripts

![Latest version: v1.5.0](https://img.shields.io/badge/Latest_version%3A_v1.5.0-555) ![Self-Hosted](https://img.shields.io/badge/Self--Hosted-555) ![ESX](https://img.shields.io/badge/ESX-555) ![QBCore](https://img.shields.io/badge/QBCore-555) ![Standalone](https://img.shields.io/badge/Standalone-555)

![Template Script](docs/assets/hero-en.png)

> FiveM Script Template with integrated Densory licensing system – ready to customize and sell.

The template script is the basis for all FiveM scripts on the Densory platform. It includes a complete licensing system with hardware binding (cfx.re server ID), automatic settings distribution via the API, update detection and an exemplary /ping command. Perfect as a starting point for your own script development.

### 🛒 Get it on the Densory Shop

**[Template Script — View in Shop](https://densory.com/shop/template-script)**

## Features

- **Ultra-Low Resmon** — Optimized for under 0.05ms idle — stays invisible on your server.
- **ESX & QBCore** — Adapter for both frameworks included — neatly abstracted.
- **Multi-Locale** — DE/EN/FR Strings out-of-the-box, custom languages can be easily added.
- **Anti-Cheat Hooks** — Built-in exploit detection with configurable response levels.
- **MySQL & Redis** — Native adapters for persistent data and real-time caches.
- **Event Bus** — Clean module architecture — Features can be attached as plugins.

## Prerequisites

- FiveM Server with txAdmin or direct console access
- Access to server.cfg for convar configuration
- Basic knowledge of Lua and FiveM Resource structure

## Setup

1. **Download Script**
   Download the ZIP archive via the download button in the dashboard or shop.
2. **Install Resource**
   Unzip the folder to server-data/resources/ on your FiveM server.
3. **Configuring License Keys**
   Add to your server.cfg: set densory_template-script "YOUR-LICENSE KEY" and ensure template-script.
4. **Start and test the server**
   Restart your FiveM server. The license is automatically validated and settings are loaded via the API. Test with /ping in chat.

## Framework Compatibility

This script is compatible with the following frameworks:
- ESX
- QBCore
- Standalone

## Configuration

See the full settings reference in [docs/configuration.md](docs/configuration.md).

## Changelog

See [CHANGELOG.md](CHANGELOG.md) and the GitHub Releases tab for the full version history.

## Support & Links

- 🛒 [Shop](https://densory.com/shop/template-script)
- 💬 [Discord](https://densory.com/discord)
- ⚙️ [Control Center](https://densory.com/dashboard)

---

_Managed with the Densory Control Center: [https://densory.com/dashboard](https://densory.com/dashboard). Available at [https://densory.com/shop/template-script](https://densory.com/shop/template-script)._
