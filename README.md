# Solar-Powered Bluetooth Arduino Car

### Project Overview
This project demonstrates a solar-powered car controlled via Bluetooth using an Arduino. The car uses a solar panel to charge its battery, which powers the Arduino, motors, and Bluetooth module. Users can control the car wirelessly through a smartphone app.

### Features
* Forward, backward, left, right, and stop movement.
* Wireless control via HC-05 Bluetooth module.
* Powered sustainably by solar energy.
* Lightweight and portable design.

### Components Required
* Arduino Uno
* L298N Motor Driver Module
* HC-05 Bluetooth Module
* 2 DC Motors with wheels
* Solar panel (suitable for battery charging)
* Rechargeable battery (to store solar energy)
* Jumper wires and chassis

### Circuit Connections

1. Arduino to L298N Motor Driver:
* Motor1Pin1 → Arduino Pin 5
* Motor1Pin2 → Arduino Pin 6
* Motor2Pin1 → Arduino Pin 9
* Motor2Pin2 → Arduino Pin 10

2. Arduino to Bluetooth (HC-05):
* TX → Arduino RX
* RX → Arduino TX
* VCC → 5V
* GND → GND

### Power:
* Motors powered by battery charged via solar panel.
* Arduino powered from battery output.
  
### Software
* Arduino IDE for programming the Arduino.
* Mobile app (any Bluetooth controller app) to send commands:
* F → Forward
* B → Backward
* L → Left
* R → Right
* S → Stop

### How to Use
1. Upload the Arduino code to the Arduino board.
2. Connect the Bluetooth module to your smartphone.
3. Use a Bluetooth controller app to send commands.
4. Ensure the battery is charged by the solar panel.
5. Drive the car wirelessly using the app.

### Applications
* Robotics learning and experimentation
* Eco-friendly remote-controlled vehicles
* Solar energy-based automation projects

### Future Enhancements
* Add speed control using PWM.
* Include obstacle detection using ultrasonic sensors.
* Integrate a solar charging status indicator on the Arduino.
