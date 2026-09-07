# Thorn   
Dual MOSFET Power Control Module for Makers
|<img src="/Images/image1.jpg" alt="1" width="300"/>|<img src="/Images/image2.jpg" alt="2" width="300"/>|<img src="/Images/image6.jpg" alt="6" width="300"/>|
|---|---|---|

Thorn is a compact, open-source dual MOSFET control module designed as part of the **SprigStack ecosystem**.  
It allows an ESP32 (like the [Sprig-C3](https://github.com/Frapais/SprigC3-ESP32-Development-Board)) or any microcontroller to switch and control **high-current DC loads up to 10A each**, with input voltages from **5–30V**.  

Perfect for driving **LEDs, motors, fans, heaters, pumps, or other DC devices** in smart home projects, robotics, and DIY automation.  

---

## 🔋 Free ESPHome battery pack
Building battery-powered ESP32 sensors? Check out this battery-life
calculator (works with any ESP32 board):
**→ [Get the free pack](https://sprig-labs.com/esp32-battery-life-calculator/?utm_source=github&utm_medium=readme)**

## ✨ Features
-  **Dual MOSFET channels** — control two independent DC loads.  
-  **Wide input voltage**: 5–30V DC.  
-  **High current capacity**: up to 10A per channel.  
-  **Screw terminals** for easy wiring.  
-  **Part of the SprigStack ecosystem** — plug-and-play with the Sprig-C3 ESP32 board.  
-  **Open-source hardware** — schematics, PCB, and design files included.  

---

## 📦 Applications
- Smart lighting (LED strips, panels, grow lights).  
- Fans, pumps, or motorized devices.  
- 3D printer or CNC add-ons.  
- Smart appliances with [Home Assistant](https://www.home-assistant.io/) integration via ESPHome.  
- General-purpose power switching in your projects.  

---

## 🛠️ Getting Started

### Hardware Setup
1. Connect **power input** (5–30V) to the shared input terminal.  
2. Connect your **load devices** (up to 10A each) to the channel terminals.  
3. Plug the module into a **Sprig-C3** or wire it to your own MCU.  

### Example Wiring
![drawing](/Images/Thorn%20wiring%20diagram.png)

