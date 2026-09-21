# A5 – [Snap Fits]

## Objective
The goal of this lab is to design and print a snap fit connection. A snap fit connection requires two or more pieces that fit together using elastic deformation. We are to create a design, print it, and physically demonstrate that it works properly. Before designing, we are to research a common Young's Modulus, use the yield strength of PLA, use a safety factor of 3.5, and choose a transverse load between .25 lbf - 5 lbf. The dimensions of the design will depend on the flexing using the chosen load.

## Pre-design research

What is a snap fit? A snap fit is a connection that uses elastic deformation to flex and unflex to create a fit. Common examples of snap fits are bookbag clips, LEGOs, battery casings, and remote control back plates.
<img width="535" height="309" alt="image" src="https://github.com/user-attachments/assets/d95f57aa-76d2-4363-a280-53873b7ce0f8" />

<img width="1920" height="1094" alt="image" src="https://github.com/user-attachments/assets/fac16a4a-88ba-4838-80fe-a3cbe3e7cf69" />

<img width="1429" height="803" alt="image" src="https://github.com/user-attachments/assets/3b3e2483-5e98-44c1-b76b-3624120aa182" />

I wanted to research my choices for snap-fit connections to brainstorm what kind of design I wanted to create. I found there are many kinds of snap-fit connections, giving me a lot of variety and freedom in what I want to design. Some common ones I found are cantilever, ball-and-socket, L-shaped, and U-shaped joints. I decided I wanted to try


## CAD Model prototype (parametric)
### Part 1

To start this project, I wanted to start off by prototyping my CAD model. The assignment states for us to select the initial geometry of the design and solve for the flexure dimensions depending on which type of snap fit we make, as well as what initial geometry we choose to create. We have to solve for the flexure length later because the length will depend on how much force needs to be applied to the end of your snap-fit to unlock it. For my project, I chose to create a simple cantilever beam with a hook end that will snap into place after sliding into the hole I will create in part two. So my flexure length (the length of the arm connected to the rigid base) will depend on how far I have to push the hook over to fit it back into the hole after it snaps into place, as well as how much force is required.

<img width="377" height="204" alt="image" src="https://github.com/user-attachments/assets/b572dbe6-b668-4d17-a313-f55a70176abe" />

<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/4c1b8f52-40d2-44ce-87dd-eba2876a2da6" />

<img width="405" height="300" alt="image" src="https://github.com/user-attachments/assets/0c475dd6-95af-409d-be8d-5b3ffd9e5e59" />

<img width="654" height="293" alt="image" src="https://github.com/user-attachments/assets/f9da580e-a6e1-4677-83b0-63b0a6475bce" />

For the model itself, I started with a simple 2in by 2in base and extruded it to a thickness of .5in. Next, I needed to add the flexure to the middle of the base. I started by adding a center plane in the middle of the base. I did this because sketching on top of the base would've been more difficult to extrude since I have an overhang for the hook part of my flexure. I would've had to split it into 2 extrudes to be able to create the hook. So instead, I can create a center plane and sketch the flexure from the side, allowing me to extrude the piece as a whole. The downfall of this is that this piece has a certain thickness, and I need that thickness to be the exact center of the base, and since the plane is at the center, I can't do that. So I would just have to mirror the extrusion about that same plane I'm sketching on to have it be at the center. I just had to take this into account for my dimensions when modeling. Since I am going to mirror the extrusion, I have to make my thickness dimension half of what I actually want it to be so that when I mirror it about the plane, the thickness dimensions will add together to the value I want. 

To model the flexure, I started a sketch on the plane I created earlier and made a cantilever beam shape with a hook end with a total height of .50in and a total width of .20in. I made the hook end stick out from the shaft of the shape by .05in. I then extruded this shape by .05in. This will add up to .1in after mirroring. 

<img width="626" height="323" alt="image" src="https://github.com/user-attachments/assets/0672e866-bfe4-431b-ab0a-6c85df633791" />

<img width="530" height="272" alt="image" src="https://github.com/user-attachments/assets/bb1e2868-9c39-4a4a-bfdc-e7ec332c4c8c" />

Here is where I implemented the mirror, about the same plan I sketched, which is in the center of the base. This is the complete prototype of part one before I calculate what the flexure length needs to be. 
### Part 2
<img width="216" height="182" alt="image" src="https://github.com/user-attachments/assets/87bba827-2caa-4a27-aaee-af089ea4aecc" />

<img width="203" height="304" alt="image" src="https://github.com/user-attachments/assets/6ef86741-a137-4319-9068-241322ea7c2f" />

<img width="371" height="314" alt="image" src="https://github.com/user-attachments/assets/87c4991f-93a3-4a75-8187-3cf696c5e602" />

## Printing the Prototype
I wanted to print the prototype to see initially how it would turn out. I did this for a few reasons: one, to see if the snap fit I created before taking forces and math into account would work, and two, simply to feel and touch what I had made to get a better understanding of what needs to happen in my next steps. I had to add supports for the hook end, which I did by going into the print settings and auto-generating the supports and support material. I also scaled it down 70% to make it print a little faster since this isn't my final product. I tried to scale it down smaller to 50%, but the supports wouldn't come out right if I made it that small. 

<img width="674" height="335" alt="image" src="https://github.com/user-attachments/assets/093d5091-7b63-4011-9302-41cd4323a8ef" />

<img width="959" height="437" alt="image" src="https://github.com/user-attachments/assets/62795351-a7b2-4e6c-9035-5dbda7ef90f6" />

<img width="947" height="443" alt="image" src="https://github.com/user-attachments/assets/c85f0652-da99-4d85-9cd3-5b9b75519d2c" />

## Calculating the Length of the Flexure

## Communicate

