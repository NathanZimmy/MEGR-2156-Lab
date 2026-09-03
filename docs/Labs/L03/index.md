# A3 – Design Something Small

## Design
For my self-design, I wanted to make a small cracker. Similar to a Ritz cracker but smaller to fit the maximum dimension criteria we were given. I chose this because we were given basic instructions to design something small with no stipulations except to be school-appropriate. So while I was brainstorming ideas, I was sitting there eating Ritz crackers and thought that I like food and I need to model something simple, and what's more simple than a cracker.
#### Criteria
-No more than 0.5in tall

-No overhangs

-Large enough to use an infil

-Modify the wall thickness

-Print in PLA or PETG

-No more than 1.5in by 1.5in

-Print time must be less than 1.5 hours

## SolidWorks Model

<img width="352" height="269" alt="image" src="https://github.com/user-attachments/assets/2c1ab809-49c1-4e5f-aecb-174fb5d34422" />

To start my model, I simply sketched a circle on the top plane and made the diameter 1in. A real Ritz cracker is 1.8in in diameter, but I wanted mine to be smaller. I then extruded the circle to a height of .1in 

<img width="380" height="310" alt="image" src="https://github.com/user-attachments/assets/254d7d12-aa6c-413c-ae4e-fe3a3c362f6d" />

I then wanted to add holes into the cracker. So I did a bunch of extrude cuts onto the top surface of the cracker. I chose not to do a pattern here because no cracker is the same, and I want it to be more authentic, even if it took longer to model. I set the extrude cuts to through all, and the diameters of the holes ranged from 0.03-0.08in.

<img width="341" height="233" alt="image" src="https://github.com/user-attachments/assets/eb637a1b-3380-4cd0-8d83-0ea196422453" />

<img width="422" height="253" alt="image" src="https://github.com/user-attachments/assets/bf1d1e59-c796-49b4-bb4d-c7aab0a84ad9" />

<img width="289" height="211" alt="image" src="https://github.com/user-attachments/assets/2b56bd5b-f9b4-4c91-b32b-887ca2b6cac3" />

Next, I did a fillet on both outer edges to make the shape more round. I set the radius of the fillet to 0.05in. I also went into my display options and turned off display tangent edges so it wouldn't have a crease line.

<img width="364" height="259" alt="image" src="https://github.com/user-attachments/assets/a57133da-b4cd-436f-909d-0f8dee5e4c81" />

<img width="384" height="233" alt="image" src="https://github.com/user-attachments/assets/e3a2afc9-dacd-4c7c-b3b0-c19bbf41fb24" />

I then wanted to make all the holes more rounded. So, I did another fillet and set the radius to 0.01in. I did this for the top and bottom of the cracker. This was the final step in modeling my design.

## PrusaSlicer

<img width="265" height="196" alt="image" src="https://github.com/user-attachments/assets/937c032c-0e0f-4337-ae30-2f8ebed90f46" />

<img width="128" height="64" alt="image" src="https://github.com/user-attachments/assets/e64a2d80-7cae-4c9d-96c0-01b0981e0895" />

<img width="180" height="163" alt="image" src="https://github.com/user-attachments/assets/f956a912-acca-4d4c-9a52-8fdc2a1cfa51" />

The next step was to save my SolidWorks file as an STL file and import it into PrusaSlicer. When I did this, though, it imported vertically, so I needed to rotate it so I could make it flat on the plate to print properly. I quickly ran into a problem, though, because I could not find a way to set an exact angle of rotation to make it flat. I then started experimenting with buttons and found one that is labeled "place on face". I hit this and selected the flat part of the cracker, and it automatically aligned my design with the plate.

<img width="959" height="440" alt="image" src="https://github.com/user-attachments/assets/87f8a6e7-3379-45ca-9311-66906b70ef5d" />

<img width="362" height="116" alt="image" src="https://github.com/user-attachments/assets/8b864be6-3f4e-447c-93f2-8d4ccf005f75" />

Now it's time to slice my print and decide on an infill percentage and pattern. The default infill is 15%, but I chose to go down to 10% because I want it to be realistic, and less infill will make it weaker and more brittle. I also chose to go with a lighting pattern because it is one of the quickest and most efficient patterns, but it is also very brittle under lateral or vertical stress.

## Research


## Preprocessor and Printing


## Print

## Lessons Learned

