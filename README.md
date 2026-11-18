# Hi, I'm Zakariae 👋

**Embedded Software Engineer** based in Paris, France — MSc Electronics & Embedded Systems, École Centrale de Lyon.
I write real-time firmware in C for ARM Cortex-M microcontrollers, from bare-metal startup code and drivers up to RTOS applications with touch UIs and connected gateways.

- 🏥 **Schiller Médical** — real-time physiological signal acquisition for defibrillators (drivers, interrupts, middleware in C)
- 🚗 **Capgemini Engineering** — STM32 control of an automotive rear-light board, real-time LED fault detection
- 🎓 **Safran** — delivered a 4-day training on embedded C, FreeRTOS and real-time systems
- 💼 Founder of **BEN-AKKA Consulting** — freelance embedded software consulting

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| Languages | C, C++, Python |
| RTOS | Zephyr RTOS, FreeRTOS |
| MCUs & boards | STM32 (F4, F7), ARM Cortex-M, ESP32, ESP8266 |
| Low level | Bare-metal (no HAL), startup code, linker scripts, QSPI XIP, watchdogs |
| Protocols | UART, SPI, I2C, CAN, MQTT, custom CRC16 framing |
| UI | LVGL |
| Build & debug | GCC, Make, CMake, west, OpenOCD, GDB, ST-Link |
| CI & tooling | Git, GitLab CI, Jenkins, Docker, Linux |

## 🚀 Featured projects

### [Zephyr_Project](https://github.com/zkariae/Zephyr_Project) — STM32F7 dashboard on Zephyr RTOS
LVGL touch UI with system diagnostics, a PC-sampling CPU profiler and a tilt-controlled game driven by an MPU6050. Runs XIP from QSPI flash through a two-stage boot chain.

[![Demo](https://i.ytimg.com/vi/aI7hIi8hxNI/mqdefault.jpg)](https://www.youtube.com/watch?v=aI7hIi8hxNI)

### [stm32-esp8266-uart-gateway](https://github.com/zkariae/stm32-esp8266-uart-gateway) — IoT gateway
FreeRTOS UART gateway with a CRC16 binary protocol (ACK/retry) and MQTT cloud publishing (STM32F407G-DISC1 + ESP8266), validated on hardware.

### [stm32f7508-dk-baremetal](https://github.com/zkariae/stm32f7508-dk-baremetal) — Bare-metal STM32F7
No HAL, no CubeMX: startup code, linker scripts and peripheral drivers written from the reference manual.

### [embedded-data-logger](https://github.com/zkariae/embedded-data-logger) — Data acquisition
Register-level STM32F4 firmware streaming data over UART, with a Python GUI and cloud storage.

### [STM32_RFID_RC522_Reader](https://github.com/zkariae/STM32_RFID_RC522_Reader) — RFID driver
Bare-metal SPI driver for the RC522 reader on STM32F407.

## 📫 Contact

- 🌐 Portfolio: [benakka-tech.fr](https://benakka-tech.fr/)
- 💼 Upwork: [Zakariae B. — Embedded Firmware Engineer](https://www.upwork.com/freelancers/~015671be00471a2a10)
- 📍 Paris, France — open to embedded software opportunities
