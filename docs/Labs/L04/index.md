# A4 – [Benchmark A Parameter]
## objective
The objective of this lab is to create a design or benchmark that will push the limits of a Prusa Core One parameter and hopefully cause a failure when printing. We know how to print and what the Core One can do, but now we are to learn what it can't do and what its limits are. We are given a few parameters to choose from, but we are allowed to find any that we want to test. The parameters we were given to choose from are overhang angle test, pull strength test, tolerance gauge test, and dimension calibration test. 

### Criteria
Print may not exceed one hour total print time

## Parameter Choice and Prediction
The parameter I want to test is the overhang angle test, and I want to do this by designing an archway that is long enough to gauge how far the machine can print before the filament is too weak to support its own mass. The parameter says it can go up to a 45% angle, but a lot of archways are wider than this, so I want to see how angled I can make the archway. This is a different test than most people do by using a linear plane with a set angle to test. While that is effective, I want to test it slightly differently by adding curvature. A lot of components use arches and curvature rather than straight-cornered angles, so I want to know the capabilities of using this in a future design. I predict that the printer will fail after 45% because these machines are pretty advanced, and I think the 45% is a safety net, but it can really do more.

## Design 
The design I chose will have two arches, each of different geometry. It is similar to the McDonald's Golden Arches, and I based this idea on McDonald's because I am a thorough enjoyer of McDonald's. One arch is going to be very steep and skinny, while the other will be wider and stretched out. This is to see what it can and can't do. I think it will be able to do the steep, skinny arch because it does not surpass the 45% angle rule, but the wider arch will have issues printing towards the top.

To start my model, I created a sketch on the top plane and drew three lines of equal length and distance apart from each other. These will be the footholds that touch the plate when printing. I first changed the units to mm instead of inches so I would have a better idea of how it will fit onto the plate when printing. I set the base lines to 8mm and the spacing in between to 18mm for now, but this will have to be changed later after I get the initial arch built.

<img width="479" height="415" alt="image" src="https://github.com/user-attachments/assets/e75b5a6a-70bb-436c-954a-3eab3666bb2a" />

<img width="344" height="155" alt="image" src="https://github.com/user-attachments/assets/0de9673d-4571-4a73-9ac7-bb559b47cee8" />

Next, I had to build the curves. My thought was to build one side at a time, then mirror the arch using a centerline onto the other side. So I used the spline tool to create the arches, just picking a point at the top and connecting it to the middle foot. The for the top edge of the arch creating another spline, and puting the first point in line with the inner surface and going to the middle of the middle foot. I had to place a centerline to find the middle. I also went and set the heights of the arches to 60mm for the top surface and 50mm for the inner surface, creating a 10 mm thickness. I also set the height of the other surface to the bottom of the foot to 10mm to keep that same uniform thickness around and not just guess.

<img width="463" height="284" alt="image" src="https://github.com/user-attachments/assets/7c445d27-0c1f-432b-be18-c78f81deb075" />

Next, I mirrored the inner and outer surfaces of the arch sketch about the centerline. This, however, did not work and caused my sketch to be unsolvable, and I wasn't able to find out why, so I moved on to doing it the long way and drawing the other side of the arches. It was easy because SolidWorks allows me to set the points for the spline on the same axis as the other points I previously set.

<img width="740" height="317" alt="image" src="https://github.com/user-attachments/assets/a3881a5c-a1c4-4ba8-9f0b-a14a91296614" />

<img width="470" height="278" alt="image" src="https://github.com/user-attachments/assets/ca976be1-3546-4e60-ab12-4a68eba32eac" />

<img width="497" height="284" alt="image" src="https://github.com/user-attachments/assets/5188be22-81d2-4cec-9d7a-e5716b0d9728" />


next

<img width="524" height="221" alt="image" src="https://github.com/user-attachments/assets/6aadd65d-51c6-4dc9-ac3d-a80f927c9711" />

next

<img width="837" height="255" alt="image" src="https://github.com/user-attachments/assets/e1bfc411-157b-4da9-b638-3dda30fd0065" />

next

<img width="533" height="300" alt="image" src="https://github.com/user-attachments/assets/077c7d05-86ed-4453-8438-59564a8de1b8" />

next

<img width="958" height="487" alt="image" src="https://github.com/user-attachments/assets/b764495c-78cf-4000-8864-70efae49021d" />

## Resources
https://help.prusa3d.com/article/modeling-with-3d-printing-in-mind_164135

