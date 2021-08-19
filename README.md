# NodeMCU-Interfacing-with-Sensors

In this repository there are codes which I used while interfacing ESP8266 or Node MCU with different sensors. 

For example:
In Soil-Moisture Sensor, the following connections were made:

A0 of Soil Moisture Sensor => A0 of Node MCU.       
VCC of Soil Moisture Sensor => 3V of Node MCU.       
GND of Soil Moisture Sensor => GND of Node MCU

There after uploading the code into Node MCU, in the serial monitor the analog values were read which were observed to increase or decrease with removal and adding of moisture to the soil.

The setup has been shown in the following picture. Refer video for explanation of the same.

![WhatsApp Image 2021-08-19 at 15 15 02](https://user-images.githubusercontent.com/80844300/130051472-9f4f0456-1847-405f-add4-ab008a271172.jpeg)

More the water content, lower the corresponding analog value in the serial monitor.

![WhatsApp Image 2021-08-19 at 15 15 01](https://user-images.githubusercontent.com/80844300/130051415-477d7bbf-6fe1-4c0e-bd97-cf4b97cd6f2b.jpeg)


Similarly, I interfaced Node MCU with LCD to print " Hello World! This is so fun!" on its screen. Pictures have been shown below.

![WhatsApp Image 2021-08-19 at 15 15 04](https://user-images.githubusercontent.com/80844300/130051500-d752dd0b-3175-46f7-8945-d8c1c2702cbf.jpeg)

![WhatsApp Image 2021-08-19 at 15 15 04 (1)](https://user-images.githubusercontent.com/80844300/130051527-b7281d1c-487d-47fc-bdb5-889b70a120b0.jpeg)


Again when interfaced with accelerometer MPU6050, the x axis, y axis and z axis values could be observed on the serial monitor. 

![WhatsApp Image 2021-08-19 at 15 15 18 (1)](https://user-images.githubusercontent.com/80844300/130051595-a6fcc9bb-a629-42b7-bf87-e6b32693a169.jpeg)

![WhatsApp Image 2021-08-19 at 15 15 18](https://user-images.githubusercontent.com/80844300/130051564-26adc73c-8828-47c6-b555-d82be690b5a5.jpeg)


