# A Unified Framework for Rigid Body Dynamics 
by Helmut Garstenauer

In 2005 I finished my master thesis about rigid body dynamics. It shows how to build a rigid body physics engine for interactive 3d applications. I am sure it is a good starting point for everyone who wants to learn about game physics. If you have any questions, you can contact me via email:  rigid-body-thesis (AT) outlook (DOT) com (AT)

* [Goals of this Thesis](#goals-of-this-thesis)
* [From the Content](#from-the-content)
* [Download](#download)
* [Videos](#videos)
* [Further Reading](#further-reading)

## Goals of this Thesis

I wrote this thesis because I wanted to write a physics engines and felt that several things were missing. At first, there was no textbook which explained all the relevant fundamentals of physics and mechanics. Computer scientists who want to write rigid body simulations have to gather the information from many different sources.

**⇒ Goal 1: Create a textbook that contains all fundamentals that are required to create a physics engine.**

After I had mastered the basics, I still felt alone: No one had taught me how the different parts fit together. Parts like numerical integration, force computations, collision detection, constraint solving, etc.

**⇒ Goal 2: Show how the pieces fit together.**

Solving constraints, like non-penetration constraints and joints, is the exciting and difficult part of a rigid body simulation. Several methods exist: Penalty methods, LCP-based methods, impulse-based methods, etc. For non-experts some of these methods are hard to understand and difficult to compare. Especially, since papers use different vocabulary and notations.

**⇒ Goal 3: Give an overview of the existing simulation methods.**

Many existing physics engines have design weaknesses: The API is difficult to use. The library is hard to extend. Or the framework is focused on a single simulation method.
So I wanted to suggest a design for a framework which is easy to use, extendable and object-oriented. The simulation method should be exchangeable so that different simulation methods can be tested, compared and combined.

**⇒ Goal 4: Create a design for a unified framework for rigid body dynamics.**

## From the Content

* Basics: Rotations, Particles, Rigid Bodies, Forces, The Linear Complementarity Problem
* Simulation Overview: Numerical Integration, Collision Detection, Time step methods, Sleeping
* Constraint Solver & Error Correction: Constraints, Joints, Force-Based Methods, Impulse-Based Methods, Position-Based (Projection) Methods
* Design of a Unified Framework
* Examples
* Download

## Download 
[A Unified Framework for Rigid Body Dynamics (.pdf, 3.5MB)](https://github.com/Helikin/Physics-Engine-Thesis/blob/master/A%20Unified%20Framework%20for%20Rigid%20Body%20Dynamics.pdf)

## Videos

Three videos that were created with the rigid body dynamics library described in the thesis.

[![Ragdoll animated with rigid body dynamics](https://img.youtube.com/vi/yj6ltwZukY8/0.jpg)](https://www.youtube.com/watch?v=yj6ltwZukY8)

[![A Ragdoll on Stairs ](https://img.youtube.com/vi/yK5PMYNX2HY/0.jpg)](https://www.youtube.com/watch?v=yK5PMYNX2HY)

[![An assembling logo animated with rigid body dynamics](https://img.youtube.com/vi/Bf_5-QxS45Y/0.jpg)](https://www.youtube.com/watch?v=Bf_5-QxS45Y)

## Further Reading

* DigitalRune Physics library in the [DigitalRune Engine](https://github.com/DigitalRune/DigitalRune) - 
This is my newer physics engine, created with Martin Garstenauer.

* GDC presentations by Erin Catto (highly recommended) - 
Make sure to learn about _Sequential Impulses_. This method is newer than my thesis, and it is also used in DigitalRune Physics.


