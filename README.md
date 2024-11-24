This experience is using bluepill STM32 board in FreeRTOS in the STM32Cube IDE.
The proposal of the project is initially, the LED in PA1 is off (State 0).
Pressing the button on PB0 (PUSH_BUTTON):
First time: LED flashes at 1 Hz (State 1).
Second time: LED flashes at 10 Hz (State 2).
Third time: LED flashes at 20 Hz (State 3).
Fourth time: LED goes out again (State 0).
The cycle continues with each button press.
