# PicoEdu: Dynamic Learning with the BitDogLab Board


---

## Overview

**PicoEdu: Dynamic Learning with the BitDogLab Board** is an innovative educational project that is part of the final evaluation for Stage 1 of Embarca Tech. This project aims to bridge the gap between students and the world of hardware and electronics by offering an interactive, hands-on learning experience that makes complex concepts accessible—even for beginners.

Powered by the Raspberry Pi Pico W RP2040 and mounted on a BitDogLab board, PicoEdu features an intuitive menu interface where each option displays code demonstrating a peripheral in action. Whether it’s controlling LEDs, playing melodies through a buzzer, or reading sensor data, each demo is designed to show practical applications in a clear and engaging way.

In addition, the board’s built-in WiFi hosts a dedicated website that explains each peripheral in detail, making it easy for users to understand the underlying technology. The project also integrates cloud communication using ThingSpeak, which provides a didactic example of sending and visualizing data in the cloud—demonstrating a real-world IoT application.

---

## Features

- **Interactive Menu Interface:**  
  Easily navigate through demos like LED control, buzzer melodies, sensor data acquisition, and more.
  
- **WiFi-Enabled Website:**  
  Access a dedicated website hosted on the board that offers detailed explanations of each peripheral.
  
- **Cloud Communication with ThingSpeak:**  
  See how sensor data is sent to and visualized in the cloud, showcasing real-world IoT applications.
  
- **Modular Design:**  
  The project is divided into independent modules, each focusing on a specific functionality (e.g., LED control via PIO, ADC data acquisition, PWM for buzzer control).
  
- **Hands-On Learning:**  
  Interactive code demonstrations and live examples help demystify hardware concepts and illustrate their impact on our daily lives.

---

## Hardware Requirements

- **Raspberry Pi Pico W RP2040:**  
  A dual-core ARM Cortex-M0+ microcontroller with WiFi connectivity.
  
- **BitDogLab Board:**  
  A development board that integrates the Pico W with multiple peripherals.
  
- **Peripherals:**  
  - OLED Display (SSD1306, 128x64)  
  - LED Matrix (Neopixel 5x5)  
  - Joystick (Analog)  
  - Buzzer (Active)  
  - Microphone (e.g., MAX4466)  
  - Temperature Sensor (Internal or External)  
  - Additional communication interfaces (e.g., USART)

---

## Software Requirements

- **Pico SDK:**  
  For building and flashing firmware on the Raspberry Pi Pico W.
  
- **C/C++ Toolchain:**  
  Compatible with the RP2040 microcontroller.
  
- **Build System:**  
  Use PlatformIO, CMake, or Makefile as preferred.
  
- **ThingSpeak Account:**  
  (Optional) For cloud connectivity and data visualization.

---

## Getting Started

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/PicoEdu.git
   cd PicoEdu
