---
title: "undecided"
author: "@scalar"
description: "jack of all trades, autonomous drone!"
created_at: "2025-06-16"
---
# Total time spent- 28 hours

## IMPORTANT: the drone will now be a 5 inch drone due to cost issues, and will only carry very small packages, as a proof of concept of a package deliver drone


# July 5th - Spent 6 hours researching
Requirements:
- Needs to have a polished appearance (plastic shell with lights, speakers) (difficult)
- Solid attachment points for payloads
- Gimbal to carry thermal OR regular camera. (easy)

Optimal Drone parameters (i think):
Size: 350 to 400 mm. 
- Total weight: less than 1.3 KG 
- Battery: 8000-10000 mAh LiPo
- Motors: 400–500 KV brushless
- Propellers: 10–12” carbon fiber
- Estimated flight time: 25-30 minutes. 

Supplies:
- Going to need a flight controller that can operate over CAN bus (around 100 dollars)
- GNSS
- Already have PETG for printing the frame.

# July 6th- Brainstorming Frame design- 3 hours

Frame Characteristics:
- Quadcopter design
- Reinforced X-Shape (good camera view)

Now although this may be somewhat unrealistic, I want the drone to look polished by the end, so I will aim to have the body/shell of the drone resemble the DJI Matrice 4 series. 

<img width="575" height="242" alt="image" src="https://github.com/user-attachments/assets/fd6dfd5a-6607-4012-904b-2f1e3bfcd1ea" />

-
I also finished a rough sketch of the drone in Fusion:


<img width="752" height="599" alt="image" src="https://github.com/user-attachments/assets/1f5c489b-e419-4fde-8441-0d07cadb240c" />

# July 27th- Spent 4 hours re-planning project goals

I was kinda confused on my project goals so I took some time researching what I could actually do with the skills I have and the funding I can get. I decided that there are 3 main areas where I will spend my time in this project.

1. The frame of the drone. 
- It is essential that the frame is sturdy and able to withstand crashes.

2. LED boards. 
- Since most telemetry is handled by the flight controller, I will work on some LED lighting boards so that I can get some PCB development done too. 
- I want status leds similar to the Skydio 2 drone
- I may also make a floodlight system as an attachment (multipurpose drone)

3. Motorized package release mechanism. 
- Need to design a way to release packages while keeping them in position during flight. 
- Should have a way to release packages while in the air


# July 30th- Spent 8 hours designing the frame of the drone. 

After working on the drone for a while, it is finally starting to look like what I wanted the final product to look like. I have made it into a modular design- the arms individually screw into the body but lock into place using the other arms as support. This should hopefully result in a pretty solid but repairable body design. Other than that, I also made the flight controller/ power distribution board holder body in the center. Next, I will edit the frame a little more to add support to the frame arms. 


<img width="1531" height="619" alt="Screenshot 2025-07-31 064636" src="https://github.com/user-attachments/assets/6564c92c-4a21-43d0-a941-9716408fa84f" />
<img width="828" height="517" alt="Screenshot 2025-07-31 081405" src="https://github.com/user-attachments/assets/c7d1ff3c-36e0-4183-a8a2-4ce7959ac3d8" />

Ok, now this looks much more stable. 

<img width="1217" height="508" alt="image" src="https://github.com/user-attachments/assets/b93407c3-ef20-4fdb-96c8-7002c0a89366" />

# July 31st- Spent 2 hours making LED PCB
Researched some information about making extension boards for flight controllers. It turns out that most flight controllers have a dedicated led output pin that I can use. After researching/planning the led board, I made a quick schematic and PCB design, I was able to complete it quite fast because I am now kinda experienced with sk6812 led applications.
<img width="911" height="406" alt="image" src="https://github.com/user-attachments/assets/44a9dfb6-a581-49fb-8065-00aa34ad1f38" />

# July 31st- Spent 3 hours making legs, release mechanims.

After much research, I decided the best way to secure a package would be by adding a detachable package securing base that has slots for straps that could be used to hold a package. The package can be pretty sizable too- at around 16x16 cm. I also made detachable/replacable legs that can be screwed into the body individually, although I may decide to remove this in the end for noise reduction. 

<img width="1100" height="506" alt="image" src="https://github.com/user-attachments/assets/7964aeba-76fc-44af-9eca-0575160a937c" />

With that, I think I will conclude the project and begin the process of submitting it. 

<img width="1209" height="538" alt="image" src="https://github.com/user-attachments/assets/8b06e86d-6827-44e4-bf74-d46640f19333" />

# August 16th- spent 3 hours fixing model. 

It turns out that my drone is way too big and may not work if printed. I have decided to print the drone in PETG for strength and have made the frame smaller so that there isnt a risk of the frame snapping. **Therefore, the drone will now be a 5 inch drone due to cost issues, and will only carry very small packages, as a proof of concept of a package deliver drone**. 

I aim to make the drone similar to something like this image: 
<img width="1001" height="1001" alt="image" src="https://github.com/user-attachments/assets/f7eb5242-1e92-4e7d-aef4-369bcab0ba51" />

First of all, I changed the drone's design to be more sturdy by widening the connections to the middle frame and making them shorter, decreasing the load. **I will now be printing it in PETG or maybe a harder/stronger filament**. 
Next, I updated the BOM to more accurate components and actually used built examples from articles and youtube to research some of my parts, and verify they will work on a 5 inch drone. 

This is what the drone looks like now: <img width="876" height="467" alt="image" src="https://github.com/user-attachments/assets/56379794-972d-4aea-831c-56089f7d9156" />

