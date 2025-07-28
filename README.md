# STM32-T5000-MIDI
Techno T-5000 keyboard to midi keyboard conversion with STM32 blue pill (STM32F103C8T6) PC13

---

## How to use?
Just Flash

The current pinout for the keyboard keys are:

COL1_Pin GPIO_PIN_A0
COL2_Pin GPIO_PIN_A1
COL3_Pin GPIO_PIN_A2
COL4_Pin GPIO_PIN_A3
COL5_Pin GPIO_PIN_A4
COL6_Pin GPIO_PIN_A5
COL7_Pin GPIO_PIN_A6
COL8_Pin GPIO_PIN_A7
COL9_Pin GPIO_PIN_B0
COL10_Pin GPIO_PIN_B1

And

ROW1_Pin GPIO_PIN_B3
ROW2_Pin GPIO_PIN_B4
ROW3_Pin GPIO_PIN_B5
ROW4_Pin GPIO_PIN_B6
ROW5_Pin GPIO_PIN_B7

Examine the Column and Rows in the keyboard matrix before wire it up.

For the buttons:

SUSTAIN_PEDAL_Pin       GPIO_PIN_C13 // Configured as Input with Pull-up

OCTAVE_UP_Pin         GPIO_PIN_A8
OCTAVE_DOWN_Pin       GPIO_PIN_A9
