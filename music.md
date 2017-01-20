MUSIC, MIND, AND MACHINE
========================

Based on a course once offered by digital-music pioneer Barry Vercoe,
this course covers the technical aspects of digital music for use in
practical applications. Topics include the software libraries for the
production of music and their use in applications and
instrumentation. Students will become acquainted with digital music
while engaged in designing their own instruments, utilizing software
and sensor technology.

<img
src='https://rawgithub.com/walterbender/musicblocks/master/screenshots/Screenshot-1.png'</img>

Instructors
-----------

Walter Bender (walter@miamicollegeofdesign.com)<br>
Design Faculty

Objective
---------

The objective of this course is to give students sufficient
scaffolding in the physics of sound, acoustics, psycho-acoustics, music
theory, and analog and digital audio processing such that they can
credibly and deliberately incorporate music into the designs.

Approach
--------

To aid students in their pursuit, the course consists of hands on
exploration of questions that point to the critical scientific and
technological challenges of sound and music and hands on attempt to
pursue personal exploration of a theory and model for music as a tool
for communication.

Course Organization
-------------------

The course is broken into two phases: liquid (innovation) and solid
(consolidation).

Throughout the both phases of the course, students will be working on
a project of their own choosing. The intent is to offer students the
opportunity to pursue something personally meaningful.

During the *liquid* phase, Weeks 1 through 6, there will be two weekly
meetings: (1) a discussion and experiment; and (2) a recitation for
in-depth review of the material. Each week, different tools relevant
to music will be presented and a discussion will ensue.

During the *solid* phase, Weeks 8 through 15, there will be
twice-weekly meetings with the design faculty to move through a design
pipeline, taking the ideas developed in the *liquid* phase into a
design recommendation for production.

Requirements
------------

Weekly programming assignments and reading, as well as an individual
or group term project. Classes will consist of a weekly group
experiment, brief lecture, and discussion. There will be occasional
guest lectures by leading digital music researchers.

Course Outline
--------------

