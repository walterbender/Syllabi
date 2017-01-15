MUSIC, MIND, AND MACHINE
========================

Based on a course once offered by digital music pioneer Barry Vercoe,
this course covers the technical aspects of digital music for use in
practical applications. Topics include the software libraries for the
production of music and their use in applications and
instrumentation. Students will become acquainted with digital music
while engaged in designing their own instruments, utilizing software
and sensor technology.

<img
src='https://rawgithub.com/walterbender/musicblocks/master/screenshots/Screenshot-1.png'</img>

Instructor
----------

Walter Bender (walter@miamicollegeofdesign.com)

Objective
---------

The objective of this course is to give students sufficient
scaffolding in the physics of sound, acoustics, psychoacoustics, music
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

There will be two weekly meetings: (1) a discussion and experiment;
and (2) a recitation for in-depth review of the material. Generally
each class will begin with discussion of research other people have
done on the same topic as last week's exploration topic. This
discussion may include visits by some of the researchers or by authors
who have written on the subject. The intent is to encourage students
to explore a subject before reading about it. This approach tends to
avoid biasing interpretations of what might be going on and provides
students with their own base of experience to which they can relate
when reading research on the topic of interest. The second class
activity will be an exploration of this week's class goal.

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
6. [Project reviews](#PROJECTS)

Grading
-------
50% of your grade is based on class participation in the experiential
exploration of questions pointing to critical challenges.

25% of your grade will be for a project that might add insight to an
effective color model with stated objectives. The intent is to offer
you the opportunity to pursue something personally meaningful.

25% of your grade is dependent upon weekly problems.

Suggested Reading
-----------------

* Mazzola, G., Mannone, M., Pang, Y., O'Brien, M., Torunsky, N., *All About Music: The Complete Ontology: Realities, Semiotics, Communication, and Embodiment*, Springer (2016)
* V. Lazzarini, S. Yi, J. ffitch, J. Heintz, Ø. Brandtsegg,
  I. McCurdy, *Csound: A Sound and Music Computing System*, Springer,
  (2016).
* R. Boulanger (editor), *The Csound Book*, MIT Press (2000).

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
incuding all major operating systems as well as Android and iOS.

(from http://csound.github.io)

Goal
----

The goal of this class is to introduce students to concepts such as
unit generators, instrument models, compilers, etc. These concepts are
at the core of music programming systems. The Csound library, which is
the most technically and muscially advanced language for programming
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

* D. Deutsch, Music Perception, *Frontiers of Bioscience* (2007)
* A. Trafton, "How the brain perceives rhythm", MIT Brain and Cognitive Sciences (2017) [https://bcs.mit.edu/news-events/news/how-brain-perceives-rhythm]
* M. Gonick, "Are musical tastes cultural or hardwired in the brain?  MIT Brain and Cognitive Sciences (2016) [https://bcs.mit.edu/news-events/media/are-musical-tastes-cultural-or-hardwired-brain]
* A. Trafton, "Why we like music", MIT Brain and Cognitive Sciences (2015) [https://bcs.mit.edu/news-events/news/why-we-music-we-do]
* A. Trafton, "Music in the brain", MIT Brain and Cognitive Sciences (2015) [https://bcs.mit.edu/news-events/news/music-brain]
* 

<a name="INSTRUMENTATION">
5. INSTRUMENTATION
------------------
</a>

Goal
----

The goal of this class is to explore the variety of electro-mechanical
mechanisms available to directly create sound, e.g., a theramin, or to
interface to a digital synthesizer. Students will explore interactive
models of voice and instruments in realtime musical performance.

Questions to Consider
---------------------

* How does your choice of instrumentation impact the expressive
  quality of your music?
* How does your instrumentation differ from traditional analog solutions?

Suggested Reading
-----------------

<a name="PROJECTS">
6. FINAL PROJECT REVIEWS
------------------------
</a>

*Imagine and realize* &mdash;J. Maeda<br>*Critique and reflect* &mdash;W. Bender

Questions to Consider
---------------------

* How has music been used to enhance (or degrade) the experience?
* Is the solution targeted to a specific audience or is it universal?
* How do you know?
* What is the cost/benefit of adding music to your project?
