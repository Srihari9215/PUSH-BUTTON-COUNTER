# PUSH-BUTTON-COUNTER

COMPANY: CODTECH IT SOLUTIONS

"NAME: SRIHARI A

"INTERN ID: CT04DY35

"DOMAIN: FRONT END DEVELOPMENT"

DURATION: 4 WEEEKS

"MENTOR: VAISHALI"

Description:
🔥 Temperature Monitoring System Using LM35 and LEDs
📋 Project Description:

This project is a simple temperature monitoring system built using an Arduino, an analog temperature sensor (e.g., LM35), and three LEDs to provide a visual indication of temperature levels. The system continuously reads temperature data from the sensor, displays it on the Serial Monitor in both Celsius and Fahrenheit, and lights up LEDs based on how high the temperature is compared to a defined baseline temperature.

⚙️ How It Works:

The analog temperature sensor (connected to pin A0) reads the ambient temperature.

The raw analog value is converted into Celsius and Fahrenheit using a formula and the map() function.

A baseline temperature is set (e.g., 40°C), and based on how much the current temperature exceeds this value, LEDs are turned on to indicate rising temperature levels:

LED1 ON: Temperature is between 40°C and 49°C

LED1 + LED2 ON: Temperature is between 50°C and 59°C

All 3 LEDs ON: Temperature is between 60°C and 69°C

All 3 LEDs ON (overheat condition): Temperature is 70°C or higher

The Serial Monitor prints the real-time temperature in both Celsius and Fahrenheit every second.

🔌 Hardware Used:

Arduino Uno

LM35 Temperature Sensor (or similar analog sensor)

3 LEDs (Red, Yellow, Green)

3 Resistors (220Ω – 330Ω)

Jumper Wires

Breadboard

🎯 Applications:

Overheat detection in small electronics

Simple temperature threshold alert system

Educational purposes for learning sensor interfacing and condition-based outputs

Output:

https://github.com/Srihari9215/PUSH-BUTTON-COUNTER/issues/1#issue-3325147696
