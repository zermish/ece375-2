Brew install avrdude

The magic invocation of avrdude is
avrdude -p ATmega128 -P usb -c usbasp -U flash:w:<file>
Consult man avrdude for details.

Get a pile of avr code from
http://web.engr.oregonstate.edu/~johnstay/ece375/code/BasicBumpBot.asm


Oh god, we're rebuilding avrdude
http://web.engr.oregonstate.edu/~johnstay/ece375/pdf/mac-avr.pdf
