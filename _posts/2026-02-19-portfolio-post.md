---
layout: post
author: Gael Barranco
tags: [overview, moonwalk]
---


## Princess Bubblegum:
Dec 2025-Present
![PB Pic 1](/images/PB_Images.png)
Why must precision robots be so expensive? I built a 4 DOF robot arm from scratch using
Facebook Marketplace and a 3D printer, driven by NEMA 23 stepper motors through a
custom 16:1 two-stage planetary gearbox. In the initial testing, cantilever effects were
devastating, so I created my own custom bearings throughout the entire design.
Additionally, I initially used automotive grease for lubricant which posed both carcinogenic
effects and foul smells, so I decided on Vaseline as a safer, much more pleasant-smelling
alternative. For controls, I audited a Canadian surgical robotics course on the internet,
resulting in a completed forward kinematics script with transformation matrices, enabling
real time end effector positioning that is visualized in a 3D environment. More work is being
done to allow for inverse kinematics. 



## RoboJackets: RoboNav ARM Project:
Feb 2026 – Present
![RBN Pic 1](/images/Cycloid.png)
Contributing to the Mars Rover Competition on arm dynamics and gearbox design.
Developed a parametric Excel tool that takes design constraints — gear ratio, pin count,
and radii — and outputs an optimized cycloidal gearbox geometry, including basic analysis
of stress concentrations on the tooth profile under load. Currently running FEA on the
cycloidal drive to validate and optimize it for manufacturing, while also modeling arm
linkage dynamics to inform motor and structural specs.


## 3D Printed Metal Heat Exchangers:
Dec 2023 – Dec 2025
![PB Pic 1](/images/Poster.png)
Conducted undergraduate research with Dr. Philip Barnett developing 3D printed metal
structures for engineering applications. Optimized direct ink write processes for steel and
copper to produce highly porous, high surface area geometries that are difficult to achieve
with traditional manufacturing. Applied these structures to thermal energy storage systems,
combining the heat transfer properties of printed metals with the latent heat of various
waxes to create a cell that stabilizes temperatures during transient thermal cycles.
Presented work at the SHPE national convention in Fall 2025.


## Wearable I:
Sept 2024 – Nov 2024:
![Wearable Pic 1](/images/Wearable_I.png)
The fear of losing mobility in a limb is a scary reality that many people today face. The issue
I sought to address is: how can I regain some level of mobility with the budget of a broke
college student? I designed and built a low-cost wearable exoskeleton to restore elbow
mobility, driven by the movement of the unaffected arm. The mechanical system uses a
planetary gearbox at the shoulder driving a belt connected to the elbow, enabling flexion
and contraction of the assisted limb. Mirrored movement is captured with encoders on the
sister limb and processed by an ESP32 programmed in C++. I was successful in
constructing the wearable robot, even allowing me to add 4 kg to my max curl.

[YouTube short link of the initial test footage I have of it](https://youtube.com/shorts/JZPm1b3LvI0?si=5PBZBgxcaps_Vgw8)


## Farm World Finn’s Arm:
Jan 2023 – May 2023:
![FWF Pic 1](/images/FWF_Images.png)
Took on my first engineering project by building a working robot arm that responds to visual
hand movement. Designed full CAD assembly from scratch in Onshape, taking heavy
inspiration from the cartoon Adventure Time. I chose Arduino as the microcontroller
because of its extensive documentation and Pyfirmata library that allowed me to use Python
for everything. Leveraged OpenCV’s hand detection capabilities and turned my screen into
a coordinate system, feeding positional data to the servos to control movement. I was
successful in creating a fully 3D printed, working robot arm. However, its movement was not
very fluid, precise, or stable enough to hold any meaningful load.

[YouTube short link of it (kind of) working](https://youtube.com/shorts/oGQ8MJBtodc?si=Vr8nW1csyBtgdB8V)

---
{: data-content="footnotes"}

[^1]: this is a footnote. You should reach here if you click on the corresponding superscript number.
[^2]: hey there, don't forget to read all the footnotes!
[^3]: this is another footnote.
[^4]: this is a very very long footnote to test if a very very long footnote brings some problems or not; hope that there are no problems but you know sometimes problems arise from nowhere.
