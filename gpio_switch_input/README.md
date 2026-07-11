## GPIO Switch Input
This simple program accepts input on the PB_3(D13) Pin of the Nucleo-L432KC board from a push button switch controls the output of PB_4(D12) Pin. These Pins are configured as GPIO pins for this application using STM Cube MX.

![Breadboard layout](../images/gpio_switch_input/gpio_switch_input_breadboard.jpg)

## Acknowledgments

This project was built while following these tutorials:

- [STM32 Getting Started Breadboard](https://www.youtube.com/watch?v=ljR8TSKqAZo) — external button and LED circuit setup
- [STM32 Lab Part 1 L432KC Pin Config](https://www.youtube.com/watch?v=W7-jnVpTD1M) — initial CubeIDE setup and project creation
- [STM32CubeIDE Programming, Debugging, and Running](https://www.youtube.com/watch?v=BVC7KaUNCS8) — Programming GPIO input/output and debugging walkthrough


Thanks to https://www.youtube.com/@seankennedy7610 the creator for these clear, beginner-friendly walkthroughs. While these are based on the older version of the STM32CubeIDE, they were still perfectly useful. The initial Pin setup and code generation is now done inside STMCubeMX and is separate from the Cude IDE.