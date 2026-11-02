# A10 – RC 2 Sliding Fit Design and Verification

## Objective
In this assignment, we are going to learn and explore using resin (SLA) printers to create an RC 2 sliding fit design. This will require making multiple parts that will slide together, such as a hole/slot feature and a matching shaft/insert feature to demonstrate the fit. 

Here is the objective list from the assignment. 

- Research the RC 2 fit specification from the Machinery’s Handbook.

- Measure your printed features (hole/slot and shaft/feature) using calipers.

- Show your printed part set in class to verify the fit and documentation.

- Total volume of the two parts may not exceed 20mL including supports.



## RC 2 Fit research

What is an RC 2 fit? RC stands for running or sliding fit. This means that you have two objects, maybe a hole and a shaft, that slide and fit together with a certain tolerance. The 2 stands for the amount of tolerance allowed within the fit. There are RC 1, RC 2, RC 3, etc and the higher the number means the less tolerance for wiggly room in the fit. SO a 2 is slightly more than 1 but slightly less than three. We know about the kinds of fits being loose, close, and interference, and 2 is in the close category, meaning there is room for it to move but should be relatively tight. So, when designing, we are looking to make something that will slide together smoothly while staying aligned and tight. There is no allowable value for this fit because it depends on the nominal value of the size we choose. So, whenever I make my model, I will have to calculate the clearance based on the size of the hole I make. 

## What is SLA Resin Printing

With this being my first time seeing and using an SLA resin printer, I wanted to do some research on what it is and how it works. Instead of plastic 3D filament, SLA printers use a liquid resin that dries when hit with a certain light. The printer aligns its build platform inside the resin, then a laser or light source will dry the resin into solid plastic in specific spots, layer by layer. When printing is finished, the object isn't completely done yet and will normally need a chemical wash to clean off all the excess resin, as well as a curing stage for it to fully take on its physical properties. This curing process should be taken into account when designing because it can cause minor changes to dimensions. 

## Planning and Brainstorming

For my brainstorming, I had to think of what needs to be able to move and slide freely while also being precise in those movements. What came to mind was measuring tools. Most tools, like a tape measure, can move in their respective ways, but they're also precise about how much and where they move. But a tape measure isn't a sliding fit, so what could be? Then I thought of a depth meter I've used previously at home. It slides up and down to measure the depth of a hole while still being precise in its movement nd not falling all over the place. The problem is most of those aren't cylindrical, so I'm going to somehow make mine a cylindrical sliding mechanism. 

## CAD Modeling

<img width="244" height="264" alt="image" src="https://github.com/user-attachments/assets/0a4cde30-eeb7-49d7-94db-46636e2882d5" />

I started by making the base or body that will go around the shaft/cylindrical rod.

<img width="357" height="273" alt="image" src="https://github.com/user-attachments/assets/d559faf4-e897-41b5-b568-93507313d48d" />

Then I extruded it to a thickness of .15in and added drafts to the end at a 45-degree angle to make it look more unique and not so boxy. I chose .15in because I want the hole and shaft to be .10in thick; this gives me working room and space after it shrinks from curing. 

<img width="487" height="268" alt="image" src="https://github.com/user-attachments/assets/b001e98d-8901-45b6-88bd-7fa787a25b77" />

Next, I extrude-cut the shaft hole with an original diameter of .10in through the whole body, but I changed it to 1.02in after remembering I have to account for the shrinking of the resin.

<img width="807" height="371" alt="image" src="https://github.com/user-attachments/assets/cef009a2-787d-4feb-8876-962eb03b7055" />

I then wanted to shave off the top material so I could later engrave measurements on the side pieces beside where the shaft will go.

<img width="773" height="325" alt="image" src="https://github.com/user-attachments/assets/dd8d24d9-db36-431f-99cc-2c5dc5b2e81e" />

I wanted to add a little more detail to the shape of the body, so I added a chamfer to the corners of the drafts to angle the whole arm on both sides, not just the tip end of it. 

