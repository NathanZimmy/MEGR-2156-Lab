# Final Project 
# Part 1 Prototype

## Objectives

For this assignment we are going to use the spiral design process to start and prototype our final project. We are to have a product prototyped, and a physical artifact made ready to present to the class using 2 of the three machines we learned this semester (SLA, FDM, Laser Cutter). We are to decide a problem that yourself, a friend, or family member faces and try to solve it using this process and machines. 

## Research
### Spiral Design process

<img width="483" height="343" alt="{D760E7E1-B4CA-4945-97D0-6830A8EAB7D3}" src="https://github.com/user-attachments/assets/a89cc74c-8277-43b1-8c53-f34b6b017e55" />

The spiral design process is a four-stage engineering process that focuses on going around and around each step of the process over again to improve and correct your design until a final product is achieved. It is used heavily because engineering a lot of times requires prototyping and reworking issues that were missed at first instead of having a one and done product. The four stages are: planning/problem identification, risk analysis, product development, evaluation, in this order. Planning starts with identifying the problem you are trying to solve and how you are going to solve it and the limitations such as cost, weight, size, simplicity to the problem. It then as you go on in the project will become planning to solve issues encountered while prototyping and initial design. Risk analysis is the stage where you identify failure points or potential problems that could occur with the design. Engineers will take into account what is happening to the design that could cause failures and other limiting factures such as manufacturability, assembly and time wear. The third stage is engineering/product development. This is the stage where you will develop and manufacture your first prototypes using sketches, CAD, and physical manufacturing. This stage is to test your initial design to see how you planned it to work versus how it actually preforms. The last stage is evaluation. This is where you take the data you collected and notes from you initial design and compare it to the problem you are actually solving. What went wrong, what went right, new issues, and what needs to happen in the next iterations. After this you repeat the process until a desirable product is reached. 

I can use this process throughout my project by identifying which real world problem I want to solve and how I am going to solve it. then by prototyping and evaluation my initial design I can redo the process to enhance and optimize my design and fix any flaws and failures I came across. 

### FDM Anisotropic

Anisotropic means for a material to have a different value when measure in different directions such as wood is stronger along its grain than perpendicular to the grain. Fused Deposition Modeling (FDM) is a form of 3D printing that can cause this to happen. This is because FDM prints in layers creating layer lines similar to a wood grain. The print depending on how the layering is may be stronger against a force in one direction versus another. This is why print orientation matters. print orientation allows you to decide which way you want the layer lines to be printed to you can have them facing the direction of which the force is going. Different materials also may affect this. Some materials are more flexible or stiff than others. Knowing these I will have to take into account what forces are acting on my design and the direction it will be facing and correlate that to how I am going to print it and which material I will use. 

### SLA Shrinkage

When printing with resin or SLA, there is shrinkage that can happen after the curing stage. This can slightly adjust dimensions and  the fitments you initially designed for. This shrinkage depends on the size of your dimensions and the material used as there is no set percentage of shrinkage. Form labs however does list the typical range of shrinkage in its machines. Typical Form 4 XY dimensional tolerances of ±0.15% for features measuring 1–30 mm, ±0.2% for 31–80 mm, and ±0.3% for 81–150 mm, subject to minimum absolute tolerances. This could affect my design if not taken into account because if I design slot fits, sliding, or snap fits they may not work after shrinking or be the size I want. When prototyping I can measure how my dimensions come out versus what I initially design for and use that to adjust the value for a final product. 

### Laser Cutting Kerf

When laser cutting you highly reflected light (laser) burns away material cutting out shaped and engraving patterns you designed for. But since its fire more material is burned away then what you set the dimension to. This is called kerf. This could cause fitments to be too loose by removing too much martial. Kerf can depend on multiple factors including material (wood, plastic, acrylic), material thickness, and laser speed. I can account for this when making my product by doing test cuts and fits and measuring the size of the dimensions and comparing those to my models dimensions then adjusting my model based on the kerf amount. 


## Problem Identification

One problem I have noticed is that when working in the garage with my dad, his workbenches are an absolute mess. Specifically, if we are using wood, like when we built the back deck or working on our cars, he often just dumps hardware everywhere. If we need roofing nails or screws for boards, he will just open a pack and dump them everywhere, and they will spill on the floor because he is very impatient and tries to do everything as fast as possible. Him being my dad, I'm always the one who will clean them up. So I was thinking of making some sort of truck or wagon that, when he opens the hardware, he could pour them into the bed of it and it will stay put. Making it able to roll, or into a truck of some sort, makes it fit my dad since he is a huge car person and he's from Pennsylvania, where horse and buggies are a big thing there. 

A problem I have for myself is not enough displays for my Hot Wheels. I have a lot of hot wheels and a lot more i would like to display but can't. I think it would be pretty cool to design something myself like a semi truck with slots on the back or a garage of some sort for them to sit and be displayed. For a truck type display I could use the laser cutter for the body and fenders of the truck to make the shape then FDM printing to make the wheels axles and other more defined parts to make it roll. If i made a garage i could still use the laser cutter for the walls and floor and even be able to paint and decorate on it afterwards and use the SLA printer with a clear resin to make a front window and dividers so you can see through it while keeping it secured. 

