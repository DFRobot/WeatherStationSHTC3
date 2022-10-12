On a daily basis, people use weather forecasts to determine what to wear on a given day or to plan travel or events

However, it only tells temperature in a relatively large range. Sometimes we need environmental parameters in a specific place like a fishpond, greenhouse, an open field, etc. Here I want to know the exact temperatures during a day on my terrace. So I decide to make a weather monitoring station that outputs the real-time data I need. 

I got this environmental sensor from DFRobot that can measure temperature, humidity, pressure, ambient light, and UV, which is well suitable for this project.

This summer is much hotter than previous ones, and many places got record-breaking temperatures of over 40℃. For the sake of convenience, I add a UART fiber optic transceiver module in the project for data transmission, so I don't need to go outside to view data all the time. 

![image](https://user-images.githubusercontent.com/65546290/194977139-705bfcc6-511f-470c-aca0-a06c549d530d.png)
![image](https://user-images.githubusercontent.com/65546290/194977149-6655b0dc-e695-49ec-b270-95791ef44d37.png)



HARDWARE LIST
2
ESP32-E IoT Microcontroller
Link
1
Gravity: High Accuracy Temperature, Humidity, Pressure, Ambient Light and UV Sensor
Link
1
OLED Transparent Display
Link
2
UART Fiber Optic Transceiver Module
Link
1
SC-SC Single Mode Duplex Fiber Jumper (50m)
Link
1
Lithium Battery Charger
Link
2
3.7V Battery

 

Hardware Connection
 

Display End：
![image](https://user-images.githubusercontent.com/65546290/194977434-3c79a1b7-1b58-4788-8e3f-420865a5e48d.png)

Sensor End：
![image](https://user-images.githubusercontent.com/65546290/194977459-a110db60-59d5-4957-841c-ecf15e00bf72.png)


Test
Now we place the tripod holding the sensor end outside.
![image](https://user-images.githubusercontent.com/65546290/194977580-fbbae465-33b3-472b-9277-8172713d342f.png)

Connect the sensor end to the display end with optic-fiber cable.
![image](https://user-images.githubusercontent.com/65546290/194977612-7ec81863-b7e7-45b4-9791-f0e5b0d8edb2.png)

Then we can view the real-time temperature and humidity data at the display end.
If there is no data shown on your display, try exchanging pins TX and RX of one end.
![image](https://user-images.githubusercontent.com/65546290/194977658-7cdc6437-bb7e-473b-a031-08ef13ee3a18.png)


With the multi-functional environmental sensor, the weather station can also measure air pressure, ambient light and UV intensity besides temperature and humidity, so we can use our brains to make the most of it. For example, we can apply it to greenhouse planting monitoring, fishpond status view, laboratory experiments, etc. But we need to take good care of the display lest a backlight bleed may occur at the damaged corner and thus affect display effect.

 

Thanks for reading, feel free to leave your comments if you have any other good ideas!


The relevant information is uploaded on our YouTube channel. ——https://youtu.be/vxIjoycPucY
