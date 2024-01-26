---
layout: single
title: "Large Gantry"
author: Christopher Rosend
author_profile: true
related: true
classes: wide
header: 
    image: /assets/images/ldpe-recycling/dreams-banner.png
    teaser: /assets/images/large-gantry/large-gantry.jpg
show_date: true 

gallery:
  - url: /assets/images/large-gantry/cable-management.jpg
    image_path: /assets/images/large-gantry/cable-management.jpg
    alt: "Cables"
    title: "Attempting to manage the cables ontop of a 10 foot printer, a bit of a nightmare"

  - url: /assets/images/large-gantry/cooling-system.jpg
    image_path: /assets/images/large-gantry/cooling-system.jpg
    alt: "Cooling issues"
    title: "The cooling system that start to have issues"

  - url: /assets/images/large-gantry/endstops.jpg
    image_path: /assets/images/large-gantry/endstops.jpg
    alt: "Endstops"
    title: "Endstops that were designed and printed by us"

  - url: /assets/images/large-gantry/pellet-feed.jpg
    image_path: /assets/images/large-gantry/pellet-feed.jpg
    alt: "Pellet feed"
    title: "Preliminary testing on the pellet feed system, working on getting them up 10 feet to the top with a vaccuum"

  - url: /assets/images/large-gantry/troubleshooting-movement.jpg
    image_path: /assets/images/large-gantry/troubleshooting-movement.jpg
    alt: "Movement troubleshooting"
    title: "Moving the printer head around using basic G-code commands"

  - url: /assets/images/large-gantry/duet-working.jpg
    image_path: /assets/images/large-gantry/duet-working.jpg
    alt: "Duet testing"
    title: "The first step in making the gantry, getting the motors to connect to the motor controllers"

---
## What is it?

This was what I would consider to be my first official engineering experience. The project was started by a graduate student named Daniel who was working for a company that needed to print large polypropylene objects. Dr. Williams, the head of the DREAMS Lab which is a lab specializing in research on additive manufacturing, tasked me and two others onto the project of constructing a large gantry to print polypropylene. The body was already built so we mainly had to figure out how to wire the electronics and set up the feed system.

## What have I done?

Because this was one of my first foray into actual engineering work, a lot of my work involved the design of systems and learning the more complicated stuff from my team members who have already had experience in the field. I worked on three things, the design of the pellet feed system, the implementation of the cooling system, and the implementation of the endstop, all of which can be seen in the pictures below.
The endstops were the first thing worked on since we wanted to get the gantry moving, so they were designed to easily slot into the aluminum bars and also be easily movable so we can quickly correct any mistakes. There were 6 total, 4 for the y-axis and 2 for the x-axis. They were designed in Solidworks and 3D printed to allow for an easy fit for the endstop.
The cooling system was next which had a bit of a factory issue. After installing it into the machine and routing the wires, I discovered that the liquid wasn’t flowing unlike other cooling systems of the same brand in the lab. After learning how to use a multimeter I discovered that one of the sensors was not functioning properly, and a different type of cooler had to be used.
Lastly is the pellet feed system. Since the gantry is 10 feet tall, the pellet feed system was designed to use a vacuum to pull pellets up through a tube into the extruder. Keeping the pellet loading near the bottom allows for easier loading and reduces the risk of accidents while loading.
Figuring out how the duet works
Early tests of the pellet feed system
Nightmare cable management
Issues with the cooling system
Troubleshooting the movement of the arm
Design of the endstops

{% include gallery caption="Different parts of the process." %}

## What have I learned from this?

<ins>Experience</ins>

* Familiarity with the Duet 3D motor controllers
* Ability to test if components are working using techniques and tools
* General troubleshooting experience

<ins>Concepts</ins>
* Ask many many questions for things you don’t understand, there is no other way to learn
* You have to rely on people who know the things you don’t