Another problem I could try and solve is 

### Problem selection 

# Prototype 1
## Pre-design Planning and Research

Since I want to make a display for hot wheels car I need to know the average size of a car. 


## Engineering Work
### Laser Cutting

<img width="907" height="367" alt="image" src="https://github.com/user-attachments/assets/c1acfb23-77ff-4684-9c96-6a98dbbdf8f4" />

<img width="671" height="254" alt="image" src="https://github.com/user-attachments/assets/dacbff25-2bbc-4dfa-bec9-e9f2e9e0b606" />

I started with the bottom/ bed of the truck bed making a 1.5in by 10in rectangle. I made it this size because I want it to be able to hold 3 cars. I then made slots small rectangles that will act as the press fits for the walls of the bed to go into. I made the slots .114 by .25 this was to account for the kerf. I used the kerf value I previously measured in another assignment which was .007in. I also made tabs that stick out on the sides for the tailgate and smaller wall. 

<img width="689" height="256" alt="image" src="https://github.com/user-attachments/assets/ff58d359-5ff1-448e-9a73-25932b52c674" />

I then made the side panels of the bed basing the dimensions off the bottom of the bed. I will make two of these one for each side. 

<img width="583" height="281" alt="image" src="https://github.com/user-attachments/assets/d88e160b-b5d1-4082-9e7c-546ed5f95b1d" />

The last part of the bed I needed to make were the front and the tailgate piece. The tailgate in the prototype will not open but I am going to try to make a hinge mechanism to open it in the final product.

<img width="270" height="356" alt="image" src="https://github.com/user-attachments/assets/e3b58126-3ddc-4d81-ae39-5f492a547592" />

<img width="829" height="313" alt="image" src="https://github.com/user-attachments/assets/1129b5e1-f66f-4315-a2ca-4260cc0c0c50" />

Here are the settings and cut time for my pieces. 

<img width="219" height="242" alt="image" src="https://github.com/user-attachments/assets/09e8b3eb-a2dc-4909-bfc8-446914075047" />

<img width="215" height="207" alt="image" src="https://github.com/user-attachments/assets/ba0b2e3c-c8e2-4b53-ab5c-bc3b6ff5d5ab" />

<img width="400" height="711" alt="IMG_2019-ezgif com-resize" src="https://github.com/user-attachments/assets/a8621bdb-9c15-4274-87df-1a7e222e3a6f" />


### 3D Printing (Frame, Axels, Wheels)

<img width="623" height="202" alt="image" src="https://github.com/user-attachments/assets/5f68a1a0-985a-4741-baff-be58e3f5ec7a" />

<img width="396" height="254" alt="image" src="https://github.com/user-attachments/assets/c8f68ad1-5bff-405a-925d-4c3beab3d304" />

<img width="824" height="370" alt="image" src="https://github.com/user-attachments/assets/12cf7474-3dac-487b-98e3-52b44cf804e3" />

<img width="143" height="236" alt="image" src="https://github.com/user-attachments/assets/632caf6a-0871-4358-a800-47519007b5b2" />

I made the frame based off the dimensions of the woodcut. This frame is going to be glued to the bottom of the woodcut pieces. I also made a hitch attachment so that I can have a way of connecting the cab to the trailer bed.


<img width="621" height="320" alt="image" src="https://github.com/user-attachments/assets/7f793d19-9214-4f1d-97fc-26785d77d473" />

Here I made the axels by extruding a circle to a length of 2in. This will give me room to have the tires be .25in thick and stick off the sides of the frame. The diameter of the axle is .1in which is .05in less than the whole on the frame. this will give it enough clearance to spin freely. 

<img width="754" height="352" alt="image" src="https://github.com/user-attachments/assets/e5e42e22-4925-476c-83c6-e6c669fe564f" />

<img width="350" height="343" alt="image" src="https://github.com/user-attachments/assets/00a46add-0c46-405e-84d5-8eab430d07ff" />

Lastly I made the wheels. I used a caliper to estimate the height I wanted to make the wheels by just using my eyes and estimating from the woodcut parts and .75in looked good. I then made a hole in the middle of .12in diameter. This will be where the axels fit in and it is supposed to be a press fit with little give. 

### Prusa Slicer

<img width="959" height="446" alt="image" src="https://github.com/user-attachments/assets/91c94acf-2b89-4b86-96d0-b746136034ac" />

I had to rotate the frame body diagonally so it would it on the plater. I kept the infill at 15% because none of these pieces will be undergoing much external forces. I did have to use organic supports on the hitch part but I oriented everything else so it would'nt require supports. 

### Printing


