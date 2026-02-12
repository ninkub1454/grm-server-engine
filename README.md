# grm-server-engine
🚀 High-performance multiplayer game server engine for Genesis Realms.

# 👑 GRM Server Engine (Genesis Realms Multiplayer)

[![Build Status](https://img.shields.io/badge/status-stable-green.svg)]()
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)]()

**GRM Server Engine** เป็นระบบจัดการเซิร์ฟเวอร์เกมประสิทธิภาพสูงที่เขียนด้วยภาษา **Rust** ออกแบบมาเพื่อความเสถียร ความปลอดภัย และความยืดหยุ่นด้วยระบบ **Lua Scripting** ที่ทรงพลัง

---

## ✨ คุณสมบัติเด่น (Features)
* **Performance:** ประมวลผลรวดเร็วด้วย Rust (Zero-cost abstractions)
* **Live Console:** ควบคุมเซิร์ฟเวอร์ผ่าน Web Dashboard สวยงาม
* **Modular Scripting:** เขียนระบบเกมด้วย Lua ได้ง่ายและแยกเป็นส่วนๆ
* **Security:** ป้องกันการโจมตีพื้นฐานและระบบ License Verification
* **Cross-Platform:** รองรับทั้ง Windows และ Linux

## 🛠️ โครงสร้างโปรเจกต์ (Project Structure)
```text
.
├── src/            # Core Engine Source Code
├── resources/      # Game Scripts (Lua)
├── dashboard.html  # Web Console UI
└── config.ron      # Server Configuration
