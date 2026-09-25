# A6 – [Design fits for an artifact]

## Objective
In this lab, we are to design a snap-fit connection for an artifact of our choosing. The artifact has to be some kind of mechanical machine/piece. This branches off the last assignment by allowing us to take our knowledge of designing a basic snap fit by itself to applying it to a real object with pre-made dimensions and criteria. We are to measure the chosen artifact's dimensions using a vernier caliper and model based on these dimensions. 

### Criteria
- Must attach to the physical artifact

- Cannot be pulled apart with ease

- Is a snap-fit connection

## Artifact

<img width="800" height="1422" alt="ezgif com-optimize" src="https://github.com/user-attachments/assets/c66ce228-ef13-427b-8dc4-f847e332c4ae" />

For my artifact, I chose to use a 3-6V motor from an Arduino kit. I am going to make a snap-fit motor mount to hold the motor in place, as well as allow the mount to be screwed into another surface to make it rigid. This idea allows me to combine multiple assignments I have done thus far and combine my learning into one project. What made me think to choose this motor to design a snap fit for was that after completing the motor mount assignment, I saw most motors have bolt holes that screw them directly to the mount itself, but this motor is very small and has no way to directly hold it to a mount. So this will solve two issues at once: one, it allows the motor to be mounted to a surface as needed and gives a way for the mount to hold the motor. 

## Brainstorming

<img width="218" height="287" alt="image" src="https://github.com/user-attachments/assets/35672cd7-86fb-4bbe-bbd6-7ddd1fad9c4c" />

<img width="156" height="96" alt="image" src="https://github.com/user-attachments/assets/c2e76667-e158-4f45-9e8b-76580cc278f2" />

To start his project, I drew out my idea on paper and kept adding and changing things around until i got to a point i was satified with and though would work for a starting prototype. 
## Prototype 1
Learning from my previous mistakes I wanted to start with a simple prototype of just the snap fit feature before adding the rest of the mount to the model. I did this so I could make sure the values I measured with the vernier caliper were correct and the motor will fit into the space properly. I also wanted to test that the snap fit would break by undergoing too much deflection. 

<img width="397" height="335" alt="image" src="https://github.com/user-attachments/assets/5add42fc-21e2-4fc0-a9f9-a999b4afe070" />

<img width="824" height="372" alt="image" src="https://github.com/user-attachments/assets/6ef06a99-d2fe-4066-b83d-266310d00e29" />

I started with a sketch on the top plane where I drew this shape shown using an assortment of arcs, centerlines, dimensions, and relations such as coincident. I then extruded that shape a thickness of .880in. which was the heigh of the flat part of the motor I measured using the caliper.

<img width="952" height="446" alt="image" src="https://github.com/user-attachments/assets/1754351d-8ebe-483a-b494-6624d7a36754" />

### First Print

Next I imported my CAD file into Prusa slicer to get ready for printing. I used PetG and did not change the infill pattern or percentage nor did I scale it at all because I want all the dimensions to same how I created them since the were all measured to an exact value.

<img width="258" height="345" alt="image" src="https://github.com/user-attachments/assets/203797c0-045b-408f-807b-0475c912c17e" />

<img width="253" height="337" alt="image" src="https://github.com/user-attachments/assets/07dec186-dc4c-44f9-a743-da2dee556bd8" />

<img width="257" height="341" alt="image" src="https://github.com/user-attachments/assets/aa4030b3-c9bb-49f1-bb25-55689a37f8c1" />

This is the finished prototype with the motor fixed into place. After seeing this I learned that the snap fit will work and not break but I also learned that I need to support the motor on the front and back because it can currently slide in and out of the mount with just little force. So on my next model I am going to add another piece on the front that will deflect around the back to hold it in place. I also notice tat the over all thickness being .880 is a little to long. This came from me not taking into account the back piece of the motor where the wires connect is a different size and will stick out of mount. So I need to shrink the .880in dimesnions down to fit just the silver part. 

## Prototype 2
Now that I know the main snap fit piece will work I am ready to make a few changes to optimize my design as well as model the rest of the pieces. 

<img width="800" height="320" alt="image" src="https://github.com/user-attachments/assets/789712b7-4d0e-4c49-a7db-530cab57c634" />

