This project is a simple intruder detection system using an ultrasonic sensor. The sensor continuously measures the distance of any object in front of it. It works by sending sound waves and receiving the echo back.

When an object comes closer than a fixed distance (around 25 cm), the system detects it as an intruder.The distance is calculated using the time taken for the sound wave to travel to the object and return back. This is done using the speed of sound.
This helps us in reducing the damage of the rover. When it senses some intruder or obstacle, the buzzer beeps and the LED glows giving us the signal.

The Components used are:
1. Arduino UNO
2. Ultrasonic Sensor (HC-SR04)
3. LED
4. Buzzer
5. 220Ω resistor

As per my research, these components are used for the following purposes: 
Ardiuno UNO reads data from the sensor and controls the LED and buzzer based on the program.
Ultrasonic Sensor sends sound waves and calculates how far an object is by measuring the time taken for the echo to return.
LED to glow and indicate intruder and buzzer to produce beep sound.

While building this circuit, the wiring may go wrong. So that should be taken care off.
For unstable sensor readings, we can take multiple readings or add a small delay in the program to make the values more stable.
