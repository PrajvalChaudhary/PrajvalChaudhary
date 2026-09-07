# <p align="center">👋 Hello, I'm Prajval Chaudhary</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Anmol-Baranwal/Anmol-Baranwal/master/assets/gitspark.gif" alt="Tech Animation" width="100%">
</p>

<p align="center">
  <b>Embedded Linux & Linux Device Driver Developer</b>
  <br>
  <i>Building robust low-level firmware, custom kernel drivers, and robotics-hardware integrations.</i>
</p>

<p align="center">
  <a href="https://github.com/PrajvalChaudhary" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:your-email@example.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## ⚡ About Me

I am a passionate **Embedded Systems & Kernel-Level Developer** with a deep focus on bridging the gap between raw hardware and operating systems. My expertise lies in writing low-level drivers, configuring real-time kernels, and developing hardware-software integrated robotics systems using advanced microcontrollers and Single Board Computers.

---

## 🛠️ Core Tech Stack

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Kernel & Drivers** | **Linux Kernel Development**, **Character Drivers**, GPIO, I2C, SPI Subsystems |
| **Embedded OS** | **Embedded Linux** (RootFS on BBB), FreeRTOS, RT-Linux |
| **Languages & Tools** | **C (Kernel & Embedded)**, C++, Python, Bash Scripting, Make, GDB, Git |
| **Hardware** | **BeagleBone Black (BBB)**, **ESP32**, **LPC2148 (ARM7)**, AVR, Sensors/Actuators |

---

## 🚀 Highlighted Projects & Device Drivers

### 1. 🔌 GPIO Linux Device Drivers (Peripherals)
* **Description:** Custom character drivers developed for bare-metal and Linux-based control of hardware peripherals.
* **Key Implementations:** 
  * **LED & Buzzer Driver:** Kernel space configuration and control via sysfs / character device file operations (`ioctl`, `read`, `write`).
  * **LCD Interface Driver:** Low-level register manipulation and timing sequence handling for character/graphic displays using Linux GPIO subsystems.
* **Tech Used:** C, Linux Kernel APIs, Makefile.

### 2. 🐧 BeagleBone Black Embedded Linux & RootFS (`bbb_rootfs`)
* **Description:** Designed and customized root file systems and bootloader configurations for the BeagleBone Black to execute low-level application code.
* **Focus:** Kernel booting, module loading, cross-compilation toolchains, and hardware-in-the-loop debugging.

### 3. 🤖 Robotics & Hardware Integration (`dev_driver` & `esp`)
* **Description:** Integration of multi-sensor networks, wireless communication modules, and real-time control units for autonomous robotics applications.

---

## 📖 Linux Kernel Beginner Guide (Core Concepts)
*A quick reference breakdown of how I approach kernel and driver development:*
1. **Module Compilation:** Writing `Makefile` using kernel source trees (`obj-m := driver.o`).
2. **File Operations (`file_operations` structure):** Implementing `open`, `read`, `write`, and `release` hooks to bridge user-space and kernel-space.
3. **GPIO Subsystem:** Allocating, configuring directions, and setting values dynamically using Kernel GPIO APIs (`gpio_request`, `gpio_direction_output`, etc.).
4. **Debugging:** Utilizing `dmesg`, kernel logs, and panic handling for robust driver validation.

---

## 📊 GitHub Stats & Overview

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PrajvalChaudhary&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Prajval's Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PrajvalChaudhary&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</p>

---
<p align="center"><i>Thanks for stopping by! Feel free to explore my repositories or drop a connect.</i></p>
