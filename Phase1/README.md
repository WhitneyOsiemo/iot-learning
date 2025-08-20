 # I have returned to the fundamentals of electronics. Learning about voltage, current, and resistance. 

The relationship of the fundamentals through Ohm's Law.
LED Basics and Using the Multimeter.


Voltage is also referred to as potential difference.
How to limit the current flowing through an LED using a resistor.
How to use a resistor colour calculator to choose the right resistor.

  # Understanding the difference between analogue and digital signals
  [Difference between analog and digital signals](https://www.geeksforgeeks.org/physics/difference-between-analog-and-digital-signal/)
  

Both are electrical signals used to transmit information in various electronic systems.

Analogue - Continuous data using a continuous range of values. Can take on any value within a certain range.
         - Circuit components- Amplifiers, filters, continuous wave oscillators.
         - The signal is continuous and varies smoothly over time.

         
Digital - represents data as a sequence of discrete values, typically using binary numbers. 
        - Circuit component- Microprocessors, binary counters, logic gates.
        - The signal is discrete and is represented by a series of discrete values.

        Analogue to digital conversion(ADC)
        1. Pulse code modulation
           - Sampling
           - Quantization
           - Encoding
        2. Delta modulation
        3. Adaptive Delta modulation

  # MICROCONTROLLERS
  [Introduction to microcontroller](https://www.circuitbasics.com/introduction-to-microcontrolleres/)
  
  Microcontrollers read the voltage from an input device and use this information to decide on the correct voltage to output.
  -Embedded in an integrated circuit (IC)
  
          Integrated circuit - miniature electronic devices that combine multiple components.
          Integrates: Processor, program memory, RAM, input/output pins.


          -Development boards; Raspberry Pi
                               Arduino Uno

                               
      Programming microcontrollers.
            Arduino - IDE, write the Arduino code and upload it to the microcontroller via USB cable. 

  # SENSOR INTERFACING
  [Sensor interfacing](https://www.electronicsforu.com/technology-trends/learn-electronics/sensor-interfacing)
  [Sensors and sensing technologies](https://www.electronicsforu.com/technology-trends/tech-focus/sensor-technology-solutions)
              
  Process of connecting sensors to microcontrollers or other processing systems. 
  
               It enables the microcontrollers to; 
                  -Acquire the signals from the sensors
                  - Process and interpret the data from the sensor
                  - Control devices or actuators based on the input
                  
  Principle- integrates hardware and software components to achieve accurate and reliable measurement and control.
  
              # Types of sensors.
               1) Based on output type: Analog and digital
               2) Based on the type of measurement: Temperature, Pressure, Light, Motion, Humidity, Gas.
               3) Based on the working principle: Resistive, Capacitive, Inductive, Piezoelectric.
               4) Based on power supply: Active and passive.
               5) Based on contact type: Contact and non-contact
               6) Based on the application: Industrial, Automotive, Environment.

              Sensing technologies
                  a) Inductive
                  b) Capacitive
                  c) Magnetic( Hall effect)

# SIGNAL CONDITIONING
Modifying, filtering and amplifying the output signal

             Importance;
                1. Improves SNR ratio
                2. Match sensor output to system requirements
                3. Reduce noise and other interferences 
                4. Enhance signal fidelity

             Types;
                1. Amplification - Operational Amplifier
                2. Filtering
                3. Excitation
                4. Isolation
                5. Linearization 

  # Choosing communication protocols in digital sensor interfacing
  Communication protocols- Standardised rules and procedures that enable digital devices to exchange data efficiently. 

               Various communication protocols
                 1. Parallel - PCI, ATA, ISA
                 2. Series- I^2C, SPI, USB
                 3. Wireless - Wi-Fi, IoT devices(Zigbee, LoRa),Smartphone|Bluetooth

               Handling noise and signal interference
                   : a. Hardware solutions
                      1. Grounding techniques 
                      2. Cable management
                      3. Shielding
                     b. 
                       1. Digital filters
                       2. Averaging techniques
                       3. Advanced filtering algorithms 

               Best practices for sensor interfacing: 
                       1. Stable power supply
                       2. Regular calibration
                       3. Use of pull-up pr pull-down resistors
                       4. Efficient data acquisition and sampling
                       5. Testing and validation

         
                       
               









































