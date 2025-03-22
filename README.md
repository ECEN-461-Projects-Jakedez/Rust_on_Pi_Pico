# Rust-on-Pi-Pico
## Overview

This Project is a demonstration of a basic setup for how to program a Raspberry Pi Pico W with Rust, rather than some of the more common alternatives, such as with C/C++

This project demonstrates some basic Raspberry Pi Pico Functionality, as well as takes advantage of tools to integrate a Rust development environment into the Raspberry Pi Pico Ecosystem.

There were several notable challenges with this lab. First, the provided instructions seem to be a bit outdated, and didn't seem to work as intended anymore. So, I had to find another method that would get me to that point. Additionally, I only had a Raspberry Pi Pico W on hand, which has some key differences from the regular Raspberry Pi Pico. Notably, the onboard LED is not attached to a gpio pin. So, I opted to use an external LED attached to the GPIO-15 pin instead.

[Software Demo Video](https://youtu.be/BswQZHsqhVk)

## Development Environment

This project was developed using the Visual Studio Code IDE while taking advantage of the github.com/rp-rs/rp-hal/ drivers and template.

## Useful Websites


- [Git Hub - RP-HAL](https://github.com/rp-rs/rp-hal)
- [Rust - Getting Started](https://www.rust-lang.org/learn/get-started)
- [Raspberry Pi Pico W Documentation](https://www.raspberrypi.com/documentation/microcontrollers/silicon.html#rp2040)

## Future Work

- Use of serial output monitoring from Raspberry Pi Pico
- More I/O Functionality
