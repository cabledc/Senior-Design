**Individual Capstone Assessment**

**Destry Cable**

  For my capstone project, I wanted to mainly focus on applying software to control hardware. The second area of focus is around green energy. 
To deliver on these two areas of focus I decided on solar power and how to maximize it with software. My plan is to create a small solar device that can orient itself for maximum electricity output. 
It would consist of a solar panel, two motors for tilt and rotation, an arduino as the computer, a battery to store power for the components, and an electricity meter. 
The arduino code would utilize a proportional–integral–derivative controller or PID to control the movement for both of the motors, using input from the electricity meter.

  PIDs are very useful for outputting a smooth control, as adjusting the motors would likely be jittery/jumpy without one. 
The concepts of PIDs can be applied from Calculus 1 and 2. I have used a PID in arduino code to control a robot solving a maze in my sophomore year. 
I recall the class was ENED1120. It was effective for keeping the robot from over/under correcting its movement. I quite enjoyed this project in this class and wanted to do something similar with using hardware/robotics for my senior project.

  My Co-op experiences consisted of working for Honeywell Intelligrated as an VR/AR (virtual and augmented reality) software engineer. At this co-op I did VR work for training software. 
This software is used to train employees how to operate conveyor and logistical sorting systems. I also worked on simulation software that can take autocad files of conveyor systems and convert them into a working warehouse simulation. 
Simulating, sorting systems, movement of boxes, etc. All of this work was mainly software focused, and did not apply directly to robotics/hardware, but it did simulate it.

  This ties into my senior project motivation. As my co-op was all software engineering. I want to challenge myself and try working more with hardware, since it’s something I haven’t had another opportunity to do. 
I gained experience working with software such as Autocad, blender, Unity 3D at my co-op which I will use for 3D printing parts. I haven’t used a 3D printer before but this project and knowledge of 3D software will give a good excuse to learn how to use one. 
I could even simulate parts of this project using the same software I used at my Co-op if I really needed to.

  To approach this project I would likely start with taking two motors (or a two axis motor), and hook it up to an arduino. This would allow me to get the basics for controlling the motors through an arduino before introducing the other components. 
The second step would be getting some kind of electricity meter and solar panel and testing the feedback through the arduino. The next step would be setting up the PID controller code to receive the electricity input. 
The end result of this project is for it to track the sun's position. There’s a chance it could use more electricity adjusting itself, nullifying any efficiency gains from tracking the sun. 
This could be tested with a control, with a stationary solar panel. Even if it fails in efficiency it’s still a proof of concept and I’d be happy with just getting the basics of it working.