<img width="331" height="330" alt="{EA6DA8FD-B8BA-4A93-8DC3-AF1A2A62BB6C}" src="https://github.com/user-attachments/assets/57f36c30-3cbb-415c-81e6-2ef19d5e9fb2" />


<img width="329" height="335" alt="{6C27BEE8-4487-4684-8ACB-E60AA4438CCE}" src="https://github.com/user-attachments/assets/bf4688c9-9194-45d7-ba79-9da2aff00df2" />


<img width="326" height="244" alt="{D6843A1B-5BC8-445A-A6FF-FE19FD466DC8}" src="https://github.com/user-attachments/assets/f821d54f-df59-485d-bb01-199255a58077" />

<img width="800" height="1422" alt="ezgif com-optimize (1)" src="https://github.com/user-attachments/assets/4adc892e-0133-409b-9429-611e8fe40bc5" />

During my first print the printer accidentally knocked the axels over and caused them to fail which also let so extra material getting deposited on the frame. While it looked ugly I was able to scrap off all the hanging material and the frame still came out relatively fine. 


<img width="574" height="421" alt="{02D9D808-79E1-4F46-ADB4-74C0CA9E8DEF}" src="https://github.com/user-attachments/assets/07d9b678-4e5a-42d1-8bda-bfdf52c465b4" />


<img width="327" height="430" alt="{E275C8DD-3E2E-4D4C-A99B-AFD3138CA68A}" src="https://github.com/user-attachments/assets/4080ae1a-dc33-4492-803f-9a9c0351bc2f" />

Reprinting the axels was very quick though since there are small and it only took about 5 minutes. I did reorient them laying down instead of standing tall. 


<img width="322" height="303" alt="{9959795B-D697-4559-901C-5E5960F3856D}" src="https://github.com/user-attachments/assets/1967e9d7-74c5-4d53-9f0e-cf82c0b86348" />

<img width="316" height="359" alt="image" src="https://github.com/user-attachments/assets/2679f892-6002-4b6d-91b7-ba3463957de9" />

<img width="320" height="218" alt="{0DD8825A-8C96-4AB2-94A9-8AE8E88E82C5}" src="https://github.com/user-attachments/assets/b6f24715-1334-4313-ad40-d6a2d591f038" />

Here is the flat bed finished prototype. I have a lot of issues that need to be fixed such as the laser cutting fitment isn't quiet as tight as I'd prefer and the back and front plates keep falling off. I also have to reprint the frame and axels again because the failure went deeper than i thought and it added material into the holes where the axels go. The axels can still roll and spin but i had to force oe of them into place and it cause some deviation on the end of the axle and now one of the wheels isn't as tight of a fit because the axel is too small, but the rest of the wheels fit and roll prefectly. 

  
## Part 1 Sources

Spiral Design Process- https://teachingagile.com/sdlc/models/spiral

Form labs shrinkage percentages- https://formlabs.com/global/3d-printers/resin/tech-specs/?

# Part 2 Final Product
## Peer Evaluation Worksheets

[CamScanner 11-23-26 11.07.pdf](https://github.com/user-attachments/files/35285627/CamScanner.11-23-26.11.07.pdf)

## Refinement Ideas

To improve on my first prototype I have a few things I want to do. First I want to remove the slotted firmaments on the laser cut pieces and use glue to put the pieces together. At first I didn't realize I could glue on any piece and I think it would much easier and strong to glue the walls of the bed and cab together and it will also have a much smoother look and save space since I don't have to leave space on the edges of the bed so the laser cuter doesn't cut too far off the edge making it an open hole and not a slot. This will also in return make the bed larger for wider cars to fit. Second I want to add a hinge mechanism on the end of the FDM fram of the bed to make a ramp for the cars to be able to roll up on and be more realistic. I also want to add treads and texture to the wheels to add some design details. lastly I want to add chains on the back of the cab that can connect to the bed simiallry to the hitch because the flatbed I have used had chains that attached beisde the hitch and I think it would be a cool detail to add. 

## Prototype 2

<img width="1746" height="648" alt="image" src="https://github.com/user-attachments/assets/24fea086-75cd-4d92-994b-ebf436e3292e" />

I started with the same frame I built previously and I'm going to edit this file and add on the new additions that I want. 

<img width="1650" height="371" alt="image" src="https://github.com/user-attachments/assets/c9dd1803-8bb7-4aba-845b-1864ed047896" />

<img width="1489" height="694" alt="image" src="https://github.com/user-attachments/assets/7fb3e47a-57e4-4932-9373-d0acb0a01fd6" />

<img width="975" height="600" alt="image" src="https://github.com/user-attachments/assets/1de74348-d199-4f05-a290-5331770ae91d" />

First I added holes or another hotch type shape for the chains I will make on the cab to hook into. 

I made a few simple extrusions and extrude cuts to make the holes in the pieces sticking out for the chains to go into then I mirrored the hole and the fillets I added to make it more round about a center plane. I had to manual add in the plane to make it easier and faster than dimensioning another whole. 
