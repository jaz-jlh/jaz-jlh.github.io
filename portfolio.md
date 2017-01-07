# Jasbir Harnal Portfolio

---

## Projects:

---

![alt text][fan-mountain=timelapse]

---

### Smart Bike Light

Highlights:
* AC-DC Power Conversion
* Human-Machine Interfaces (HMI)
* Mechanical-Electrical Integration

For our final project in SYS 3048 Integrated Systems Design, we were tasked with creating a bike lighting solution. This project was intentionally left open ended so that we could embed ourselves in the problem to learn more about user needs and find out what we needed to design on our own rather than be given strict requirements. Our project team consisted of 2 computer engineers, 2 mechanical engineers, and 1 systems engineer. While we all had our own respective areas of expertise, we were required to interface with each other and understand the different disciplines within the project to ensure smooth integration. 

During this project I learned a great deal about AC to DC power conversion, the difficulties of working with an inconsistent power supply (a bike generator hub), and the non-trivial task of getting electrical and mechanical systems to integrate while still meeting design requirements.

### Semi-Quadcopter

Highlights:
* PID Control
* Kalman Filtering / Sensor Fusion
* I2C Protocol
* Multi-processor Management

This project was assigned as the final project in my Mechatronics course. All three of our team members were  mechanical engineering majors. Using an accelerometer, gyroscope, and ultrasonic sensor we had to control 2 degrees of freedom of a semi-quadcopter system with 2 propellers. We implemented a Kalman filter in our code to process the noise from the accelerometer and the drift in the gyroscope. The speed of the propellers was controlled using Proportional Integral Derivative (PID) control to adjust the power supplied to the motors through an H-Bridge with pulse-width modulation (PWM). I was responsible for the code and most of the 3D printed parts we designed to create our structure. The code was written in C for the Propeller microcontroller.

### Time-Lapse Camera Slider

Highlights:
* Independent Project
* Solidworks Components and Assembly
* Electromechanical Design and Integration

I am currently working on an independent project for fun which involves building an Arduino controlled slider for taking time-lapses. The slider will mount between two tripods, and stepper motors will move the carriage from one end to the other while the camera takes pictures at intervals. I constructed the slider portion of the project, and I have begun work on the carriage. I have also written most of the final code that will be necessary for operation. 
I designed the project in SolidWorks, and many of the parts were 3D printed on an Afinia 3D printer using my own designs. Other parts that were not 3D printed I specified and bought online. For some aluminum parts I used a horizontal band saw and lathe to make the parts, and some electronic parts also required soldering. 
This project was inspired by an Instructables.com project for a cheap DSLR slider rail using 3D printed parts. I had just finished an introductory course on mechatronics and microcontrollers and was interested in finding a project that could combine my passion for photography with my interest in mechatronics.

### Line-Following Robot

Highlights:
* Robot built from scratch
*

In my Intro to Electromechanical Systems class, we were assigned a group project. We were required to build an Arduino powered line-following automated delivery robot. I was in a team with systems and computer engineering majors. I was responsible for building the robot and coding in Arduino. I designed the chassis and mounting for the servo delivery system in Autodesk Inventor. The servo delivery system was 3D printed on an Afinia 3D printer, and the chassis was laser cut out of acrylic. I also created most of the circuits for the robot, and designed the chassis to fit all of the necessary components which included the battery pack, the Arduino microcontroller, breadboard, motors with encoders, and reflectance sensors. Our robot was the first to be successfully completed and the professor used our robot to test his code on.
During the following semester, I worked with my professor to update the code for the robot to be compatible with a WiFi shield that allowed the robot to move wirelessly. 

### Automated Greenhouse

Highlights:
* Thermal measurement and control
* PHP & SQL Database Communication
* Hysteresis for "bang-bang" control

During my spring semester 2nd year, I was in a group for an Arduino-powered automated desktop greenhouse project. The group consisted of myself the mechanical engineering major, a systems engineering major, and a computer engineering major. The project had aspects that each of us had knowledge in and that we would take the lead on. I was responsible for designing, 3D printing, and implementing a servo-motor controlled lid for the greenhouse. I used Autodesk Inventor to design the parts, and they were 3D printed on an ABS-extrusion Afinia printer.
During the course of the project, I also began writing a significant portion of the code, and by the end of the project most of the code had been written by me with assistance from the other team members with debugging. The code was written in C for the Arduino microcontroller. There were also PHP scripts and HTML documents that we needed for the project in order to have our greenhouse communicate with a database and display data on a website. For the internet communication coding, the systems and computer engineer wrote most of the code, but I also assisted with debugging. The project was successfully completed on time. 
Based on my performance, the professor invited me to revisit the project this semester for a cyber-physical security demonstration. We reconstructed the greenhouse and circuit, then modified the code to utilize numerical simulation to predict the temperature and detect when the greenhouse has been tampered with. This project was presented to the UVA Systems Engineering Advisory Panel as a demonstration of student capabilities in the realm of cyber-physical security systems.

[fan-mountain-timelapse]: https://jaz-jlh.github.io/images/fan-mountain-timelapse.gif "Timelapse at Fan Mountain"