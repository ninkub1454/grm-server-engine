# 👑 GRM Server Engine (Genesis Realms Multiplayer)

[![Build Status](https://img.shields.io/badge/status-stable-green.svg)]()
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)]()
[![License](https://img.shields.io/badge/license-MIT-orange.svg)]()

**GRM Server Engine** is a high-performance, modular multiplayer game server engine built with **Rust**. It is designed for stability, memory safety, and extreme flexibility through its **Lua Scripting API**.



---

## ✨ Key Features

* **High Performance:** Leveraging Rust's zero-cost abstractions for lightning-fast packet processing.
* **Modular Scripting:** Fully extensible through a sandboxed Lua 5.4 environment.
* **Web Dashboard:** Real-time server management via a modern, built-in Web Console.
* **Global Discovery:** Integrated Heartbeat system connecting to the GRM Master Server.
* **Multi-Platform:** Native support for both Windows and Linux binaries.
* **Security:** Built-in license verification and anti-spam log limiting.

---

## 🏗️ Project Structure

The project follows a strict modular architecture to ensure scalability:

```text
grm_server/
├── src/
│   ├── core/         # Core logic (Config, State, Logging)
│   ├── systems/      # Backend services (Heartbeat, Network, Resources)
│   ├── scripting/    # Lua Engine & Modular APIs
│   └── web/          # Axum Web Server & Dashboard API
├── resources/        # Game Scripts & Assets
├── dashboard.html    # Web Console UI
└── server_config.ron # Server configuration file
