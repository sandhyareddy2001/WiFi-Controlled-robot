ARDUINO BASED WIFI CONTROLLED INTELLIGENT ROBOT WITH RECORDER


 
ABSTRACT-It is 2020; the world has technically grown in a very drastic way in the past few decades. Many countries have implemented robots in various fields robots have replaced humans in performing repetitive and dangerous tasks .Object transportation robot has become a very important part of modern science and exploration. This types of robots are used in various sectors including astronomy, mining and industries. In this report the design and construction of an object transportation robot have been described elaborately. This particular robot can be controlled from a remote distance using radio frequency. There are basically three major parts of the robot: receiver- transmitter couple, chassis mounted on the wheels and the robotic arm. Two ATmega32 microcontrollers have been used for the purpose, one in the transmitter and the other in the receiver. In the receiver this microcontroller receives the rf signal and controls the robot according to the instruction. The movement of robot is controlled using 2 DC motors coupled with each other wheel. So, we as students and the future engineers, our team came to an idea of creating a robot, which can be controlled through phone or any device .in addition, this paper gives a broad idea about designing a remotely controlled two-wheeled intelligent robotic  rover over a wifi network by using an arduino.uno connected to an ESP8266-wifi  module.
Keywords-Gesture; Arduino; RF Robot; WiFi- module ESP8266; Wireless; DC motor
1.INTRODUCTION
One of the major uses of robot is their flexibility and ease with which they can be used in all places. The project particularly aims for those places where human involvement is difficult and dangerous such as places where a building is collapsed or fire accidents etc..
	Our motive is to implement and design an intelligent arduino board based robot that can be driven remotely using ESP8266 WIFI module over a wifi network. The design of the robot is in such a way that it can be controlled remotely by any android device through an app, which can control the speed of the moving rover and the direction in which it is being headed to. This paper is a proposal to the idea of installing the audio receiver, which records the sounds in the surroundings of the rover and also has the capability to transmit the message that the controller wants to send. It is basically the implementation of two – way radio transceiver in the intelligent rover.  In section 1, there is a detailed description of the hardware required for the project and their working. The basic hardware required are Arduino UNO board, ESP8266 wifi module, L298 motor driver module and male-female wires. 
This section consists 8 different modules in the code. In section 2, there is a detailed explanation of the arduino code required to run the robot.  In section 3, complete details of the android app to control the wifi controlled robot is given. In this project, we create an android app through MIT app creator, which can be integrated to the arduino set up and run.
Section 4 consists of the future implementations in the project and better ways to improve the quality and efficiency of the project.
  

              2. PROBLEM STATEMENT
Many countries have implemented robots in various fields robots have replaced humans in performing repetitive and dangerous tasks .Object transportation robot has become a very important part of modern science and exploration. This types of robots are used in various sectors including astronomy, mining and industries. In this report the design and construction of an object transportation robot have been described elaborately.
Robots produce more accurate and high quality work. Robots rarely make mistakes and are more precise than human workers. They can produce a greater quantity in a short amount of time. They can work at a constant speed with no breaks, days off, or holiday time.
Object  transportation  robots  have  become  a  very  important  part  of  modern  science  and 
exploration. These types of robots are used in various sectors including astronomy, mining 
and industries. In this  report the design and construction of an  object transportation robot 
have  been  described  elaborately.  This  particular  robot  can  be  controlled  from  a  remote 
distance using radio frequency. There are basically three major parts of this robot, receiver-
transmitter  couple,  chassis  mounted  on  the  wheels  and the  robotic  arm.  Two  ATmega32 
microcontrollers have  been  used  for this  purpose, one in the  transmitter and the  other  in 
the  receiver.  In  the  receiver,  this  microcontroller  receives  the RF  signal and  controls  the 
robot according to  the  instruction. The movement of this robot is controlled using  four  DC 
motors coupled  with  each  wheel.  The  speeds  of  these  DC  motors  determine  whether  the 
robot will go forward, reverse or take a turn. And finally three servo motors have been used 
to grab any object precisely, located in the shoulder, arm and claw. The accurate operation 
of all these three parts ensures the operation of the complete RF controlled robotic system 
for object transportation. 
3. RELATED WORK
Various researches [1] have been made by different researchers in developing this project however, they served a different application and have different technologies implemented. Some of these papers are mentioned below stating their technology and application.
In 2015 Muhammad Gulfam et al., created a surveillance robot using socket programming [6]. This paper presents way of controlling a surveillance robot using android mobile devices through socket programming. Socket is one of the major technologies of Computer Network programming
In 2017 Bharath Kumar [2] along with their researchers implemented a robot car using micro contoller arduino.They proposed a model which uses a wifi module ESP8266 along with an HTML interface for controlling the robot 
Few other researchers [5] did an implementation of the fundamental concept of wireless communication on a small scale. They extended the remote control application of RF to operated bot.
[3] Controlled the robot by using the Front Panel of LABVIEW. This robot is not exactly massive one and intended to be simple transportation. Transmitting section consists of RF-transmitter, ARDUINO UNO and a LabVIEW platform. In this project, we have built a simple Robot (robotic car) that can be controlled over WiFi Network i.e. the user inputs for direction of the movement of the Robot are provided through the WiFi (with the help of a simple HTML Page).
iv 
 
