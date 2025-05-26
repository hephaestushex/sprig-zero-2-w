# sprig-zero-2-w
Hack Club's sprig, repurposed for a handheld retro gaming device.

It's modified to add 5 more buttons, for better gameplay.

# Instructions

Remove the Raspberry Pi Pico (W)(H), you will not need it.

Pinout:

note: the pins on the left are on the 40 pin header on the zero, and the pins on the right are the pins on the pico header on the sprig

Power Pins
- 3.3V - 3V3

Audio Pins
- GPIO21 - GPIO9 (DIN)
- GPIO18 - GPIO10 (BCLK)
- GPIO19 - LRCLK (GPIO11)

Display Pins
- GPIO25 - GPIO26 (RESET)
- GPIO24 - GPIO22 (D/C)
- GPIO08 - GPIO20 (TFT_CS)
- GPIO10 - GPIO19 (MOSI)
- GPIO11 - GPIO18 (SCK)
- 3.3V - GPIO17 (LITE)

Controller Pins - These are not specific. Use whatever on the pi side, but not on the pico side.
- GPIO02 - GPIO05 (BTN_W)
- GPIO03 - GPIO06 (BTN_A)
- GPIO04 - GPIO07 (BTN_S)
- GPIO17 - GPIO08 (BTN_D)
- GPIO27 - GPIO12 (BTN_I)
- GPIO22 - GPIO13 (BTN_J)
- GPIO00 - GPIO14 (BTN_K)
- GPIO05 - GPIO15 (BTN_L)

the rest of these pins do not connect to the sprig. Connect the grounds of the buttons and connect it to ground.
the other leads go to these pins.
- GPIO06 - Start Button
- GPIO13 - Select Button
- GPIO26 - Left Shoulder
- GPIO20 - Right Shoulder
- GPIO16 - Hotkey Button

 


