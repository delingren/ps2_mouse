# Convert a PS/2 mouse to USB

This project interfaces a PS/2 mouse with an Atmel atmega32u4 microcontroller and presents it as a USB HID device to the host. This by itself it not too interesting. But most laptop touchpads are PS/2 devices and we can repurpose them as standalone mice. This is somewhat useful. But it lacks advanced features such as two-finger scrolling. Such advanced features require proprietary drivers and extension of PS/2 protocol supported by the touchpad and the driver. My ultimate goal is to implement such a protocol defined by Synaptics. This project is a stepping stone towards that goal.

The Synaptics touchpad project is a WIP but it's already more or less usable. It can be found [here](https://github.com/delingren/touchpad).