ACKNOWLEDGMENTSIn case of the Bluetooth Controlled Robotic Arm and RF Controlled Robot, the robots wait for the user to provide appropriate input. This input can be either direction of movement or holding an object etc. In this project, we have built a simple Robot (robotic car) that can be controlled over WiFi Network i.e. the user inputs for direction of the movement of the Robot are provided through the WiFi (with the help of a simple HTML Page).   
4. PROPOSED WORK
The proposed system is implemented using ultra-sonic sensor, which detects the obstacles and changes its direction without the help of user (controller). The ultrasonic sensor can detect the obstacle at a range set by the controller, preferably 25cm.
An ultrasonic sensor is an instrument that measures the distance to an object using ultrasonic sound waves. An ultrasonic sensor uses a transducer to send and receive ultrasonic pulses that relay back information about an object's proximity.
 
The robot car also contains a sound recorder sensor to record the voices or sounds in the surroundings and the information is stored in a remote cloud. This voice Record Module is based on ISD1820, capable of multiple‐message record/playback. It can offers true single‐chip voice recording, no‐volatile storage, and playback capability of about 10 seconds.


FEATURES
•	Push‐button interface, playback can be edge or level activated
•	Auto power‐down mode
•	On‐chip 8Ω speaker driver
•	Power Supply – 3V – 5V
•	Can be controlled both manually 
•	Record up to 10 seconds of audio
•	Size: 38 x 42 mm
 
5. METHODOLOGY:
CONCEPT BEHIND WIFI CONTROLLED ROBOT
The ESP8266 Module is responsible for connecting to the WiFi Network and also acting as a server. As far as the client is concerned, a simple HTML page is created and the browser which opens this web page acts as a client is considered as the first try, else we have used an app as the interface between WiFi module and the client. We have used MIT app inventor to develop the app and to download it into a mobile phone of any operating system, preferably android.
Whenever you click on the web page, corresponding information will be transmitted to the Server (ESP8266) and this information is further received by Arduino and it controls the motors of the robot. The same applies to the app idea.
Circuit Diagram of WiFi Controlled Robot
The circuit diagram of the WiFi Controlled Robot using ESP8266 and Arduino is as follows:
 
NOTE: ESP8266 WiFi Module is loaded with AT Commands. The above circuit is designed as per the same.  
Components Required
•	ESP8266  
•	L298N Motor Driver Module
•	Arduino UNO  
•	Robot Chassis  
•	2 x 5V Geared Motors  
•	Connecting Wires
•	Voice record Monitor  
•	Power supply (or battery) 
 
Circuit Design
               Arduino is responsible for configuring the ESP8266 Module through Serial Communication and also controlling the L298n Motor Driver Module.
        The Digital Pins 2 and 3 of Arduino are configured as RX and TX using SoftwareSerial function. These pins are connected to the TX and RX pins of the ESP8266 Module.
Then, the Inputs of the L298n Motor Driver Module i.e. IN1, IN2, IN3 and IN4 are connected to Digital Pins 8, 9, 10 and 11 of Arduino UNO.
As far as the robot chassis is concerned, it has 2 geared motors. So, the right motor is connected in parallel and connected to OUT1 and OUT2 terminals of the Motor Driver. Similarly, the left two motor is connected to OUT3 and OUT4.




