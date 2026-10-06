# A7 – [Linkage and Mechanisms]

## Objective
For this week's assignment, we are to research, learn, understand, and design linkages and mechanisms. We will design linkages using existing hardware to fasten the pieces together. While researching, we will document our findings and the design process throughout the project. 

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

<img width="537" height="320" alt="image" src="https://github.com/user-attachments/assets/ceea7bad-1e09-4c8a-b205-38578abef6cc" />

<img width="358" height="310" alt="image" src="https://github.com/user-attachments/assets/327c9896-8052-433a-9a00-4280a923305a" />

Next was to make the pins to connect the members together. I started by drawing a circle with a diameter of .23 in on the top plane. I did .23 so it will be smaller than the hole diameter, but knowing how 3d printing works, I'm hoping that friction and the slight change in dimensions will be enough to allow it to slide into the hole and slide into place. I then extruded it to a thickness of .25 in, which is double the thickness of the members because it needs to hold two together plus a little more for retaining room. Lastly, I did another sketch on the bottom of the first feature and drew another circle from the center of the first and made it have a diameter of .3in. I then extruded that to a thickness .05in. This feature allows me to push the pin into the hole and support it from one side. 

I originally thought of making a male-female connection here for the pin by shelling out on one side and making another shape to insert into the shell. But after some debating, I didn't think this would be necessary and would only complicate things and make printing harder. I tested it in CAD, and the wall thickness of the shelled piece would be very thin and have a high chance of failure. 

<img width="673" height="284" alt="image" src="https://github.com/user-attachments/assets/53449fe4-ff58-4987-b4c0-36b0dfd566d4" />

<img width="323" height="316" alt="image" src="https://github.com/user-attachments/assets/5f12fe5a-a5f7-479f-aa6b-336ee3974d1e" />

<img width="800" height="1422" alt="ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/fc69e209-fc43-4fca-97a4-21ab7dd36616" />

This is the design made in an assembly to test the fits and how it will look all together. Here you can also see how it will rotate about the pin. 

## Print 1

For my first print, I only did 2 members and one pin just to see if the pin would fit and the design would actually work before I had to wait a longer time to print all of it and it ends up not working. If it does work, then I would only have to print 2 more members and three more pins.

<img width="959" height="472" alt="image" src="https://github.com/user-attachments/assets/a9b80a61-ee92-4ab5-ae94-2f4054eb7686" />

I oriented everything flat so no supports would be needed, and I used PLA with a 15% infill and a regular grid infill pattern. This was printed on PC-14.

<img width="800" height="1422" alt="ezgif com-optimize (6)" src="https://github.com/user-attachments/assets/804a2339-eec9-402a-9b9a-5927405e3796" />

<img width="254" height="336" alt="image" src="https://github.com/user-attachments/assets/db20f89d-e1b4-4046-b9c5-e3946f69ce00" />

<img width="263" height="186" alt="image" src="https://github.com/user-attachments/assets/baa216d5-52e8-4854-b493-5bb1421482bd" />

After the first print, I found the pin was too small/too loose. So I am going to make the diameter wider and a little bit longer. 

## Print 2

<img width="362" height="305" alt="image" src="https://github.com/user-attachments/assets/d56005de-6f70-4112-bc21-d243c917e377" />

<img width="757" height="358" alt="image" src="https://github.com/user-attachments/assets/2d52552a-3ca8-4975-8ef6-953b532cf2b5" />

After finding out the pin was too small, I went into my CAD files and changed the dimensions to make it slightly bigger. I made the pin diameter .25in which is the same as the hole, and the length of the pin .3in. to give it a little more working room.

<img width="959" height="412" alt="image" src="https://github.com/user-attachments/assets/da6a05d7-dfba-4aa6-bcb2-20f63cd5801e" />

To slice this time, I went ahead and added the other 2 links because I liked the way the first two came out and I didn't adjust them at all. I also added the new pin design. I left the infill percentage and pattern all the same with generic PLA, and this time I am printing on PC-15.

## Print 3

For this third print, I am going to print the last pins I need, as well as caps to support the links for the other side that is open to hold them together. 

<img width="323" height="292" alt="image" src="https://github.com/user-attachments/assets/5b5ab16f-3cb5-4892-be49-1c89608422c0" />

<img width="368" height="293" alt="image" src="https://github.com/user-attachments/assets/b1c289f2-1777-4f81-ad4c-73c9abc62d46" />

I started with a circle with a diameter of .25in and extruded it to a thickness of .10in

<img width="372" height="269" alt="image" src="https://github.com/user-attachments/assets/94951663-a179-4a70-82b8-38e1bc1c5b93" />

I then did an outward shell with a thickness of .01in.


## Lessons Learned

### time taken
This entire project took about 6 hours. This consisted of 4 hours of research and portfolio creation, 1 hour of design, and 1 hour of printing. This took a lot less time than I originally expected when I saw this assignment. When I first read the assignment and saw the mechanism, I had no idea what that meant, but after research, I did a relatively simple project, which allowed me to not take as long as I was expecting. 

### Biggest Mistake
The biggest mistake I made was underestimating how hard it would be to make the pins to connect the links. I saw many people using already-made hardware they bought, whereas I made my own. This was my first time designing something hardware-related to hold pieces together, so I didn't really know how it works or how dimensioning is supposed to be done, such as tolerancing it and making it fit properly. 

### Tolerances
My first print did not work. The dimensions I made for the pins were too small and too loose in the hole. So I made them longer as well as the same diameter as the hole itself. 
## Sources

1) https://3dprinterly.com/how-to-3d-print-connecting-joints-interlocking-parts/

2) https://engineerfix.com/a-complete-guide-to-linkage-mechanisms/

3) https://patents.google.com/patent/US20250065979A1/en?q=(linkage+body+part)&before=priority:20231231&after=priority:20230101&oq=2023+linkage+body+part

4) https://patents.google.com/patent/US12103164B2/en?q=(linkage+mechanism+arms)&before=priority:20231231&after=priority:20230101&oq=2023+linkage+mechanism+arms
