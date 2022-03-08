# **WATER SUPPLY CONTROL SYSTEM**
<br/>

## **ABSTRACT**
> Water tank overflow is a common problem which leads to the wastage of water. This circuit will detect the water level and will blink a red or green colour upon getting the water tank full or a preset level. Water level indicator is a modern way of measuring the water level using latest technologies like sensors, Arduino. The main aim of the project is to observe the water level at any instant of time using Arduino, Servo Motor and Ultrasonic sensor to make it possible. As the motor will turn off when the tank fulls with water so that the water will not overflow. This may be useful in saving water from getting waste.
<br/>

## **DETAILED REQUIREMENTS**

## **High Level Requirements**
| ID | Description | 
| ----- | ----- | 
| HR01 | Servo motor should ON/OFF |
| HR02 | Ultrasonic Sensor should sense the level of water |
| HR03 | LED should glow RED/GREEN |
| HR04 | Voltmeter should measure the voltage |

## **Low level Requirements**
| ID | Description | HLR ID |
| ------ | --------- | ------ |
| LR01 | Servo motor valve should be open when the water is less. | HR01 |
| LR02 | Servo motor valve should close when water is full. | HR01 |
| LR03 | LED should glow Red when valve is open. | HR03 |
| LR04 | LED should glow green when valve is closed. | HR03 |
| LR05 | Potentiometer should regulate the voltage properly. | HR04 |
<br/>

## **BLOCK DIAGRAM**
![WaterLevelControl](https://user-images.githubusercontent.com/98867361/155748963-c843c468-5965-4576-a6c3-b16b751cb8f5.png)
<br/>

## **Description**

### Arduino
-  Arduino UNO is a low-cost, flexible, and easy-to-use programmable open-source microcontroller board that can be integrated into a variety of electronic projects. This board can be interfaced with other Arduino boards, and can control relays, LEDs, servos, and motors as an output. 

### Servo Motor
-  The function of the servo motor is to convert the control signal of the controller into the rotational angular displacement or angular velocity of the motor output shaft. Servo motor is used to drive the joints

### Ultrasonic Sensor (HC-SR01)
-  To determine the distance to the water, it transmits a sound pulse that reflects from the surface of the water and measures the time it takes for the echo to return. To automatically control open and close the water gate, we use Ultrasonic sensors as input values.

### LED
-  LED is a semiconductor device used in many electronic devices, mostly used for indication purposes. It is used widely as indicator during test for checking the validity of results at different stages. It is very cheap and easily available in variety of shape, color and size. The LEDs are also used in designing of message display boards and traffic control signal lights etc.

### Potentiometer
-  The mechanical system of sensor is destined to convert linearly the value of potentiometer resistance to the water level variation. The signal conditioning consists of analog and digital system especially microcontroller circuit.

### Voltmeter
-  Voltmeters can also be used to measure DC voltage as well as sinusoidal AC voltages but the introduction of a voltmeter as a measuring instrument into a circuit can interfere with its steady state conditions.
<br/>

## **4W's and 1'H**

### Who
- Anyone in industrial and domestic purpose can use this system

### What
- This system will turn ON/OFF the motor depending upon the level of water in the tank

### When
- Depending on the water level it will ON/OFF the motor

### Where
- In industrial as well as domestic purposes.

### How
- This system controls the motor depending on the water level in the tank
<br/>

## SWOT analysis
![SWOT_Analysis](https://user-images.githubusercontent.com/98867361/157009221-dc6bd894-d7ac-410d-aa67-156b6ee374d2.png)
<br/>

## **Applications**
- Can be used in water tanks to control water levels.

- Automatically turn ON/OFF pumps.

- Can be used in factories, commercial complexes, apartments, home.

- Oil tank level control.

- Pool water level control.
<br/>

## HIGH LEVEL TEST PLAN

|Test ID | Description | Exp I/P | Exp O/P | Exp O/P |
|--------|-------------|---------|---------|---------|
|HR_01    |Servo motor should ON/OFF             |Power supply         |  Servo Motor will ON/OFF        | Passed        |
|HR_02    |  Ultra-sonic sensor should sense the water level           | Water should be there in the tank to sense the level of water        |Sensor will sense the water level in the tank         | Passed  |
|HR_03    |  LED should glow RED/GREEN           | After sensing  Arduino will glow LED red or green        |   Red/green LED should glow      |    Passed     |
|HR_04    |         Voltmeter should measure the voltage    |      Potentiometer    |    Voltmeter will show the readings according to the potentiometer     |    Passed     |
<br/>

## LOW LEVEL TEST PLAN

|Test ID | Description | Exp I/P | Exp O/P | Exp O/P |
|--------|-------------|---------|---------|---------|
|LR_01    |Servo motor valve should be open when the water is less.            |Less water level        |  Servo Motor will ON      | Passed        |
|LR_02    | Servo motor valve should close when water is full.       | Full water level       |Servo Motor will OFF     | Passed  |
|LR_03    |  LED should glow Red when valve is open.          | Taking input from Arduino       |   Red LED will glow    |    Passed     |
|LR_04    |         LED should glow green when valve is closed.|     Taking input from Arduino    |    Green LED will glow    |    Passed     |
|LR_05   |      Potentiometer should regulate the voltage properly|     5V supply  |    Voltmeter will show the reading.    |    Passed     |
<br/>

## OUTPUT

### Output when Motor is ON and Red LED glows
![MOTOR ON ](https://user-images.githubusercontent.com/98867361/157002862-32bc6f64-fc17-4d22-9c85-3f8354e821e7.png)
<br/>

### Output when Motor is OFF and Green LED glows
![MOTOR OFF](https://user-images.githubusercontent.com/98867361/157002918-135093ab-6c18-4403-895f-7148162afd5a.png)
