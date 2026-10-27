# A9 – Laser cutting

## Objective

## Step 1- Measure the Material
- Measure your sheet with calipers at a minimum of 3 locations.

- Record each value and the mean. Use the mean as your thickness variable.

### Thickness Measurements 
Measurement 1= 3.08mm  Measurement 2= 2.98mm Measurement 3= 2.91mm Average thickness= 2.96mm

## Step 2- Measure The Kerf 

We decided to make our section 25.4mm by 25.4mm because that is equivalent to 1in, so it will be easy to calculate using specific measurements. 

We made a mistake with our first cut and didn't change the settings from engrave to off, so it would cut all the way through the material. 

<img width="263" height="318" alt="{22D0EAC4-F8E5-49AF-AD84-9A2A6684F53F}" src="https://github.com/user-attachments/assets/599a66fa-8dd2-4737-a7c3-4c603335de49" />

<img width="351" height="388" alt="{605A79B2-9480-4B9D-B683-B0E21EEEFA82}" src="https://github.com/user-attachments/assets/56de63c5-2e57-47c4-8e24-b88f96b8ba0e" />

<img width="800" height="1422" alt="ezgif com-optimize" src="https://github.com/user-attachments/assets/9d5b7d9b-e585-4030-9bd6-8d63bc195cf5" />

After cutting the second time, I measured the width with a vernier caliper and got .993in by .993in. 1in - .993in = .007in or .1778mm kerf.

## Step 3- Run a Fit Test
- Design a fit coupon with one tab and 3 slots at 3 different clearances (tight, target, loose), based on your measured thickness and kerf.

- Cut and test it. Rate each fit and photograph the results.

<img width="514" height="275" alt="image" src="https://github.com/user-attachments/assets/99e61952-6327-4d9c-8875-ef1dd5688f22" />

<img width="516" height="275" alt="image" src="https://github.com/user-attachments/assets/e6fab20f-3ec7-44ad-96e8-0fbe6d640dfe" />

<img width="512" height="272" alt="image" src="https://github.com/user-attachments/assets/df766fac-2fcc-417a-bd33-7649b5ac163f" />

When designing for a test fit, there are a lot of variables to take into account revolving around kerf. One is the average thickness. The supposed thickness of the wood is 3mm, but we measured the average thickness to be 2.96mm. So, our goal target fitment should be somewhere less than 2.96 because we want it to be an interference fit so it is snug and doesn't move naturally, but we can still force it into place. A good start to the desired clearance would be 2.7822mm, which is average thickness minus the kerf in millimeters
So we made a design with a few different slots to test which clearance would fit our wants the best. We then made a simple square that will act as a key in these slots and will slide into place, and we will determine which dimension we like best based on how easily or how hard it is for the key to move. 


## Step 4- Choose a Clearance
- Select the clearance that gives the most reliable fit, and explain why.

- Enter it in your Parameter Table (below). Your final CAD must use this value.

After running a test fit we decided to go with the smallest dimensions we cut because it had the best support while standing still, while still being able to insert the key piece and move it with using some force. This dimension was 2.55mm before kerf and 2.3722mm after kerf. 

## Brainstorming

<img width="926" height="779" alt="image" src="https://github.com/user-attachments/assets/5b2f888d-bf38-476f-9622-bd4f718d6775" />


## SolidWorks Model and Inkscape

<img width="296" height="271" alt="image" src="https://github.com/user-attachments/assets/ed4a86b4-01df-484c-bc21-a35b078c4228" />

Here is the wheel design I made based on an actual Cybertruck. I had some struggles when modeling this since everything has to stay in a 2d plane and not extrude it into a 3d shape. This is vastly different from what I'm used to in 3d printing, where we make full 3d shaped and models to be printed as a whole. With this project, laser cutting has to be done on a 2d plane, and each section is layered on top of each other, and later in Inkscape we will differentiate which shapes are engraved to give definition and depth and what is fully cut out. Layering each piece on top of each other gets complicated when adding a lot of details on one sketch. 

For the design itself, I did a simple 30mm diameter circle and sketched multiple polygon shapes onto it. I used a multitude of centerlines, mirror entities, and circular patterns to have this come out as the final product. I also did a rectangular cut in the center for the axle that will be cut on the base of the car. 

<img width="949" height="440" alt="image" src="https://github.com/user-attachments/assets/5d171c9a-6c54-451c-a0c1-14812ec574f7" />

<img width="217" height="201" alt="image" src="https://github.com/user-attachments/assets/f83124f3-6dae-43e3-9188-39c602e22cca" />

Here are the four wheels inside Inkscape before printing. The red is what is to be engraved, and the black is what is to be cut through. To have the red filled in, I ran into some issues. When importing a sketch from SolidWorks into Inkscape, it didn't recognize the shapes as a full shape but each line segment as its own piece. So I had to rework all the shapes into fully enclosed shapes in Inkscape and then trace them using the spline pen and manually color in each part. 
## Cutting

<img width="682" height="259" alt="image" src="https://github.com/user-attachments/assets/da34b77d-1286-45fe-836a-affed3c81f60" />

<img width="368" height="87" alt="image" src="https://github.com/user-attachments/assets/f84bb1d2-c508-4111-a483-ad3743821dbd" />

<img width="225" height="324" alt="image" src="https://github.com/user-attachments/assets/300c7e71-ffa3-4996-a66a-d845aae4e148" />

To cut the wheels out it took about 3 and a half minutes. I autoset the speed and power settings to what the laser has pre set for cutting wood at 3mm.

## Final product

<img width="263" height="347" alt="image" src="https://github.com/user-attachments/assets/e807e073-3de4-4e34-aab7-440789abb31b" />

<img width="251" height="335" alt="image" src="https://github.com/user-attachments/assets/ec220da0-c847-4cc6-9341-c41e92091440" />

<img width="249" height="326" alt="image" src="https://github.com/user-attachments/assets/b39086bb-cf9a-46d4-bba6-bd1814480d44" />

## Lessons Learned

