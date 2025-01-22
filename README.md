# Line-following-robot-MCT-Group-11
The line follower robot is a mobile machine that can detect and follow the line drawn on the floor. Generally, the path is predefined and can be either visible like a black line on a white surface with a high contrasted color or it can be invisible like a magnetic filed. Definitely, this kind of robot should sense the line with its infrared ray (IR) sensors that installed under the robot. After that, the data is transmitted to the processor by specific transition buses. Hence, the processor is going to decide the proper commends and then it sends them to the driver and thus the path will be followed by the line follower robot. In this line-follower robot, we use IR transmitters and receivers (photodiodes). They are used to send and receive the lights. When IR rays fall on a white surface, they are reflected toward the IR receiver, generating some voltage changes.

# **Components Used in Line Follower Robot**                                                                                                                                                                           
**1. Arduino Uno**  
Arduino Uno is an 8-bit ATmega328P microcontroller. To support the microcontroller, it uses components such as a crystal oscillator, serial communication, voltage regulator, etc. It has 14 digital I/O pins( 6 pins can be used as PWM pins). It has six separate analog input pins, a USB connection, a power barrel jack, an ICSP header, and a reset button. This board is programmable with the Arduino IDE (Integrated Development Environment) platform via a type B USB cable. This board can be powered via a USB cable or an external voltage ranging from 7 to 20 volts.

**2. IR sensor**       
An infrared sensor emits light to detect certain surroundings. In the infrared spectrum, all the objects radiate some form of thermal radiation that is invisible to our eyes, but an IR sensor can detect these radiations.
Here, the IR LED is an emitter, and the IR photodiode is a detector. An IR LED emits the IR light, and the photodiode is sensitive to this IR light. When IR light falls on the photodiode, the output voltages and the resistances will change in proportion to the magnitude of the received IR light. The infrared detection system uses five essential elements: an infrared source, a transmission medium, an optical component, infrared detectors, and signal processing. Infrared transmission can be done through the vacuum, atmosphere, and optical fibers. 

**3. L298 motor driver**           
L298N is one of the easiest and best ways to control DC motors. It is the two-channel motor driver that can control the speed and spinning direction of DC motors.
This L298N motor driver is a high-power motor driver module. It is used for driving DC and stepper motors. This motor driver consists of an L298N motor driver IC and a 78M05 5V voltage regulator, resistors, capacitor, power LED, and 5V jumper in an integrated circuit. When the jumper is placed, it enables the 78M05 voltage regulator. When the power supply is less than or equal to 12 volts, the voltage regulator will power the internal circuitry. When the power supply is more than 12 volts, then the jumper should not be placed and should give a separate 5 volts to power the internal circuitry.

**4. Wheels**

**5. Jumper cables**

# **Softwares Used to build the Line Follower Robot** 
**1. Proteus**           
**2. Arduino IDE**

# **Applications of a Line Follower Robot**
**i. Industrial Applications**      
Line-following robots help to transport materials from one place to another, such as in the automotive assembly process. They help inspect the products and detect flaws, which can help in quality control and increase efficiency. They can also detect potentially hazardous environmental situations, such as a blocked pipe or a malfunctioning machine.

**ii. Automobile Applications**      
Line-following robots are helpful in automobile applications, such as autonomous driving. Autonomous vehicles use sensors and cameras to detect the environment and use line-following robots to stay in the correct lane and maintain a safe speed. Additionally, this technology can help reduce accidents and make driving safer.

**iii. Domestic Applications**      
Line-following robots help in various domestic applications, such as vacuum cleaners and robot mops. These robots use sensors to detect obstacles and stay on the right path, allowing them to clean more efficiently. Furthermore, they are increasingly applicable in lawnmowers and pool cleaners, helping to make these tasks more accessible and efficient.

**iv. Guidance Applications**      
Line-following robots are helpful for guidance applications, such as in museums and other tourist attractions. Manufacturers can program these robots to guide people around a particular area and provide information about the interests they are visiting. Additionally, they can help give directions to visitors and provide information about the area’s history.
