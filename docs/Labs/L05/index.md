# A5 – [Snap Fits]

## Objective
The goal of this lab is to design and print a snap fit connection. A snap fit connection requires two or more pieces that fit together using elastic deformation. We are to create a design, print it, and physically demonstrate that it works properly. Before designing, we are to research a common Young's Modulus, use the yield strength of PLA, use a safety factor of 3.5, and choose a transverse load between .25 lbf - 5 lbf. The dimensions of the design will depend on the flexing using the chosen load.

## Pre-design research

What is a snap fit? A snap fit is a connection that uses elastic deformation to flex and unflex to create a fit. Common examples of snap fits are bookbag clips, LEGOs, battery casings, and remote control back plates.
<img width="535" height="309" alt="image" src="https://github.com/user-attachments/assets/d95f57aa-76d2-4363-a280-53873b7ce0f8" />

<img width="1920" height="1094" alt="image" src="https://github.com/user-attachments/assets/fac16a4a-88ba-4838-80fe-a3cbe3e7cf69" />

<img width="1429" height="803" alt="image" src="https://github.com/user-attachments/assets/3b3e2483-5e98-44c1-b76b-3624120aa182" />

I wanted to research my choices for snap-fit connections to brainstorm what kind of design I wanted to create. I found there are many kinds of snap-fit connections, giving me a lot of variety and freedom in what I want to design. Some common ones I found are cantilever, ball-and-socket, L-shaped, and U-shaped joints. I decided I wanted to try


## CAD Model (parametric)
### Part 1

To start this project, I wanted to start off by prototyping my CAD model. The assignment states for us to select the initial geometry of the design and solve for the flexure dimensions depending on which type of snap fit we make, as well as what initial geometry we choose to create. We have to solve for the flexure length later because the length will depend on how much force needs to be applied to the end of your snap-fit to unlock it. For my project, I chose to create a simple cantilever beam with a hook end that will snap into place after sliding into the hole I will create in part two. So my flexure length (the length of the arm connected to the rigid base) will depend on how far I have to push the hook over to fit it back into the hole after it snaps into place, as well as how much force is required.
<img width="377" height="204" alt="image" src="https://github.com/user-attachments/assets/b572dbe6-b668-4d17-a313-f55a70176abe" />

<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/4c1b8f52-40d2-44ce-87dd-eba2876a2da6" />

<img width="405" height="300" alt="image" src="https://github.com/user-attachments/assets/0c475dd6-95af-409d-be8d-5b3ffd9e5e59" />

<img width="654" height="293" alt="image" src="https://github.com/user-attachments/assets/f9da580e-a6e1-4677-83b0-63b0a6475bce" />

For the model itself, I started with a simple 2in by 2in base and extruded it to a thickness of .5in. Next, I needed to add the flexure to the middle of the base. I started by adding a center plane in the middle of the base. I did this because sketching on top of the base would've been more difficult to extrude since I have an overhang for the hook part of my flexure. I would've had to split it into 2 extrudes to be able to create the hook. So instead, I can create a center plane and sketch the flexure from the side, allowing me to extrude the piece as a whole. The downfall of this is that this piece has a certain thickness, and I need that thickness to be the exact center of the base, and since the plane is on the center, I can't do that. So I would just have to mirror the extrusion about that same plane I'm sketching on to have it be on the center. I just had to take this into account for my dimensions when modeling. Since I am going to mirror the extrusion, I have to make my thickness dimension half of what I actually want it to be so when I mirror it about the plane, the thickness dimensions will add together to the value I want. 

<img width="626" height="323" alt="image" src="https://github.com/user-attachments/assets/0672e866-bfe4-431b-ab0a-6c85df633791" />

<img width="530" height="272" alt="image" src="https://github.com/user-attachments/assets/bb1e2868-9c39-4a4a-bfdc-e7ec332c4c8c" />

### Part 2
<img width="216" height="182" alt="image" src="https://github.com/user-attachments/assets/87bba827-2caa-4a27-aaee-af089ea4aecc" />

<img width="203" height="304" alt="image" src="https://github.com/user-attachments/assets/6ef86741-a137-4319-9068-241322ea7c2f" />

<img width="371" height="314" alt="image" src="https://github.com/user-attachments/assets/87c4991f-93a3-4a75-8187-3cf696c5e602" />

## Communicate

