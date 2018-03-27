# BBCKeyboard
Arduino code to drive an Acorn BBC micro keyboard

If you use an arduino with a USB transceiver (e.g. arduino pro micro, arduino pro mini, leonardo) then the BBC keyboard will look like a normal USB keyboard. The main issue will be the keymap which will default to a PC keymap meaning some keys are correct but a lot of the symbols aren't. For other arduinos the keyboard will send characters to the serial port.

At the moment caps lock works but shift lock doesn't. Instead the shift lock key acts like an alt key because it will be more useful. Also, the function keys are PC style, starting from f1 instead of f0.

