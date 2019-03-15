# Thermocouple Amplifier MAX31855 (MAX6675 upgrade)

<a href="http://www.adafruit.com/products/269"><img src="assets/board.jpg?raw=true" width="500px"></a>

Thermocouples are very sensitive, requiring a good amplifier with a cold-compensation reference. The MAX31855K does everything for you, and can be easily interfaced with any microcontroller, even one without an analog input. This breakout board has the chip itself, a 3.3V regulator with 10uF bypass capacitors and level shifting circuitry, all assembled and tested. Comes with a 2 pin terminal block (for connecting to the thermocouple) and pin header (to plug into any breadboard or perfboard). [Goes great with our 1m K-type thermocouple](https://www.adafruit.com/product/270).

[If you need a thermocouple interface that can handle other types of thermocouples, check out our 'Universal' MAX31856 amplifier board which can be configured in the Arduino sketch to interface with just about any kind of thermocouple](https://www.adafruit.com/product/3263)


New! Now uses the MAX31855K instead of the MAX6675, so it can measure a wider temperature measurement range. Please note! the MAX31855 is not pin compatible or drop-in code compatible with the MAX6675. We do have an Arduino library for both chips but you'll need to adjust any existing MAX6675 designs for the new MAX31855. The MAX6675 has been discontinued by Maxim.

- Works with any K type thermocouple
- Will not work with any other kind of thermocouple other than K type
- __-200°C to +1350°C output in 0.25 degree increments__ - note that K thermocouples have about ±2°C to ±6°C accuracy
- Internal temperature reading
- 3.3 to 5v power supply and logic level compliant!
- SPI data output requires any 3 digital I/O pins.

[Hey we even have a handy tutorial on thermocouples which includes both CircuitPython and Arduino libraries, wiring diagrams and example code. How easy is that?](https://learn.adafruit.com/thermocouple/)
