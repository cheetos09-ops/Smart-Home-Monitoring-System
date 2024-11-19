# Smart-Home-Monitoring-System

This project is a Smart Home Monitoring System using an Arduino, sensors, an OLED display, and a buzzer. It monitors temperature, humidity, air quality, and proximity, providing real-time feedback and alerts to ensure a safe home environment.

## :star2: Features
- _Temperature and Humidity Monitoring:_ Uses a DHT11 sensor to continuously monitor and display real-time temperature and humidity.
- _Air Quality Monitoring:_ Utilizes an MQ-135 gas sensor to monitor air quality, providing feedback on whether the air quality is "Good" or "Bad."
- _Proximity Detection:_ An ultrasonic sensor monitors the distance to nearby objects and triggers an alert if the object is too close.
- _OLED Display:_ Displays sensor readings such as temperature, humidity, air quality, and proximity alerts on an easy-to-read OLED screen.
- _Buzzer Alerts:_ A buzzer sounds an alarm when the proximity sensor detects an object within a defined distance, making it useful for security and home safety.

## :toolbox: Components

- **DHT11 Sensor:** Measures temperature & humidity.
- **MQ-135 Sensor:** Monitors air quality.
- **Ultrasonic Sensor (HC-SR04):** Measures distance for proximity alerts.
- **OLED Display (SSD1306):** Displays sensor data.
- **Buzzer:** Sounds alert when an object is too close.

## :gear: Installation

### Hardware: 

![image](https://github.com/user-attachments/assets/2cbd5483-6e43-4888-8826-0c70a113720b)

### Libraries:

Install these libraries: Adafruit SSD1306, Adafruit GFX, DHT sensor library

Upload the Code to your Arduino and run the system.



## :hammer_and_wrench: Applications
1. **Home Air Quality Monitoring:** Continuously track indoor air quality to maintain a healthy environment.
2. **Home Security:** The proximity sensor can detect objects or intruders within a certain distance and trigger an alert.
3. **Smart Home Systems:** Integrate with other home automation systems for enhanced functionality.


