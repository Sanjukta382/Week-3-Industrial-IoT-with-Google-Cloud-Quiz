# Week-3-Industrial-IoT-with-Google-Cloud-Quiz
Week 3

Sensor and Devices

Quiz 1: Choosing a sensor

1.Given the following information about temperature sensors, answer the questions listed below.
 
1. Negative Temperature Coefficient (NTC) thermistor
An NTC thermistor experiences such a large change in resistance per °C, small changes in temperature are reflected very fast and with high accuracy (0.05 to 1.5 °C). Because of its exponential nature, the output of an NTC thermistor requires linearization. The effective operating range is -50 to 250 °C for glass encapsulated thermistors or 150°C for standard.

2. Resistance Temperature Detector (RTD)
An RTD, consists of a film or, for greater accuracy, a wire wrapped around a ceramic or glass core. The most accurate RTDs are made using platinum but lower-cost RTDs can be made from nickel or copper. However, nickel and copper are not as stable or repeatable. Platinum RTDs offer a fairly linear output that is highly accurate (0.1 to 1 °C) across -200 to 600 °C. While providing the greatest accuracy, RTDs also tend to be the most expensive of temperature sensors.

3. Thermocouple
This temperature sensor type consists of two wires of different metals connected at two points. The varying voltage between these two points reflects proportional changes in temperature. Thermocouples are nonlinear, requiring conversion when used for temperature control and compensation, typically accomplished using a lookup table. Accuracy is low, from 0.5 °C to 5 °C. However, they operate from -200 °C to 1750 °C.

4. Semiconductor-based sensors
A semiconductor-based temperature sensor is placed on integrated circuits (ICs). These sensors are effectively two identical diodes with temperature-sensitive voltage vs current characteristics that can be used to monitor changes in temperature. They offer a linear response but have the lowest accuracy of the basic sensor types at 1 °C to 5 °C. They also have the slowest responsiveness (5 s to 60 s) across the narrowest temperature range (-70 °C to 150 °C).


You are designing a new pottery kiln. The maximum temperature in the kiln will be  816 °C. 

Which of the temperature sensors listed above should you use in the kiln? 

Ans: Thermocouple



2. You are designing an appliance that counts the number of animals that use a tunnel to cross under a highway. The highway is in the desert and when the temperature inside the appliance goes over 37.5°C you want a fan to turn on and cool the device. 
Using the same information on sensors listed above, which sensor would be a good choice for this design? 

Ans: Semiconductor-based


3. You are designing an industrial oven for a production line. The oven must heat parts to a very precise temperature range. This means the oven temperature must remain between 260 °C and 265°C.
Using the same information on sensors listed above, which sensor would be a good choice for this design?

Ans: RTD


Quiz 2: Sensor and Devices

1. You are designing an IoT system that measures a number of environmental factors in a factory: light, temperature, oxygen levels, air particle levels, and humidity.
You plan on placing sensors/devices in each room of the factory. For larger rooms you will place more sensors/devices (up to 10 in the assembly area).
What format should you use to send the data to the cloud? (Choose ONE)

Ans: It depends on the situation, a case can be made for either option. 


2. What are some tasks that you should consider carefully when designing an IIoT network? 

Ans: Receiving telemetry data, sending device commands, updating devices. 


3. When designing an IIoT network, you need to think about the future. Check all the characteristics that will contribute to an agile network.  (Choose TWO)

Ans: Use standard communication protocols that will make it easier to upgrade to new devices.
     The ability of the cloud side of the network to scale for streaming data. 


Communicating with Devices

Quiz 1: MQTT and HTTP

1. Why would someone prefer MQTT over HTTP for IoT?

Ans: MQTT is better than HTTP for resource constrained devices. 
     MQTT enhances the whole IoT system because when one client is not working the rest of the system continues to work. 
     MQTT is data-centric as opposed to document-centric like HTTP.


2. Which of the following are characteristics of MQTT?

Ans: MQTT includes the topic in the message. 
     MQTT keeps the channel open even when messages are not being sent.


3. Which of the following is a characteristic of HTTP?

Ans: HTTP is lighter weight than MQTT
