# **AUTOMATIC FAN SPEED CONTROL**

## **ABSTRACT**

Technology is speeding quickly these days, and it has fully taken over people's lives. Despite the fact that technology plays such an important role in our daily lives, there are those whose lifestyles are completely unrelated to this well-known term. As a result, it is our obligation to design a few dependable methods that they can employ effectively. One of these is the Automatic Room Temperature Controlled Fan Speed Controller. The designed technology creates an atmosphere in which the fan speed is controlled by the system rather than the user. By monitoring the room temperature, you can change the fan speed automatically. These fascinating initiatives to construct intelligent systems are aimed at making life easier for humans. The circuit was created utilising electronic components that were readily available in the area.

# **DESCRIPTION**

This project is a self-contained automatic fan speed controller that regulates the speed of an electric fan to meet our needs. This closed loop feedback control system is efficient and reliable thanks to the use of embedded technology. The ATmega328 microcontroller enables for dynamic and speedier control. The microcontroller, which controls all of the circuit's functions, is its beating heart. The temperature sensor LM35 detects the temperature and converts it to an electrical signal that the microcontroller may use. The measured temperature values are presented on the LCD panel at the same time. The fan speed is controlled by the microcontroller via the motor driver. A controlled 12V, 2A power source is used in this project. This project can be used in the process industry to maintain and manage the temperature of boilers.

# **REQUIREMENTS**
- HIGH LEVEL REQUIREMENTS

<html>
<body>
<!--StartFragment-->

HLR_ID | High level Description
-- | --
HLR01 | It shall have a Sensor
HLR02 | It shall have a Microcontroller
HLR03 | It shall have a Fan
HLR04 | It shall have a Display

<!--EndFragment-->
- LOW LEVEL REQUIREMENTS
</body>
</html>

LLR_ID | Low level Description
-- | --
HLR01_LLR01 | It shall have a Temperature sensor(LM35) to measure the temperature of the room
HLR02_LLR02 | It shall have a Microcontroller(ATmega328) to recieve/transmit the data
HLR03_LLR03 | It shall have a Motor Driver to drive the motor
HLR03_LLR04 | It shall have a Motor to Spin the fan
HLR04_LLR05 | It shall have a LCD Display(16X2) to display the temperture of the room

<!--EndFragment-->
</body>
</html>

## **ADVANTAGES**

- It is cost-effective and simple to use.
- The fan starts up on its own.
- It's simple to put in heat-dissipating devices to keep them cool.
- Saves electricity by turning off the fan when the room temperature reaches a certain level.

## **APPLICATIONS**

- It can regulate the temperature of devices, rooms, and electronic components, among other things.
- It can be used as laptop or computer cooling pads.
- This gadget is used to keep the car engine cool.

# **BLOCK DIAGRAM**

[![156115015-84153921-dd31-4c30-94d8-e386cb172375](https://user-images.githubusercontent.com/101035721/164256292-be3c6687-8667-4955-b327-08e7b04de82c.jpg)](https://user-images.githubusercontent.com/77672209/157167968-8d641a78-fa2c-47aa-a002-8536939590f6.jpg)

# **FLOW CHART**

![image](https://user-images.githubusercontent.com/101035721/164256680-fddd891e-8e35-4ef6-8b12-267cd1d85eaa.png)

# **SYSTEM DESIGN**

![image](https://user-images.githubusercontent.com/101035721/164256894-d243d3ff-6cc4-414a-a508-11905a8dcac3.png)

# **SUB-SYSTEM DESIGN**

- Temperature sensor
![image](https://user-images.githubusercontent.com/101035721/164256971-32ca379a-9628-4a62-b572-a26ab622b157.png)

- Digital Temperature Sensor
![image](https://user-images.githubusercontent.com/101035721/164257042-ae56be4a-ed96-4674-bc23-0d325ce5c2d5.png)

- Motor Driver
![image](https://user-images.githubusercontent.com/101035721/164257202-a4541d44-7d2d-4091-a964-7240f121c277.png)

- DC motor
![image](https://user-images.githubusercontent.com/101035721/164257268-2f27f821-0aa7-4c29-b81d-d35b059dd1bd.png)

- LCD Display
![image](https://user-images.githubusercontent.com/101035721/164257316-b1b5db2e-4ee4-4c5d-890c-19a64e96348a.png)

# **COMPONENT DESCRIPTION**

- MICROCONTROLLER
An integrated circuit that contains a microprocessor along with memory and associated circuits and those controls some or all the functions of an electronic device (such as a home appliance) or system.

- Temperature Sensor
A temperature sensor is a device that is designed to measure the degree of hotness or coolness in an object. The working of a temperature meter depends upon the voltage across the diode

- Digital Temperature Sensor
The TC74 is a serially accessible, digital temperature sensor particularly suited for low cost and small formfactor applications. Temperature data is converted from the onboard thermal sensing element and made available as an 8-bit digital word.

- DC Motor
A DC motor is an electrical machine that converts electrical energy into mechanical energy. In a DC motor, the input electrical energy is the direct current which is transformed into the mechanical rotation.

- Motor Driver
The motor driver IC is an integrated circuit chip used as a motor controlling device in autonomous robots and embedded circuits. A motor driver is undoubtedly something that makes the motor move as per the given instructions or the inputs (high and low).

- LCD
LCD (Liquid Crystal Display) is a type of flat panel display which uses liquid crystals in its primary form of operation. LEDs have a large and varying set of use cases for consumers and businesses, as they can be commonly found in smartphones, televisions, computer monitors and instrument panels.