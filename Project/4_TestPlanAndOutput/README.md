# HIGH LEVEL TEST PLAN

|Test ID | Description | Exp I/P | Exp O/P | Exp O/P |
|--------|-------------|---------|---------|---------|
|HR_01    |Servo motor should ON/OFF             |Power supply         |  Servo Motor will ON/OFF        | Passed        |
|HR_02    |  Ultra-sonic sensor should sense the water level           | Water should be there in the tank to sense the level of water        |Sensor will sense the water level in the tank         | Passed  |
|HR_03    |  LED should glow RED/GREEN           | After sensing  Arduino will glow LED red or green        |   Red/green LED should glow      |    Passed     |
|HR_04    |         Voltmeter should measure the voltage    |      Potentiometer    |    Voltmeter will show the readings according to the potentiometer     |    Passed     |
<br/>

# LOW LEVEL TEST PLAN

|Test ID | Description | Exp I/P | Exp O/P | Exp O/P |
|--------|-------------|---------|---------|---------|
|LR_01    |Servo motor valve should be open when the water is less.            |Less water level        |  Servo Motor will ON      | Passed        |
|LR_02    | Servo motor valve should close when water is full.       | Full water level       |Servo Motor will OFF     | Passed  |
|LR_03    |  LED should glow Red when valve is open.          | Taking input from Arduino       |   Red LED will glow    |    Passed     |
|LR_04    |         LED should glow green when valve is closed.|     Taking input from Arduino    |    Green LED will glow    |    Passed     |
|LR_05   |      Potentiometer should regulate the voltage properly|     5V supply  |    Voltmeter will show the reading.    |    Passed     |
<br/>
<br/>


## OUTPUT
### When Motor is OFF and Green LED glows
![MOTOR OFF](https://user-images.githubusercontent.com/98867361/157077845-f3fc0a54-3b08-41b7-8da8-060162cafd9e.png)
<br/>
<br/>
<br/>

### When Motor is ON and Red LED glows
![MOTOR ON ](https://user-images.githubusercontent.com/98867361/157077891-b82621b7-0b3d-4693-a38c-c494abe38a98.png)


