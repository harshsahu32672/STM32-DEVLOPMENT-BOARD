#  STM32L433CBT6 Custom Development Board  

A fully custom-designed **STM32L433CBT6 development board** built using **KiCad**, featuring USB connectivity, debugging support, and optimized PCB layout for embedded applications.

---

## 📌 Overview  
This project focuses on designing a compact and efficient development board based on the **STM32L4 series (ARM Cortex-M4)**. It includes all essential peripherals required for development, debugging, and prototyping.

---

## 🔧 Features  

- ⚡ **MCU:** STM32L433CBT6 (Ultra-low-power Cortex-M4)  
- 🔌 **Power Supply:** 5V input with onboard 3.3V regulation  
- 💻 **USB Support:** USB interface with ESD protection  
- 🔄 **USB-to-UART:** CP2102N for serial communication  
- 🧰 **Debugging:** SWD (SWCLK, SWDIO, NRST)  
- ⏱️ **Clock:**  
  - 8 MHz external crystal  
  - 32.768 kHz RTC crystal  
- 🔘 **Controls:** Reset & Boot buttons  
- 💡 **Indicators:** Power LED & User LED  
- 📡 **GPIO Access:** All major pins broken out for easy use  
- 📐 **Design:** Clean routing, proper grounding, and compact layout  

---

## 🖼️ Preview  

### 3D View  
![3D View]<img width="1256" height="578" alt="image" src="https://github.com/user-attachments/assets/b6fa009e-f2d6-4fb7-8408-4b185a8b4127" />


### Schematic  
![Schematic]<img width="949" height="671" alt="image" src="https://github.com/user-attachments/assets/9cad5fc0-f701-4636-ac26-52649c17e0c3" />
---

## 🛠️ Tools Used  

- **KiCad** – Schematic & PCB Design  
- **STM32CubeIDE / STM32CubeMX** – Firmware development  

---

## 📂 Project Structure  

STM32_Dev_Board/
│── Hardware/
│ ├── Schematic/
│ ├── PCB/
│ ├── Gerber/
│── docs/
│ ├── pcb_layout.png
│ ├── 3d_view.png
│ ├── schematic.png
│── README.md
