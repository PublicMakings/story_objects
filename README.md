# story_objects

THings to figure out: logic level shifters:
[sparkfun tutorial](https://learn.sparkfun.com/tutorials/bi-directional-logic-level-converter-hookup-guide)
[another overview](http://deloarts.com/en/hardware/logic-level-shifter/)


Shift register[adafruits tutorial](https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds)

Multiple RFID's 
[some video](https://www.youtube.com/watch?v=HmGmFknAIqc)

[General RFID](http://deloarts.com/en/scripts/arduino/rfid/)

[general power output arduinot](http://www.electricrcaircraftguy.com/2014/02/arduino-power-current-and-voltage.html)_

[how to power sparkfun tutorial](https://learn.sparkfun.com/tutorials/how-to-power-a-project)
[arduino power overview](https://www.open-electronics.org/the-power-of-arduino-this-unknown/)

[voltage divider](https://www.youtube.com/watch?v=XxLKfAZrhbM)
[voltage regulator](https://www.youtube.com/watch?v=J66_8P043ko)
##critical issues 
[logic level questions](https://electronics.stackexchange.com/questions/332150/problem-with-arduino-pro-mini-and-rc522)
[logic level conversion video](https://www.youtube.com/watch?v=t-yuYasIKtY)
[Multi-SPI and shift register](http://forum.arduino.cc/index.php?topic=319375.0)
[Multi SPI sparkfun](https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi)

components:  
*[Adafruit Feather HUZZAH ESP8266](https://www.adafruit.com/product/2821)*
>Measures 2.0" x 0.9" x 0.28" (51mm x 23mm x 8mm) without headers soldered in  
Light as a (large?) feather - 9.7 grams  
ESP8266 @ 80MHz with 3.3V logic/power  
4MB of FLASH (32 MBit)  
Built in WiFi 802.11 b/g/n  
3.3V regulator with __500mA peak current output__  
CP2104 USB-Serial converter onboard with 921600 max baudrate for speedy uploading  
Auto-reset support for getting into bootload mode before firmware upload  
9 x GPIO pins - can also be used as I2C and SPI  
1 x analog inputs 1.0V max  
Built in 100mA LiPoly charger with charging status indicator LED, can also cut a trace to disable the charger  
Pin #0 red LED for general purpose blinking. Pin #2 blue LED for bootloading debug & general purpose blinking  
Power/enable pin  

*12 x RC522 readers*
[data sheet](https://www.nxp.com/docs/en/data-sheet/MFRC522.pdf)
>Working current：13 - 26mA / DC 3.3V  
Standby current：10 - 13mA / DC 3.3V  
Sleep current：<80uA  
Peak current：<30mA  
Working frequency：13.56MHz  
Card reading distance ：0～60mm （Mifare1 card） 
Protocol：SPI  
Data communication speed：10Mbit/s Max.  
Card types supported: Mifare1  S50, Mifare1 S70, Mifare UltraLight, Mifare Pro, Mifare Desfire  

*Vellman amp*
[data sheet](https://www.velleman.eu/downloads/29/vma408_a4v01.pdf)

[3.7 watt amp](https://www.adafruit.com/product/987)
>Output Power: 3.7W at 3Ω, 10% THD, 1.7W at 8Ω, 10% THD, with 5V Supply  
Passes EMI limit unfiltered with up to 12 inches (30 cm) of speaker cable  
High 83dB PSRR at 217Hz  
Five pin-selectable gains: 6dB, 9dB, 12dB, 15dB and 18dB.  
Low current draw: 2mA quiescent and 10uA in shutdown mode2
