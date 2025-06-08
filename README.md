# COMPANY:- CODTECH IT SOLUTION
# NMAE:- SUMIT KUMAR
# INTERN ID:- CT04DF1595
# DOMAIN:- Internet Of Things
# DURATION:- 4 WEEKS
# MENTOR:- NEELA SANTOSH
# DESCRIPTION #
# OUTPUT:-
![Image](https://github.com/user-attachments/assets/59bf37d1-3f33-49ac-80f2-cce3678f4075)
![Image](https://github.com/user-attachments/assets/386171e3-4163-437f-b812-91a981077a2d)
An Air Quality Monitoring System using an ESP8266 microcontroller, MQ series smoke sensor, breadboard, and jumper wires, combined with ThingSpeak for data visualization, is a practical and cost-effective IoT project. It allows real-time monitoring and analysis of air pollutants like carbon monoxide, methane, smoke, and other harmful gases, especially in urban or indoor environments.

Hardware Components
ESP8266 (NodeMCU):
The ESP8266 is a low-cost Wi-Fi microcontroller unit capable of connecting to the internet. It is programmable through the Arduino IDE and can send sensor data to cloud platforms. It acts as the brain of the system, collecting data from sensors and transmitting it to the cloud.

MQ Smoke Sensor (e.g., MQ-2, MQ-135):
The MQ series sensors are gas sensors capable of detecting various gases like smoke, CO, CH4, and others. MQ-2 is commonly used for detecting smoke and flammable gases, while MQ-135 can detect harmful gases such as ammonia, benzene, and carbon dioxide.

Breadboard and Jumper Wires:
These components are used for prototyping the system. The breadboard allows easy circuit assembly without soldering, and jumper wires are used to connect the ESP8266 and sensor pins.

Working Principle
The MQ sensor detects gas concentration and produces an analog signal proportional to the gas level. This analog signal is read by the ESP8266, which then converts it into digital data. The ESP8266 is programmed to connect to a Wi-Fi network and transmit this data to a cloud platform such as ThingSpeak at regular intervals.

Software and Cloud Integration
Arduino IDE:
Used for programming the ESP8266. A simple sketch (program) reads the analog data from the MQ sensor and uploads it to ThingSpeak via HTTP or MQTT protocols.

ThingSpeak:
ThingSpeak is an open-source IoT platform for visualizing sensor data online. Users can create channels to store and view data. Graphs and analytics tools are available to understand trends in air quality over time.

System Workflow
Connect the MQ sensor to the ESP8266 using jumper wires (VCC to 3.3V, GND to GND, analog output to A0 pin).

Connect the ESP8266 to a computer and upload the Arduino sketch.

Configure Wi-Fi credentials and ThingSpeak API key in the code.

Power the ESP8266 using USB or an external source.

The sensor starts detecting gases and sends readings to ThingSpeak at intervals.

View real-time data and historical graphs on the ThingSpeak dashboard.

Applications and Benefits
Indoor Air Monitoring: Detect pollutants in homes, schools, or offices.

Early Warning Systems: Alert users of dangerous gas levels to prevent accidents.

Data Logging and Analysis: Enables researchers to study pollution patterns.

Smart City Projects: Can be scaled and integrated into larger IoT networks.

Conclusion
This air quality monitoring system is a simple yet powerful way to explore IoT and environmental sensing. It combines basic electronics with internet connectivity to make air quality data accessible and actionable. With minimal components and open-source tools, users can build a meaningful project to raise awareness and improve public health.