1. [Music Blocks](#MUSICBLOCKS)
2. [CSound](#CSOUND)
3. [Physics of Sound](#PHYSICS)
4. [Mind and Music](#MINDMUSIC)
5. [Music Instrumentation](#INSTRUMENTATION)
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
incorporating music into a product.

20% of your grade will be based on the project presentation at the end
of the *liquid* phase of the course.

50% of your grade will be for your project work during the *solid*
phase of the course.

Suggested Reading
-----------------

* Mazzola, G., Mannone, M., Pang, Y., O'Brien, M., Torunsky, N., *All About Music: The Complete Ontology: Realities, Semiotics, Communication, and Embodiment*, Springer (2016)
* V. Lazzarini, S. Yi, J. ffitch, J. Heintz, Ø. Brandtsegg,
  I. McCurdy, *Csound: A Sound and Music Computing System*, Springer,
  (2016).
* R. Boulanger (editor), *The Csound Book*, MIT Press (2000).
* T. Tunstall, *Changing Lives: Gustavo Dudamel, El Sistema, and the Transformative Power of Music*, Norton (2013).
* D. Hosken, *An Introduction to Music Technology*, Routledge (2014).
* C. D. Shelton, *Music and the Brain: How Music Changes the Brain*, Choice (2013).
* C. Harding, *How We Listen Now: Essays and Conversations About Music and Technology*, Create Space (2015).

<a name="MUSICBLOCKS">
1. MUSIC BLOCKS
---------------
</a>

Music Blocks is a collection of manipulative tools for exploring
fundamental musical concepts in an integrative and fun way.

Goal
----

The goal of this class is to provide an introduction to music
programming and to provide a common vocabulary for composing and
listening to music.

Experiment
----------

Use Music Blocks to establish a musical expectation and then violate
that expectation.

Questions to Consider
---------------------

* How do you set an expectation with music?
* Is the expectation universal?
* How do you violate an expectation with music?
* How can you apply this technique to design?

Suggested Reading
-----------------

* *The Music Blocks Guide*,
   http://walterbender.github.io/musicblocks/guide/README.md
* tone.js, https://github.com/Tonejs/Tone.js/
* *Lilypond Notation Manual*,
   http://lilypond.org/doc/v2.18/Documentation/notation.pdf

<a name="CSOUND">
2. CSOUND
---------
</a>

Csound is a sound and music computing system that was originally
developed by Barry Vercoe in 1985 at MIT Media Lab.

Csound has a strong tradition as a tool for composing
electro-acoustic pieces; it is also used by composers and musicians for any
kind of music that can be made with the help of the computer.

Csound has been used in both non-interactive score-driven contexts and
a real-time contexts. Csound can run on a host of different platforms
including all major operating systems as well as Android and iOS.

(from http://csound.github.io)

Goal
----

The goal of this class is to introduce students to concepts such as
unit generators, instrument models, compilers, etc. These concepts are
at the core of music programming systems. The Csound library, which is
the most technically and musically advanced language for programming
music is used as the medium for studying these concepts.

Experiment
----------

Build a real-time interactive performance application using Csound.

Questions to Consider
---------------------

* How do digital instrument models differ from their analog equivalents?
* What are the constraints on real-time interactive music generation?

Suggested Reading
-----------------

* *The Canonical Csound Reference Manual*, http://csound.github.io/docs/manual/index.html

<a name="PHYSICS">
3. THE PHYSICS OF SOUND
-----------------------
</a>

Goal
----

Sound is produced from vibrations in air that we can hear. The goal of
this class is to explore different physical sources of vibrations and
how they impact audio perception. We will explore pitch perception as
it relates to frequency, amplitude as it relates to sound intensity,
and the limits of the human ear. We will also explore different
mechanisms for creating resonance and standing waves as they relate to
music and musical instruments.

Experiment
----------

Build a flute and a two-string acoustic resonator.

Questions to Consider
---------------------

* How does the position of the holes impact the tuning of the flute?
* How does the shape of the barrel impact the sound of the flute?
* How does the shape of the resonator impact the quality of the sound?
* How can the two strings be tuned differently?

Suggested Reading
-----------------

* http://physics.info/sound/
* http://www.phy.mtu.edu/~suits/Physicsofmusic.html
* http://www.indiana.edu/~emusic/etext/acoustics/chapter1_intro.shtml

<a name="MINDMUSIC">
4. MIND AND MUSIC
-----------------
</a>

Goal
----

The goal of this class is to explore the relationship between
acoustics and perception. Students will build upon their understanding
of the physics of sound in order to begin to understand how the
perception of sound can be interpreted as music in the mind.  They
will explore the pathways from detection of frequency, intensity, and
spectrum, to the development of their perceptual correlates as pitch,
loudness and timbre.

Experiment
----------

Using Music Blocks, generate a series of rhythms, with integral and
non-integral proportions. Using the techniques developed by Jacoby
(described by Trafton), measure the biases for musical rhythm of your
classmates.

Questions to Consider
---------------------

* What is a prior and how do priors impact our perception of music?
* What is the relationship between the physical reality of music and
  its semiotics, i.e., its expressive character?

Suggested Reading
-----------------

* S. Vercoe, *Moodtrack: practical methods for assembling emotion-driven music*, MS Thesis, MIT Media Lab (2006) [http://pubs.media.mit.edu/pubs/papers/scottyv-ms.pdf]
* D. Deutsch, Music Perception, *Frontiers of Bioscience* (2007)
* A. Trafton, "How the brain perceives rhythm", *MIT Brain and Cognitive Sciences News* (2017) [https://bcs.mit.edu/news-events/news/how-brain-perceives-rhythm]
* M. Gonick, "Are musical tastes cultural or hardwired in the brain?, *MIT Brain and Cognitive Sciences News* (2016) [https://bcs.mit.edu/news-events/media/are-musical-tastes-cultural-or-hardwired-brain]
* A. Trafton, "Why we like music", *MIT Brain and Cognitive Sciences New* (2015) [https://bcs.mit.edu/news-events/news/why-we-music-we-do]
* A. Trafton, "Music in the brain", *MIT Brain and Cognitive Sciences News* (2015) [https://bcs.mit.edu/news-events/news/music-brain]

<a name="INSTRUMENTATION">
5. INSTRUMENTATION
------------------
</a>

Goal
----

The goal of this class is to explore the variety of electro-mechanical
mechanisms available to directly create sound, e.g., a theramin, or to
interface to a digital synthesizer. Students will explore interactive
models of voice and instruments in real-time musical performance.

Questions to Consider
---------------------

* How does your choice of instrumentation impact the expressive
  quality of your music?
* How does your instrumentation differ from traditional analog solutions?

Suggested Reading
-----------------

* J. Paradiso, E. Hu, "Electronic Music Interfaces: New Ways to Play", *IEEE Spectrum* (1997) [https://dam-prod.media.mit.edu/x/files/pubs/papers/97-12-SpectrumScan-BW.pdf]

<a name="PROJECTS">
6. LIQUID-PHASE PROJECT REVIEWS
------------------------
</a>

*Imagine and realize* &mdash;J. Maeda<br>*Critique and reflect* &mdash;W. Bender

Questions to Consider
---------------------

* How has music been used to enhance (or degrade) the experience?
* Is the solution targeted to a specific audience or is it universal?
* How do you know?
* What is the cost/benefit of adding music to your project?

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