My first change was to make the thickness .778in. I got this from measuring the silver part of the motor with the caliper. 

<img width="397" height="340" alt="image" src="https://github.com/user-attachments/assets/fafc16bd-47cf-49c8-8519-ca38a1360bc2" />

<img width="620" height="355" alt="image" src="https://github.com/user-attachments/assets/4d36c180-58d2-4b38-984e-36e472193a42" />

<img width="357" height="159" alt="image" src="https://github.com/user-attachments/assets/402885f3-6516-4322-8696-1014fde358c7" />

<img width="599" height="371" alt="image" src="https://github.com/user-attachments/assets/fdb71f13-7a52-45d2-91bb-4d2de5cbf67d" />

I then added a sketch plane in line with the top hook of the mount. I did this because the length back hook holding in the motor from sliding in an out of the mount will be equal to the distance between the hooks up top. I then sketch my desired shape and extruded it to a distant of .207in which is the distance between the hooks. I then did another sketch extrusion on the other side but I made it flush with the snap fit part because there is no part of the motor that stick out of the front. 

### Print 2

<img width="959" height="485" alt="image" src="https://github.com/user-attachments/assets/aaf08ca4-7f1c-44e2-a2a4-6910605cbc45" />

For this print I oriented it differently to have the biggest surface on bottom because now that I have the tabs on the side to hold the motor in place I can't print it laying on its side. I did also have to use supports here so I set Prusa slicer to autofill the supports and I increased the infill to 20% so it would be a little stronger just to be safe.

## Prototype 3

<img width="804" height="364" alt="image" src="https://github.com/user-attachments/assets/d5c4078f-76e2-402e-ae47-24f6ac496a1f" />

For my third prototype I'm continuing my previous prototype and adding on to the design I already had. I started a sketch on the bottom surface and created two centerline one horizontal and one vertical so I could find the middle of the shape easier. I then drew two circles of equal diameter of .1in on the horizontal centerline. I set both of those circles an equal distance of .2in from the vertical centerline. I then extruded these circles to a length of .2in. These prongs will be what connects the snap fit piece to the actual motor mount itself allowing me to attach the motor to a surface. 

Next I started a new part. This part will be the part of the motor mount that allows the motor to be screwed in, bolted, or attached to a surface in however way needed. The motor itself doesn't have screw holes, so I have to mount the motor by creating a plate allowing me to do so. 

<img width="747" height="332" alt="image" src="https://github.com/user-attachments/assets/71c46a42-2874-4adb-950b-bcb42e75461d" />

I created a sketch on the top plane and made a 1in by 1in plate and extruded it to a thickness of .2in. This is the same thickness as the prongs I made on the bottom of the snap flexure. 

<img width="423" height="356" alt="image" src="https://github.com/user-attachments/assets/a76cd66e-08e7-4a44-9c87-b300984ae801" />

<img width="725" height="361" alt="image" src="https://github.com/user-attachments/assets/55c0b101-7649-462a-9bf7-34f522daa2fe" />

Next I made another sketch on the top surface of the extrusion. I drew two centerlines one vertical and one horizontal. I then drew two circles on the horizontal vertical line and set them both to .2 in from the center with a diameter of .1in. This is the same dimensions as the prongs on the flexure. I then did an extrude cut and set it to through all so the prongs will be flush with the bottom of the surface. 

<img width="394" height="358" alt="image" src="https://github.com/user-attachments/assets/1fb932f1-1112-4c95-96f1-6ad04d0094ea" />

<img width="647" height="371" alt="image" src="https://github.com/user-attachments/assets/4f151b31-fec6-4e4e-9a9e-9df9873f5ae4" />

I then did another sketch on the same surface. This sketch will be the screw holes for the mount to be attached to a surface. I drew four holes in each corner of the plate and set them all to equal distances from the edges. I then extrude cut these and set to through all. 

### Print 3

<img width="953" height="485" alt="image" src="https://github.com/user-attachments/assets/5531b91e-be87-4519-8fef-9b2b0df4e16d" />

For the third print I place both pieces on the plater and set the infill percentage to 20%. I also selected autogenerated supports. 
