# Proteus Libraries Collection

A curated collection of archived **Proteus Design Suite** libraries for electronics simulation and circuit design.  
This directory brings together useful and commonly needed libraries for Arduino, Raspberry Pi, USB, sensors, modules, communication interfaces, and other simulation components.

> **Note:** The libraries in this repository are provided as archived packages for convenient access and reuse.

---

## 📦 Included Categories

* **🔵 Arduino**
  * Arduino Uno
  * Arduino Nano
  * Arduino Mega
  * Other commonly used Arduino boards and components
* **🥧 Raspberry Pi**
  * Raspberry Pi boards
  * Related simulation components
* **🔌 USB**
  * USB connectors
  * USB-related components and interfaces
* **📡 Communication Modules**
  * UART
  * I2C
  * SPI
  * RS-232 / RS-485
  * Other communication-related components
* **🌡️ Sensors & Modules**
  * Temperature sensors
  * Motion sensors
  * Distance sensors
  * Displays
  * Relays
  * Motors and drivers
  * Other commonly used modules
* **⚡ Electronics & Simulation Components**
  * Microcontrollers
  * Displays
  * Drivers
  * Modules
  * Connectors

---

## 🛠️️ How to Install Libraries

### 1. Download & Extract
Download the required archived library (`.zip` or `.rar`) from this folder and extract it on your computer.

### 2. Copy the Files
Copy the extracted library files (`.LIB`, `.IDX`, `.MODEL`, etc.).

### 3. Open the Proteus Library Folder
Navigate to your Proteus installation directory on your `C:` drive:

```text
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\Data\LIBRARY
```

### 4. Paste the Files
Paste all copied files into the `LIBRARY` folder. Grant administrator permission if requested by Windows.

### 5. Restart Proteus
Close Proteus completely if it was open, then restart it. You can now press **P** in the schematic layout to pick and search for your newly installed components.

---

## 📁 Library Directory Structure

```text
Proteus-Libraries/
├── Arduino/
├── Raspberry-Pi/
├── USB/
├── Sensors/
├── Communication/
├── Displays/
├── Modules/
├── Motors/
└── Other/
```

---

## 🔍 Troubleshooting

* Ensure files are copied directly into the `LIBRARY` folder, not inside subfolders within `LIBRARY`.
* Restart Proteus after adding new library files.
* Run Proteus as Administrator if components don't appear.
