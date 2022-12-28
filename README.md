# stm_ws2812b_hal_controller

## About

An example for controlling WS2812b RGB leds and led strips with an STM32F103 blue pill board and only STM32 HAL timers without wasting any SPI pins.

This is actually really hard.
There are bunch of overcomplicated or simply non-working examples out there.

**Credit for the WS2812b library actually goes to Nico Korn @(https://github.com/nicokorn/STM32F1XX_WS2812B/).
You are awesome!**

## Building

1. Load the project in STM32CubeIDE.

2. Build the project in debug or release mode.

3. Upload the corresponding ".bin" file to your bule pill development board 

	or 
	
   launch debug view with a ST-LINK debug probe attached.
   
4. Simply hook up your led(s) to 3.3v, GND and the PA0 pin and there you go!

Yay!

## License

[MIT](https://choosealicense.com/licenses/mit/)$

## TODO

Recreate library and example in Rust with stm32-rs...
