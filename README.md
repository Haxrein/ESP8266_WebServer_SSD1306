# ESP8266_WebServer_SSD1306

 ESP8266 Web Server controlling OLED SSD1306 display


# ESP8266-SSD1306 Connections Pins

- D1 > SCL
- D2 > SDA
- 3V > VCC
- G > GND

# Usage

- Firstly, enter your Wi-Fi SSID and Wi-Fi password at line 6.
- Save and load to ESP8266
- Connect same Wi-Fi which you specified line 6

- When the ESP8266 is booted. You will see an IP address on the display. (For example 192.168.4.167)


# Send Message

- Go to that IP address any browser. You will see a blank page.
- Use this syntax to send message to ESP8266 http://your_ip_adress/?q=your_message
- If you send "logo" message to ESP8266. You will see a example logo on your display

- Also if you want to add your image to ESP8266 use this website: https://javl.github.io/image2cpp/

