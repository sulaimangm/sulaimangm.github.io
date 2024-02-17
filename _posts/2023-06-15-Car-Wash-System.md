---
layout: post
title: Automated Car Wash System
thumbnail-img: /assets/img/project_images/Car_Wash_System_Thumbnail.png
tags: [Python, Internet of Things, Blynk]
---

<h4>Summary</h4>
This project presents the working of an automated car wash system that uses sensors, actuators, and a cloud (Blynk) platform. The integration of these components enables real-time monitoring, precise control, and efficient operation of the car washing and drying process. By utilizing sensor data and actuator control, the system optimizes the cleaning procedure for different vehicle types. The cloud platform shows real-time statuses of the entire process. This paper also discusses the design, implementation, and applications of this system. Results demonstrate the system's ability to streamline the car wash process and deliver consistent results. The findings will contribute to the field of automated car wash systems and provide insights for further advancements in smart car wash technology using deep learning technologies.

<h4>Overview</h4>
* This project is a prototype of an Automated Car Wash System.
* Initially, a camera sensor detects a vehicle following which a barricade opens.
* The LED turns Green, allowing the vehicle to enter the wash area.
* In the wash area, an ultrasonic sensor aids the vehicle to position itself accurately.
* Once positioned accurately, the washing begins followed by drying.
* When both the processes complete, an exit barricade opens up for the vehicle to exit.
* Current status of the entire process is transmitted to the cloud.

![Diagram](/assets/img/project_images/Car_Wash_System_Diagram.png)

<h4>Components</h4>

<table>
    <tr>
        <td>Raspberry Pi 4</td>
        <td>Water Pump</td>
        <td>LED</td>
    </tr>
    <tr>
        <td>Camera Module</td>
        <td>Ultrasonic Sensor</td>
        <td>Relay</td>
    </tr>
    <tr>
        <td>Servo Motor</td>
        <td>LCD</td>
        <td>Power Module</td>
    </tr>
</table>

<h4>Blynk</h4>

<div style="display: flex; align-items: center;">
    <p>This project uses the Blynk cloud platform. Blynk is an IoT platform for iOS or Android smartphones that is used to control Arduino, Raspberry Pi and NodeMCU via the Internet. This application is used to create a graphical interface or human machine interface (HMI) by compiling and providing the appropriate address on the available widgets. Both the Web and Mobile User Interface is used to send information about the stats of the car wash process to the user in real time.</p>
    <img src="/assets/img/project_images/Car_Wash_System_Blynk.png" alt="Blynk">
</div>

<h4>Working</h4>

<iframe width="560" height="315" src="/assets/img/project_images/Car_Wash_System_Video.png" frameborder="0" allowfullscreen></iframe>

With this prototype, we explored an existing version of the Automated Car Wash System using the fundamentals of Electronics, IOT and Deep Learning. Various industries have implemented systems that further automate and dynamically control specific phases in the process such as washing and drying. Our system, having immense upgrade potential and numerous real-world use-cases, can improve businesses of organizations and contribute effectively to this rapidly growing technological world.
