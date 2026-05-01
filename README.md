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
- **Protocols:** UART (implemented), I2C (implemented), SPI (learning)  
- **Tools:** STM32CubeIDE, VS Code, Git, Linux  
- **Concepts:** Interrupts, Memory-mapped I/O, Debugging, Real-time systems  

---

##  Projects

###  Bare-metal GPIO Driver — STM32F411RE
> Register-level driver with zero HAL dependencies

- Direct manipulation of **MODER, BSRR, PUPDR registers**
- Configurable pin modes, output type, pull-up/pull-down
- Atomic pin set/reset using BSRR

**Stack:** C · STM32F411RE · ARM Cortex-M4  
https://github.com/musee-00/stm32-gpio-driver

---

###  Bare-metal UART Driver — STM32
> Serial communication between STM32 and MacBook

- Implemented UART TX from scratch using registers
- Configured PA2 as AF7, set baud rate via BRR register
- Sends real-time data to Mac over USB — no HAL

**Stack:** C · UART · STM32F411RE · Bare-metal  
https://github.com/musee-00/stm32-uart-driver

---

###  STM32 Telemetry Dashboard — LCD + UART + Python
> Full embedded pipeline: STM32 firmware → UART → Python → CSV log

- STM32 streams counter data over UART at 9600 baud
- I2C LCD displays live counter on PCF8574 backpack
- Python reads serial data with `pyserial` and logs to CSV
- LED triggers at min/max counter values

**Stack:** C · Python · STM32F411RE · I2C · UART · pyserial  
https://github.com/musee-00/stm32-telemetry-dashboard

---

###  PIR Alarm System — STM32
> Motion-activated alarm with bare-metal register control

- PIR sensor triggers LED and buzzer on motion detection
- 5x fast blink/buzz pattern on motion event
- UART logging sends `Motion detected!` and `No motion` over USB at 9600 baud
- Full register-level GPIO and USART2 control — no HAL dependencies

| Component | Pin |
|-----------|-----|
| PIR Signal | PA0 |
| LED + Buzzer | PA1 |
| UART TX (log) | PA2 |

**Stack:** C · STM32F411RE · Bare-metal · UART · STM32CubeIDE  
https://github.com/musee-00/PIR_Alarm 


###  LiDAR Mapping Controller — ROS2
> Group project

- Built controller node for LiDAR-based mapping
- Processed point cloud data and published occupancy maps

**Stack:** ROS2 · C++/Python · SLAM · Linux  

---

###  Todo Manager — C++ CLI
> OOP and STL practice — command-line task manager

- Task class with due dates, priority levels, and persistent file storage
- Search, complete, and remove tasks via interactive menu
- Color-coded terminal output

**Stack:** C++ · STL · OOP · File I/O  
https://github.com/musee-00/todo-manager

---

##  What I'm Working Towards

-  RTOS-based multi-tasking systems (FreeRTOS)
-  Real-time data visualization from embedded devices (matplotlib)
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
