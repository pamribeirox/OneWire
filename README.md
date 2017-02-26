# OneWire
Library for Dallas/Maxim 1-Wire Chips

This experimental fork adds the option to use 2 independent pins to drive the bus enabling some hardware tweaks
that (I hope) allow the bus to become larger

* The output pin can have inverted logic to drive a MOSFET in a "open drain" configutation
* The output pin can have an buffer added like the 74LCX07 (six open-drain)
