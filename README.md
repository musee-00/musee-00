# Hi, I'm Musee Mengsteab.G 

> 3rd-year Computer Science student specialising in **Embedded Systems**  
> Building bare-metal firmware and bridging hardware with software using C and Python.

---

## About me

I'm a Computer Science student focused on Embedded Systems, working close to the hardware level — registers, interrupts, and memory — to understand how systems really work.

Recently, I've been building complete embedded systems from scratch, including drivers, communication interfaces, and simple UI systems using real STM32 hardware.

-  CS student — Embedded Systems (Year 3)
-  Building **bare-metal firmware (no HAL) on STM32**
-  Working with **UART, GPIO, LCD interfaces**
-  Integrating embedded systems with **Python (serial communication & data visualization)**
-  Currently learning: **FreeRTOS, system design, and real-time debugging**
-  Open to internships and embedded systems roles

---

##  Core Skills

- **Languages:** C, C++, Python  
- **Embedded:** STM32 (ARM Cortex-M), Bare-metal programming, Register-level development  
- **Protocols:** UART (implemented), SPI/I2C (learning)  
- **Tools:** STM32CubeIDE, VS Code, Git, Linux  
- **Concepts:** Interrupts, Memory-mapped I/O, Debugging, Real-time systems  

---


##  Projects

###  Bare-metal GPIO Driver — STM32F411RE
> Register-level driver with zero HAL dependencies

- Direct manipulation of **MODER, BSRR, PUPDR registers**
- Configurable pin modes and output control
- Designed for portability and clarity

**Stack:** C · STM32F411RE · ARM Cortex-M4  
https://github.com/musee-00/stm32-gpio-driver

---

###  Bare-metal UART Driver — STM32
> Serial communication between STM32 and MacBook

- Implemented UART TX from scratch using registers
- Sent real-time data from microcontroller to PC
- Used for debugging and external communication

**Stack:** C · UART · STM32 · Serial communication  

---

###  LCD Interface + Counter System
> Embedded UI system with real-time feedback

- LCD displays counting loop (1 → 10 → -1)
- LED triggers at max/min values
- Demonstrates control logic + hardware interaction

**Concepts:**
- State-based logic
- Hardware feedback systems
- Embedded UI basics

---

###  STM32 ↔ Python Serial Monitor (in progress)
> Bridging embedded systems with high-level software

- Reading UART data using Python (`pyserial`)
- Planned: real-time plotting + logging

---

###  LiDAR Mapping Controller — ROS2
> Group project

- Built controller node for LiDAR-based mapping
- Processed point cloud data and published occupancy maps

**Stack:** ROS2 · C++/Python · SLAM · Linux  

---
###  PIR Alarm System — STM32
> Motion-activated alarm with bare-metal register control

- PIR sensor triggers LED blink sequence on motion detection
- Buzzer alert output (hardware pending)
- Full register-level GPIO control — no HAL dependencies

**Wiring:**
| Component | Nucleo Pin |
|-----------|-----------|
| PIR Signal | PA0 (A0) |
| LED | PA1 (A1) |
| Buzzer | PA2 (D1) |

**Status:** PIR + LED working · Buzzer pending replacement

**Stack:** C · STM32F411RE · Bare-metal · STM32CubeIDE
https://github.com/musee-00/pir-alarm-system

------

###  Todo Manager — C++ CLI
> OOP and STL practice — command-line task manager

- Task class with due dates, priority levels, and persistent file storage
- Search, complete, and remove tasks via interactive menu
- Color-coded terminal output

**Stack:** C++ · STL · OOP · File I/O
https://github.com/musee-00/todo-manager


##  What I'm Working Towards

-  RTOS-based multi-tasking systems (FreeRTOS)
-  Real-time data visualization from embedded devices
-  Building reusable embedded drivers and tools
-  Embedded + Python + UI integration

---

## GitHub stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=musee-00&show_icons=true&theme=default&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=musee-00&layout=compact&hide_border=true&theme=default" height="150" />
</p>

---

## Let's connect

-  Open to internships and embedded systems opportunities

---

<sub>2026 · Embedded Systems · Building from registers up</sub>
