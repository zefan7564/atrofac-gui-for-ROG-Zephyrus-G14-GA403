# Atrofac-Extended

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> A lightweight and extensible Linux fan and performance control daemon, based on [cronosun/atrofac](https://github.com/cronosun/atrofac), with added **system fan control** and **hardware monitoring** capabilities.

---

## 🧩 Introduction

**Atrofac-Extended** is a customized fork of the [atrofac](https://github.com/cronosun/atrofac) project, originally designed for controlling laptop fans and performance profiles on Linux systems.

This extended version adds:
- 🌀 **System fan control** for desktop or server environments  
- ⚙️ Support for hardware temperature sensors beyond CPU/GPU (e.g., chipset, VRM)  
- 📈 Improved temperature-to-fan curve management  
- 🔧 Optional D-Bus interface for integration with system daemons  
- 💻 Configuration persistence and logging

---

## 🚀 Features

| Feature | Description |
|----------|-------------|
| **Fan curve control** | Dynamically adjust fan speed based on temperature |
| **System fan support** | Control system chassis fans (e.g., via hwmon, i2c, or IPMI) |
| **Custom profiles** | Create performance/fan presets |
| **CLI tool** | Easy command-line control and monitoring |
| **Configurable YAML format** | Store and reload fan policies easily |

---
