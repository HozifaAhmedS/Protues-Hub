# Proteus Libraries

A curated collection of archived **Proteus Design Suite** libraries for electronics simulation and circuit design.  
This repository brings together some of the most useful and commonly needed libraries for Arduino, Raspberry Pi, USB, sensors, modules, communication interfaces, and other simulation components in one place.

> **Note:** The libraries in this repository are provided as archived packages for convenient access and reuse.

---

## 📦 What's Included

The collection includes important Proteus libraries for:

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
  * Other useful components for circuit simulation

The collection is intended to make commonly needed Proteus libraries easier to find and install.

---

## 🛠️ Installation

### 1. Download the Library
Download the required archived library from this repository.  
The libraries are provided as compressed/archive files such as:
* `.zip`
* `.rar`

### 2. Extract the Archive
Extract the downloaded archive using Windows File Explorer, WinRAR, 7-Zip, or any other archive utility.  
After extracting the archive, you should find the Proteus library files inside.

### 3. Copy the Library Files
Copy the extracted library files. Depending on the library, these may include files such as:
* `.LIB`
* `.IDX`
* `.MODEL`  
*(or other files required by the library)*

### 4. Open the Proteus Library Folder
Go to the Proteus installation directory on your `C:` drive.  
The default location is:

```text
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\Data\LIBRARY
```

You can also navigate manually:
```text
C:
└── Program Files (x86)
    └── Labcenter Electronics
        └── Proteus 8 Professional
            └── Data
                └── LIBRARY
```

### 5. Paste the Files
Paste the extracted library files into the `LIBRARY` folder.  
If Windows asks for Administrator Permission, click **Continue** to allow the files to be copied.

### 6. Restart Proteus
If Proteus is already running, close it completely and open it again. Then:
1. Open your Proteus project.
2. Click **Pick Devices (P)**.
3. Search for the component you installed.
4. Select the component and add it to your schematic.

The library should now be available in Proteus.

---

## 🔍 Troubleshooting

If the component does not appear:
- [ ] Make sure the archive was extracted correctly.
- [ ] Verify that the library files were copied to the correct `LIBRARY` folder.
- [ ] Make sure Proteus was restarted after installation.
- [ ] Check that all files included in the archive were copied.
- [ ] Try running Proteus with Administrator permissions if Windows prevented the files from being copied.

---

## 📁 Repository Structure

The repository is organized by library/category to make it easier to find the required components:

```text
Proteus-Libraries/
│
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

*The exact categories may change as more libraries are added.*

---

## 💻 Proteus Compatibility

These libraries are intended for use with **Proteus Design Suite**.  
Compatibility may vary depending on the specific library and Proteus version. Always check the library contents and documentation if a component does not work as expected.

---

## ⚠️ Important Note

This repository is primarily a collection and archive of Proteus libraries gathered for convenient access.  
Some libraries may be provided by their original authors or third parties. Please respect the original licenses and terms of use where applicable.

---

## 🤝 Contributions

If you have a useful Proteus library that is missing from this collection, contributions are welcome!

You can contribute by:
1. **Forking** this repository.
2. **Adding** the library to the appropriate category.
3. **Keeping** the original archive and file structure when possible.
4. **Adding** any useful documentation or installation notes.
5. Creating a **Pull Request**.

---

## ⭐ Support

If you find this collection useful, consider giving the repository a **Star ⭐**.  
It helps others discover the collection and encourages further updates!

---

## 📌 Disclaimer

This repository is provided for educational, development, and electronics simulation purposes.  
The author does not claim ownership of third-party libraries unless explicitly stated.
