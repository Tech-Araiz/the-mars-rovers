#SOFTWARE REQUIREMENT SPECIFICATION
##FUNCTIONAL REQUIREMENTS
### FR1:
The system must connect to and communicate with multiple rovers at the same time.

### FR2:
The system must let operators send different commands to each rover individually.

### FR3:
The system must allow operators to send a single command to all connected rovers at once.

### FR4:
The rover shall enter Safe Mode within 3 seconds when
battery temperature exceeds the critical threshold or
battery capacity falls below the defined emergency level.

### FR5:
The system must automatically try to reconnect if a rover drops its signal.

### FR6:
The system must save a history log of every command sent and every response received from each rover.

##NON FUNCTIONAL REQUIREMENTS
### NFR1:
The rovers must respond to control commands in under 1 second.

### NFR2:
A new user must be able to view and select any connected rover within 2 clicks on the main screen.

### NFR3: Scale to 20 Rovers
The system must run smoothly with up to 20 rovers connected at once without slowing down.

### NFR4: 99.9% Uptime
The control software must remain online and running 99.9% of the time during active work shifts.
