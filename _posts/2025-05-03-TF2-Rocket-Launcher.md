---
title: "3D Modelling a Replica Weapon"
layout: post
post-image: "/assets/images/blogs/TF2RL.jpg"
description: Solidworks, Blender, and real life troubleshooting as I setoff to make a prop rocket launcher from the video game <em>Team Fortress Two.</em> I have ideas for electronics and some functionality, but that comes after the hurdles of construction.
tags:
- Embedded Systems
- CAD
---

The enamour and charm of Valve's Team Fortress Two is not lost on me. 700 hours of playtime deep with more interaction with the community through community run servers, youtube, and the like has left an impact on my life from the very beginning. A large portion of what I enjoy in the game is the extremely depth of combat and movement, which begins with the characters and weapons.

# Jane Doe's (aka Soldier) Rocket Launcher from TF2

<figure>
    <img src="/assets/images/blogs/RocketLauncherMay4.jpg"
         alt="TF2 Rocket Launcher"
         style="max-height: 80vh; width: auto;">
    <figcaption>Current Progress as of May 4th 2025. </figcaption>
</figure>

The project begins in the underbelly of the games assets. I set out to etract the originally weapon model to use as a reference when modelling. I could've easily used this model as the baseline for a 3d print, but I wished to gain experience in the modelling while also controlling the scale and measurements.
To get the model files, I used GCFScape which is used to open gcf and vpk files, the main files for most Steam developed games. Finding the model was relatively simple, crawling through the various data and config files, then I used a tool called Crowbar to unpack the model files into a usable form. The next step was taking the extracted model and making it compatible with solidworks, and to do this I imported the SMD file (or Signed Mark Data) into blender. This worked without a hitch, and I now had the rocket launcher in blender.

<figure>
    <img src="/assets/images/blogs/BlenderRL.jpg"
         alt="TF2 Rocket Launcher in Blender"
         style="max-height: 80vh; width: auto;">
    <figcaption>Current Progress as of May 4th 2025. </figcaption>
</figure>

SolidWorks cannot read the SMD file type, so exporting this model as an STL or OBJ was the next step. I chose OBJ as these retain more surface geometry data, but none of the other properties were relevant to me at the time. Importing the graphical model into SolidWorks was also simple, and soon enough I had a good graphical model in SolidWorks to begin my modelling.

<figure>
    <img src="/assets/images/blogs/SLRL1.jpg"
         alt="TF2 Rocket Launcher in SolidWorks"
         style="max-height: 80vh; width: auto;">
    <figcaption>Current Progress as of May 4th 2025. </figcaption>
</figure>

I decided to scale the model up so it wouldn't disappear in the sea of features. I also tried my best between these stages to get the proportions as life-like as possible for manufacturing later, while also keeping middle of the barrel centered around the origin. I was doing this to have a rotational extrude to do the body in one shot, which I didn't end up doing. This was still helpful as elements like the handles and various misc. parts were centered on the right and front plane which made making new planes and references very simple.

I've documented my progress across the days of the project in a googe slides presentation. I took screenshots for the day of modelling, and wrote comments about anything from the manufacturing, modelling difficulties, and others. Since the project is still in progress, I will append that journal later.
On a day to day, it consisted of modelling a part or multiple parts of the rocket launcher per day, with some days being dedicated to manufacturing processes and other post-printing procedures. The progress in the photo as of May 4th was the 11th day of the project.