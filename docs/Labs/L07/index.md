# A7 – [Linkage and Mechanisms]

## Objective
For this week's assignment, we are to research, learn, understand, and design linkages and mechanisms. We will design linkages using existing hardware to fasten the pieces together. While researching, we are to document all our findings and the design process throughout the project. 

### Constraints
- The linkage or mechanism must perform motion or a task

- Hardware may consist of screws, bolts, pins, or springs

- Model must be our own design and 3d printable
- 
## Research
- Find at least two linkages or mechanisms that were developed, patented, or published within the last 5 years (2021–present)

- For each one, explain how it works and include an image or sketch.

- For each one, describe how it could be used in at least two different industries.

- Cite at least three credible sources, such as journal articles, patents, conference papers, or reputable industry publications.

### Patent 1
<ins>Reducer bodies, extender bodies, suspension linkages, and two-wheeled vehicles including the same</ins>
Inventor: Peter Zawistowski

<img width="332" height="232" alt="image" src="https://github.com/user-attachments/assets/700e2372-6fe7-4888-8f7b-2736691101c3" />

<img width="308" height="230" alt="image" src="https://github.com/user-attachments/assets/517795d3-0f8d-4558-a2db-d7123fce8f7b" />

<img width="202" height="231" alt="image" src="https://github.com/user-attachments/assets/9fa3294c-497a-4bda-8802-d38457a31c10" />

This design is a bicycle suspension linkage. Its purpose is to soften the blow on the bicycle frame when you hit a bump or uneven surface. It does this by allowing the rear wheels to move upwards using a linkage system instead of keeping the bicycle as one rigid body. It does this by having the rear suspension linkage rotate the rear shock, and the shock compresses and absorbs the force from the ground. The linkage itself controls the movement and activation of the shock. 

This design could be used in almost any two-wheeled transportation or recreational industry, including bicycles, motorcycles, and e-bikes. It could also be resized and adjusted slightly to be used on medical service equipment such as wheelchairs and stretchers to help them roll along uneven surfaces and support patients. 

-Source 3

### Patent 2
<ins> Gripper mechanism </ins> 
Inventor: Brian Todd Dellon

<img width="338" height="108" alt="image" src="https://github.com/user-attachments/assets/c429a330-7329-4c6b-88a2-80b1e9d11a8d" />

<img width="279" height="233" alt="image" src="https://github.com/user-attachments/assets/15e7f5ae-cdb0-4a5a-a49a-2bf4017d15a2" />

Here is a "gripper mechanism." This mechanism has a pair of jaws, a linear actuator, and a pivoting rocker bogey. The actuator uses a lead screw and drive nut. When the motor turns the lead screw, the nut travels along the screw. That linear motion is transferred through the rocker/cam arrangement, which causes one gripper jaw to move relative to the other. The second jaw can remain fixed while the first jaw closes around the object.

This design can be used in many industries in robotics and artificial intelligence. It has a gripper hand for the robot to grab and hold things and perform specific tasks. It can also be implemented in the biomedical and prosthetic industry by adding a way to connect the gripper to the nervous system or being able to control it with a device to allow for grabbing items like a regular hand. 

-source 4

## Brainstorming

<img width="224" height="193" alt="image" src="https://github.com/user-attachments/assets/6fd9e449-b7f4-461a-a66f-6d383846a8a6" />

When I first searched linkages and saw different members being attached by pin connections, I instantly had an idea of a tool I had seen before. An expanding ruler uses the same type of system by allowing multiple members to rotate freely relative to each other to create a longer measuring device while staying together as a whole tool. So my idea is to make four alike members, each with pin holes on each side, allowing me to connect them. I will separately design pins to fit in the holes, attaching the members together. I chose four because it allows me to either leave the design as one long, free-moving line, combine it end to end and create a square or diamond shape, or take a member out and create a triangle.

## Linkage Solidworks Model 

<img width="539" height="325" alt="image" src="https://github.com/user-attachments/assets/b701c775-5308-496b-ae24-f46224ce1bba" />

<img width="575" height="295" alt="image" src="https://github.com/user-attachments/assets/9399e645-9661-4a05-a0a2-573c6d2a36fd" />

I started with a sketch on the top plane and created two lines 3in long and .5in wide, parallel to each other. I chose 3in long because I am making 4 members, so it will be a total of 1 foot long. I then added a 3-point arc on both sides with a radius of .35in to enclose the shape. Next, I extruded the shape to a thickness of .1 in. I chose this so it would be thin enough for all the members to attach together and not be too thick, as well as to keep the print time down. Lastly, I did a fillet on the edges to make the members rounded. 

<img width="634" height="203" alt="image" src="https://github.com/user-attachments/assets/45c2ebdb-8516-445c-86b9-6d5ccc86d31a" />

<img width="677" height="264" alt="image" src="https://github.com/user-attachments/assets/66e2fa1f-ac88-4384-a500-0ec8fbad5b78" />

The next step was to add a hole into each side of the link to allow them to attach to each other. I created two centerlines on the 3-point arch to find the center connection point of the arc to the body of the link. I then placed a circle on that center point and set the diameter to .25in which is half of the total width of the member. I then created another centerline in the middle of the member and mirrored the circle across that line. Lastly, I did an extrude cut and set it to through all. 

<img width="275" height="225" alt="image" src="https://github.com/user-attachments/assets/4328e341-cb7e-43bf-85db-84a027cdf255" />

<img width="513" height="275" alt="image" src="https://github.com/user-attachments/assets/9e3cb764-a3ed-46c0-b465-db263804e62d" />

Next was to make the pins to connect the members together. I started by drawing a circle with a diameter of .23 in on the top plane. I did .23 so it will be smaller than the hole diameter, but knowing how 3d printing works, I'm hoping that friction and the slight change in dimensions will be enough to allow it to slide into the hole and slide into place. I then extruded it to a thickness of .25 in, which is double the thickness of the members because it needs to hold two together plus a little more for retaining room. 


## Sources

1) https://3dprinterly.com/how-to-3d-print-connecting-joints-interlocking-parts/

2) https://engineerfix.com/a-complete-guide-to-linkage-mechanisms/

3) https://patents.google.com/patent/US20250065979A1/en?q=(linkage+body+part)&before=priority:20231231&after=priority:20230101&oq=2023+linkage+body+part

4) https://patents.google.com/patent/US12103164B2/en?q=(linkage+mechanism+arms)&before=priority:20231231&after=priority:20230101&oq=2023+linkage+mechanism+arms
