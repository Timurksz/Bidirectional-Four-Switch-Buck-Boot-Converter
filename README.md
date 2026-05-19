This repository contains the design files and documentation for a 100W Bidirectional Four Switch Buck-Boost (FSBB) Converter, 
digitally controlled by the Texas Instruments UCD3138 highly integrated digital power supply controller.

This converter is designed for bidirectional energy transfer, making it ideal for battery management systems (BMS), 
automotive applications (48V/12V dual-battery systems), and renewable energy setups.

Project Overview

The topology is based on a non-isolated synchronous four-switch buck-boost converter, capable of operating in both:

Buck Mode (48V → 12V)
High-voltage side supplies the low-voltage load.

Boost Mode (12V → 48V)
Low-voltage source transfers energy back to the 48V bus.

The system is digitally controlled using the UCD3138 Digital Power MCU, enabling:

Closed-loop voltage regulation

PWM generation

Bidirectional mode management

Protection algorithms

Real-time monitoring
