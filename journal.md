---
title: "undecided"
author: "@scalar"
description: "jack of all trades, autonomous drone!"
created_at: "2025-06-16"
---

# July 5th - Spent 6 hours researching
Requirements:
- Needs to have a polished appearance (plastic shell with lights, speakers) (difficult)
- Solid attachment points for payloads
- Attachment types: String based attachment, Package release mechanism. 
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


# July 30th- Spent 7 hours designing the frame of the drone. 

After working on the drone for a while, it is finally starting to look like what I wanted the final product to look like. I have made it into a modular design- the arms individually screw into the body but lock into place using the other arms as support. This should hopefully result in a pretty solid but repairable body design. Other than that, I also made the flight controller/ power distribution board holder body in the center. Next, I will edit the frame a little more to add support to the frame arms. 
