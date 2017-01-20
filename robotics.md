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

(TBD)<br>
Design Faculty

Course Objectives
-----------------

* Achieve a general understanding of robotics and their role in creative
  thinking;
* Learn how to use mechatronics in unconventional ways to solve
  challenging tasks;
* Develop team-working and communication skills;
* Develop critical-thinking and problem-solving skills.

Course Organization
-------------------

The course is broken into two phases: liquid (innovation) and solid
(consolidation).

Throughout the both phases of the course, students will be working on
a robots project of their own choosing. The goal of the project is to
incorporate robotics and mechatronics into a project of personal
interest and of relevance to the local community. How can robotics
help you address an authentic problem? The intent is to offer
students the opportunity to pursue something personally meaningful.

During the *liquid* phase, Weeks 1 through 6, there will be two weekly
meetings: (1) a discussion and experiment; and (2) a recitation for
in-depth review of the material. Each week, different tools relevant
to color will be presented and a discussion will ensue.

During the *solid* phase, Weeks 8 through 15, there will be
twice-weekly meetings with the design faculty to move through a design
pipeline, taking the ideas developed in the *liquid* phase into a
design recommendation for production.

Materials
---------

* RoDi (RedBot or Zumo 32u4 or an Arduino-based platform), 1 per team
  (Specific Robot TBD)
* Journal
* Laptop

Course Outline
---------------

1. [Programming a robot](#INTRODUCTION)
2. [Using a sensor](#SENSOR)
3. [Custom sensor](#CUSTOMSENSOR)
4. [Actuators](#ACTUATORS)
5. [Multiple robots](#MULTIROBOTS)
6. [Liquid-phase project reviews](#PROJECTS)
7. [Solid-phase problem definition](#DEFINITION)
8. [Discovery](#DISCOVERY)
9. [Consolidation](#CONSOLIDATION)
10. [Technical feasibility study](#FEASIBILITY)
11. [Prototyping](#PROTOTYPING)
12. [Candidate selection](#CANDIDATES)
13. [Finalization of design](#FINALIZATION)
14. [Recommendations for production](#PRODUCTION)
15. [Solid-phase project reviews](#REVIEW)

Grading
-------

30% of your grade is based on class participation in the experiential
exploration of questions pointing to critical challenges for
incorporating robotics into a product.

20% of your grade will be based on the project presentation at the end
of the *liquid* phase of the course.

50% of your grade will be for your project work during the *solid*
phase of the course.

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
  Engineering*, Prentice-Hall (2000).
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

The goal of this class is to delve more deeply into sensor
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
6. LIQUID-PHASE PROJECT REVIEWS
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

<a name="DEFINITION">
7. SOLID-PHASE PROBLEM DEFINITION
---------------------------------
</a>

"Almost anybody can have an idea... Getting things actually done is
where people stumble." &mdash;Linus Torvalds

Goal
----

Problem definition, typically a synthesis of an interim output of the
liquid phase with a real-world problem.

Questions to Consider
---------------------

* What is the meaning or purpose of the problem you are trying to solve?
* Is it a real-world problem?
* What makes your design worth pursuing?
* Have you compared your design with existing ideas?

Suggested Reading
-----------------

* D. Norman, *The Design of Everyday Things*, Basic Books (2013).

<a name="DISCOVERY">
8. DISCOVERY
------------
</a>

Goal
----

Discovery of underlying natural phenomena and principles, i.e., input
from the natural world: materials, processes, and functions that can
influence and direct the design choices.

Questions to Consider
---------------------

* Are there any mechanisms in nature that can serve as analogs for
  your design?

Suggested Reading
-----------------

* j. Bernsen *Bionics in Action: The Design Work of Franco Lodato*,
  StoryWorks DK (2004).
* F Wilczek, *A Beautiful Question: Finding Nature's Deep Design*,
  Penguin (2015).

<a name="CONSOLIDATION">
9. CONSOLIDATION
----------------
</a>

Goal
----

Consolidation of the concepts through a process of sketches,
layout, functional and material design, and cost analysis; When
iterating in this step, these parameters are purposefully exaggerated
to identify potential opportunities and risks and liabilities.

Questions to Consider
---------------------

* What are the technical considerations to realize your idea?
* What is the environmental impact of your design?

<a name="FEASIBILITY">
10. STUDY OF TECHNICAL FEASIBILITY
----------------------------------
</a>

Goal
----

Study of technical feasibility and product relevance, which may result
in our revisiting the problem definition determined in Session 8
[Discovery](#DISCOVERY).

Questions to Consider
---------------------

* Is your design manufacturable?
* Is your design cost-effective?
* What is the energy footprint of your design?
* Is your design sustainable?
* What is the material life-cycle of your design?

<a name="PROTOTYPING">
11. PROTOTYPING
---------------
</a>

Goal
----

Developing prototypes that can be tested in the lab and/or field.

Questions to Consider
---------------------

* What observations have you made about your prototype while in "action"?
* Did your "users" make any suggestions about the design?
* Did your "users" make any suggestions about alternative uses for your design?

<a name="CANDIDATES">
12. SELECTION OF CANDIDATE DESIGNS
----------------------------------
</a>

Goal
----

Selection of (three) candidate designs.

Questions to Consider
---------------------

* What are the projected lifetime of use and utility of the candidate designs?
* Are they all equally easy to maintain?
* Can they be repaired? By whom?
* Can they be reused or repurposed?
* Are there environmental constraints on their operation?
* Are they all suitable and safe for young children?

<a name="FINALIZATION">
13. FINALIZATION OF DESIGN
--------------------------
</a>

Goal
----

Finalization of a design for manufacturing.

Questions to Consider
---------------------

* What constraints does manufacturing put on your design?
* What compromises must you make in light of these constraints?
* Are there established design/manufacturing practices to which you can adhere?

<a name="PRODUCTION">
14. RECOMMENDATIONS FOR PRODUCTION
----------------------------------
</a>

Goal
----

Making design recommendations to production.

Questions to Consider
---------------------

* Does your design establish clear metrics by which you can measure
  the quality of production?

<a name="REVIEW">
15. SOLID-PHASE PROJECT REVIEWS
-------------------------------
</a>

Goal
----

* Final project presentation and critique.
* Course review and critique.

Questions to Consider
---------------------

* Is your project ready for manufacturing?
* What are the next steps for your project?
* After 15 weeks of iteration, revision, and compromise, is music
  still in its essence?
* How has your initial vision of your project changed?

<p align="center">
<img src="https://rawgithub.com/walterbender/Syllabi/master/mcod-jc-small.png"/>
</p>