6. Code
There are two codes for the WiFi Controlled Robot project. One code is for the Arduino UNO and the other is an HTML Code for creating a Web Page.
•	This WiFi Controlled Robot is controlled with the help of an HTML Web Page (which can be accessed using any web browser on a computer that is connected to the same WiFi Network as ESP8266).
•	There are many projects out there which have implemented a similar concept but using Apps like MIT app developer.
•	The reason for which I have not gone with that App is that I felt that you really do not know what is going on actually as everything is done by the library files.
•	So, if you want to know exactly what is going on with the project, then only you should try this. If not, you can simply implement the project using the Blynk App.
•	If you go through both the codes carefully, you can understand how the communication happens between the Browser and the ESP Module.

7. Conclusion and Applications:
•	A simple WiFi Controlled Robot is implemented in this project where a robotic car is controlled using a web page over WiFi Network.
•	You can make this project with advanced features like integrating a camera and accessing the feed lie on the browser. 
•	Industrial applications- Industrial remote controls, alarm systems and wireless transmission for various types of low-rate digital signals, industrial data acquisition systems.
•	 Monitoring applications- The applications include environmental monitoring, biomedical applications, habitat monitoring, battlefield management, wireless fire protection systems.
•	Household applications: Alarm systems and wireless transmission for various types of low-rate digital signal, remote controls for various types of household appliances and electronics projects and several other applications related to RF wireless controlling. 
ADVANTAGES
•	 Offers productivity, convenience and cost 
•	Advantage over traditional wired technology.
•	No need for manual retrieval of data.
•	 Availability of real time data.

 LIMITATION
•	 The superior nature of this scheme depends on many environmental factors, such as operation scenarios, specific data types etc.
•	 More research work needs to be done in future to find the respective application scenarios for this scheme with all the related factors taken into consideration.
•	 This technique needs to be implemented in a wireless sensor network with mobile nodes, since mobility was not taken into account in this work.


 
 

                      8. REFERENCES:
[1] Namita Shinde, Shreya Srivastav, Vineet Sharma, Samarth Kumar, “Paper on android controlled arduino based robot car”. International Journal Of Industrial Electronics And Electrical Engineering.
[2] Bharat Kumar, Rashmi Avinash,  Sourav Sinha and K. Saravan kumar, “ Wifi controlled rover”. International Journal of Trend in Research And Development
[3] K.M. Merlin Ruby, F. Anne Jenefer, D. Vidya
[4] Maheshbabu P, Chandra Shekar
[5] Chirag Jain, ReemaKadechkar, Sachin Chaturvedi, Susmitha Pradhan, “Wireless controlled robot using aurduino and RF module”.International Journal of Technical Research and Application. March 2016.
[6]Muhammad Gulfam and Mirza Waleed Iftikhar Baig, “WG11 Android Based surveillance robot control system using socket programming with implementation” Internatonal journal of Multidisciplinary Science and Engineering, vol 6, no. 3, 2015.
[7] PrithvirajShetti et al, “On New Approach in Using433MHz Radio Modules ”International Journal of COMPUTER SCIENCE AND MOBILE COMPUTING, VOL.3, PP.3405-345, APRIL-2014
[8] Larry Mathies, Alonzo Kelly, “Obstacle Detection for Unmanned Ground Vehicles: A Progress Report,PP.475-
[9]MichaelMcRoberts”BeginningArduino”,USAISBN-13 (electronic): 978-1-4302-3241-4, pp.81-96.
[10] M. Daily et al. Autonomous cross-country navigation with the ALV. In Proc IEEE Int’ Conf on Robotics and Automation, pages 718- 726. IEEE Computer Society, April 1988.
[11] Rui Santos, “Guide for RF 433MHz Transmitter/Receiver Module With Arduino”
[12] BT Sudarshan, M Namratha, “Wi – Rover : A Wi-Fi Controlled Remotely Operated Video Enhanced Receiver”. International Journal of Computer Applications 56(7),2017.
[13] PrithvirajShetti et al, “On New Approach in Using 
433MHz Radio Modules ”International Journal of
COMPUTER SCIENCE AND MOBILE COMPUTING, 
VOL.3, PP.3405-345, APRIL-2014.
[14] Larry Mathies, Alonzo Kelly, “Obstacle Detection for 
Unmanned Ground Vehicles: A Progress Report,PP.475-
[15] MichaelMcRoberts”BeginningArduino”,USA
ISBN-13 (electronic): 978-1-4302-3241-4, pp.81-96.
[16] M. Daily et al. Autonomous cross-country navigation 
with the ALV. In Proc IEEE Int’ Conf on Robotics and 
Automation, pages 718- 726. IEEE Computer Society, April 
1988.
[17] Rui Santos, “Guide for RF 433MHz 
Transmitter/Receiver Module With Arduino

   

