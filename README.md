# Mejeriet + ESP32 DevKit 01 + 0.91 inch OLED

## ESP 32 Datasheet
https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf

## ESP32 DEVKIT 1 PinOut
D22 - OLED I2C SCK
D21 - OLED I2C SDA

## Setup arduino IDE for ESP32
https://randomnerdtutorials.com/getting-started-with-esp32/#esp32-arduino-ide

Use Arduino IDE 1.8.19 (old arduinno IDE) for ESP32

Select board: DOIT ESP32 DEVKIT 1

## Connect OLED to ESP32
https://esp32io.com/tutorials/esp32-oled?utm_content=cmp-true

OLED display is:
0.91 Inch 128x32 IIC I2C White / Blue OLED LCD Display DIY Module SSD1306 Driver IC DC 3.3V 5V

## LED Connection
https://www.instructables.com/Blinking-an-LED-With-ESP32/

- Connect the negative pin (cathode) of the LED, indicated as the flat edge of the LED to ground, shown as the blue wire.

- Connect the positive pin (anode) of the LED, indicated as the rounded edge of the LED to a 100Ω resistor.

- Connect the free end of the resistor to pin D5 on the ESP32, shown as the red wire.

- The Cathode of the super bright LED's are the chipped corner

## OSC Communication with ESP32
https://github.com/CNMAT/OSC/blob/master/examples/ESP8266ReceiveMessage/ESP8266ReceiveMessage.ino

