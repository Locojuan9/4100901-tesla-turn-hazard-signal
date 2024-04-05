# 4100901-tesla-turn-hazard-signal
This repo contains an approach to implement the tesla turn and hazard signals 

## Requirements
* STM32 NUCLEO L476RGT6

![alt text](https://github.com/Locojuan9/4100901-tesla-turn-hazard-signal/blob/main/images/stm32?raw=true)

* Multifunctional shield

![alt text](https://github.com/Locojuan9/4100901-tesla-turn-hazard-signal/blob/main/images/shield.jpeg?raw=true)


* UART console

![alt text](https://github.com/Locojuan9/4100901-tesla-turn-hazard-signal/blob/main/images/yat.png?raw=true)


## Functionality
* If a turn button is pressed 1 time: the light on the corresponding side flashes 3 times.

* If a turn button is pressed 2 times in less than 300ms: the light on the corresponding side flashes indefinitely.

* If a turn button is pressed and the light on the other side is active: the light is deactivated.

* If the parking signal button is pressed: Both lights flash indefinitely.

* Major events can be identified through a serial communication console.
