# low-power-sensor
A SENSOR is defined as a device that receives a signal or stimulus and responds to it by generating an electrical signal. The output signals correspond to some forms of electrical signal, such as current or voltage, which can be easily measured.
--> The state machine states decide whether the sensor transmit/idle state. it can be selected by using the state logic.
--> SENSOR is 8-bit data-width and if device is idle state then it holds upto the sleep counter=0, the sleep counter is count starts from 2^16 to 0
--> if device is under transmit state then it moves data from data register to sensor data register
