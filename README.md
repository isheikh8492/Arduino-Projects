This is a collection of Arduino projects I worked on when I was learning about Arduino.

## Projects


### [Keyboard Instrument]()
* *Project Type: Arduino IDE(.ino)*

This project involved creating a piano instrument with 4 notes, which had four switches in parallel. In three branches we connected a resistor in series with the switch and in the fourth one a wire connected directly to power.

### [Motorized Pinwheel]()
* *Project Type: Arduino IDE(.ino)*

This project involved making a motorized pinwheel. In other words, we wanted a motor to spin. The first issue was that the motor needed more current and voltage than the maximum dispensable by the Arduino’s output pins. To solve it, a battery of 9V was used.

Another point was that we had to control the battery and the motor (high voltage) with low voltage (outputs from the Arduino’s pins). In order to achieve it, a transister. A transistor consists in three “parts”, each one connected to the protoboard: the gate, the source and the drain. When low voltage (the one that provides Arduino’s pins) hits the gate, it closes the circuit between the source and the drain allowing you to turn on motors, batteries… and control them.

### [Knock Lock]()
* *Project Type: Arduino IDE(.ino)*

This project involved creating a lock system that only can be unlocked by knocking 3 times.

For this project, 3 different colour Led, some resistors, a switch, a capacitor and a servomotor were needed.

By pressing the button the system will get locked, which will be indicated by the red LED. The knocks will be captured by the buzzer (remember that the buzzer can act like a speaker and a vibration sensor), and each time it detects a knock, the yellow LED will blink once. When we had knocked 3 times, the servomotor will turn 90º and the green led will be on. Indicating that the system is unlocked.