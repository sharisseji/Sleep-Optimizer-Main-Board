# Sleep-Optimizer-Main-Board

This project uses two STM32 Microcontrollers to manually control and reset light and sound settings to provide an optimal sleeping environment. This board receives the UART signal from the secondary board to change the output of the LEDs and buzzer connected to it.

Code for the secondary board can be found [here](https://github.com/sharisseji/Sleep-Optimizer-Board-A.git).

The board type we used was the STM32 NUCLEO F401RE for both microctontrollers. The microcontrollers were programmed using STM32CubeIDE.

Functional code can be found in ECE198 -> Core -> Src -> main.c
