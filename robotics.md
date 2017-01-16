ROBOTS AND MECHATRONICS 
=======================

Course Description
------------------

This course presents concepts, principles, and algorithms for sensing
and computation related to the physical world. Upon completion of this
course, students will have developed skills to design a small-scale
yet complex robot capable of real-time interaction with the natural
world.

<img src='https://rawgithub.com/walterbender/Syllabi/master/rodi.jpg'/><br>Copyright CC-By Martin Abente 2016

Instructor
----------

(TBD)

Course Objectives
-----------------

* Achieve a general understanding of robotics and their role in creative
  thinking;
* Learn how to use mechatronics in unconventional ways to solve
  challenging tasks;
* Develop team-working and communication skills;
* Develop critical-thinking and problem-solving skills.

Course Structure
----------------

This is a 6-week, project-based course. Students will work as a team
on a group project of their own chosing and engage in weekly
challenges. The weekly challenges are designed to introduce specific
skills that may be incorporated into the group project.

Grading
-------

* Participation (25%, valued through weekly attendance and team evaluation)
* Weekly Projects (25%, 5 projects at 5% each)
* Group Project (50%)

Materials
---------

RoDi (RedBot or Zumo 32u4 or an arduino-based platform), 1 per team
(Specific Robot TBD)
Journal
Laptop

Group Project
-------------

The goal of the group project is to incorporate robotics and
mechatronics into a project of personal interest and of relevance to
the local community. How can robotics help you address an authentic
problem? In formulating your proposed solution, use a decision matrix
to document the choices made that lead to your outcome.

Course Outline
---------------

1. [Programming a robot](#INTRODUCTION)
2. [Using a sensor](#SENSOR)
3. [Custom sensor](#CUSTOMSENSOR)
4. [Actuators](#ACTUATORS)
5. [Multiple robots](#MULTIROBOTS)
6. [Project review](#PROJECT)

Suggested Reading
-----------------

* P. Scherz and S. Monk, *Practical Electronics for Inventors*,
  McGraw-Hill (2013).
* T. Karvinen, K. Karvinen, V. Valtokari, *A Hands-On Primer for
  Monitoring the Real World with Arduino and Raspberry Pi*, Maker
  Media (2014).
* C T Palmer, *Machines and Mechanisms: A modern maker's guide to
  technologies as old as the wheel*, Maker Media (2016)
* K Ceceri, *Making Simple Robots: Exploring Cutting-Edge Robotics
  with Everyday Stuff*, Maker Media (2015).
* F. Martin, *Robotic Explorations: A Hands-On Introduction to
  Engineering*, Prentice-Hall (1980).
* http://rodibot.github.io/
* https://learn.sparkfun.com/tutorials/getting-started-with-the-redbot
* https://www.pololu.com/product/3124

<a name="INTRODUCTION">
1. PROGRAMMING ROBOTS
---------------------
</a>

Goal
----

The goal of this class is to master the basics of programming a
robot. Students will also form teams that will work on a group
project.

Equipment
---------

* Programmable robot with motors and a light sensor

Challenge
---------

Program a robot to follow a line using a light sensor.

Questions to Consider
---------------------

* Does the robot do the exact same thing every time it tries to
  accomplish the task?
* Is your solution robust to slight changes to the path?
* What changes would cause your solution to fail?
* Is it possible to follow a line without using any sensors?


<a name="SENSORS">
2. USING SENSORS
----------------
</a>

Goal
----

The goal of this class is to familiarize the student with a variety of
different sensor types, how to calibrate a sensor, and how to
incorporate a sensor into an interactive experience.

Group-project ideas will also be shared and critiqued.

Equipment
---------

* Programmable robot with motors and sensors

Challenge
---------

Program a robot to interact with a user in a responsive way, e.g.,
following the user, shying away from the user, mirroring the user,
etc.

Questions to Consider
---------------------

* Why factors determined your choice of sensor?
* Did the calibration drift over time?
* If so, how did detect and/or compensate for the drift?
* In building a responsive robot, do you think it is possible to
  emulate human affect?

<a name="CUSTOMSENSOR">
3. Custom sensors
-----------------
</a>

Goal
----

The goal of this class is to devel more deeply into sensor
design. Students will become familiar with the range of sensors
available, how to chose the appropriate sensor for the task at hand,
and how to incorporate the sensor into their project.

Equipment
---------

* Programmable robot
* A variety of sensors from which to choose.

Challenge
---------

Design an extension to your robot that allows it to measure the
distance it travels as it navigates a labyrinth.

Questions to Consider
---------------------

* Why did you choose the particular sensor(s) to solve this problem?
* What other problems could you have solved with the same set of tools?

<a name="ACTUATORS">
4. Actuators
------------
</a>

Goal
----

The goal of this class is to learn how to integrate an actuator to a
robot, transforming an input signal into some form of motion. Students
will familiarize themselves with different mechanical systems and the
use of control signals.

Equipment
---------

* Programmable robot with motors and a solenoid 

Challenge
---------

Add a retractable pen to the robot so that it can draw.

Questions to Consider
---------------------

* What are five different ways one could solve the stated challenge?
* What are the criteria for determining which solution to chose?
* What are the typical performance metrics for actuators?
* How would you decide between hydraulic, pneumatic, magnetic,
  thermal, electrical, or mechanical actuators in a real-world design?

<a name="MULTIROBOTS">
5. Multiple robots
------------------
</a>

Goal
----

The goal of this class is to explore the potential of multiple
interconnected robots.

Equipment
---------

* multiple Butia (or other network-enabled) robots

Challenge
---------

Teach the robots to dance, where one robot leads and the other robots follow.

Questions to Consider
---------------------

* Describe some applications where a collection of simple robots might
  be better able to solve a problem than one centralized solution.
* How should one make the trade-off between complexity and robustness?

<a name="PROJECT">
6. Project review
-----------------
</a>

Goal
----

Final project presentations

Questions to Consider
---------------------

* To what extent do sensors and actuators play a role in the project?
* How does the project benefit from interaction with the physical world?
* Are the results replicable? scalable? manufacturable?

