# esp8266_SSD1306_ntpclient
Code example for SSD1306 and ESP8266 with the NTP client configured with the Brazilian server.
The SSD1306 is a library for write data in a OLED display. In my case, did use with the ESP8266 and OLED 0.96 pol.

I adapted example code of the SSD1306 for my use.
The code example is here: 
https://github.com/squix78/esp8266-oled-ssd1306/tree/master/examples/SSD1306ClockDemo

I used the NTPClient library:
https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266WiFi/examples/NTPClient/NTPClient.ino

Also I used the TimeLib library:
https://github.com/PaulStoffregen/Time

For last, the WifiUdp library for the make download of the NTP data:
https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266WiFi/src/WiFiUdp.cpp
