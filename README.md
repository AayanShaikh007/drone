# Multicopter

## Goal: 
_To design a polished multipurpose drone that can carry various payloads._


## Requirements:
- Needs to have a polished appearance (plastic shell with lights, speakers) (difficult)
- Solid attachment points for payloads (difficult, see 1.) - Will require pcb design. 
- Attachment types: String based attachment, Package release mechanism. 
- Gimbal to carry thermal OR regular camera. (easy, Probably going to buy this and attach it, too complicated to make)

## Drone parameters:
Size: Medium (250-400 mm) or Large (400+ mm)

## Supplies:
- Going to need a flight controller that can operate over CAN bus (around 100 dollars)
- I like this flight controller: Pixhawk 6C Mini Model A – DroneDynamics.ca
- GNSS
- Already have PETG for printing the frame.


My interest in drones sparked when i was in Grade 4, when I saw an individual using a DJI Phantom to perform photography at a welcoming parade in Toronto. Ever since then, I was intrigued by drones and their numerous applications. Nowadays, I find it annoying that companies such as DJI are commercializing their drones, designing them to perform one purpose or task (photography, FPV, search and rescue, agriculture, etc). I agree that it is difficult or unrealistic to make a drone that can do everything, but there are some merits to it. For example, drones should at least be such that they can be used for FPV flying as well as casual photography, so that consumer waste can be reduced. 

In larger cities, road traffic is becoming a major issue. Not only is it greatly contributing to climate change, it also affects everyone who depends on the city by afflicting them with stress and potentially even physical harm (vehicle accidents). Due to this, I aim to prototype a delivery drone that could eventually be scaled up to perform deliveries of day to day essentials. 

WIth that said, I plan to make a multipurpose autonomous drone, maybe with some components I have. 

Goals
- Return to home (easy)
- Obstacle avoidance
- Auto fly and follow (hard)
- Autonomous address package delivery (special) 
- Add a mode where it goes to a set height, goes to the specific coordinates where the recipient has stated clear skies, and land. 
- For this, something resembling a DJI Dock will be required.

I officially began this project (research) today, on June 15th. I spent around 3-4 hours researching components of the drone and what I will need to buy to create the drone. Since this project will be very heavily CAD based, it will be a very good learning opportunity as well since I will be able to learn alot about CAD analysis and producing functional prints. 


# Project Gallery
<img width="1209" height="538" alt="Screenshot 2025-07-31 185143" src="https://github.com/user-attachments/assets/2ef75404-38fb-4fd5-a7f2-b8e33a69153c" />

<img width="1100" height="506" alt="Screenshot 2025-07-31 184506" src="https://github.com/user-attachments/assets/03ecb918-6500-4b7a-9549-13c578a4b678" />

<img width="828" height="517" alt="Screenshot 2025-07-31 081405" src="https://github.com/user-attachments/assets/37c2ab94-2eb4-4076-8b3e-c4851949ce8b" />

![Uploading Screenshot 2025-07-31 113120.png…]()

# BOM

| Item                   | Amount | Bought? | Cost (CAD) | Total Cost | Notes              | Link |
|------------------------|--------|---------|------------|------------|--------------------|------|
| Motors                 | 4      | n       | 17.38      | 69.52      |                    | [Link](https://www.aliexpress.com/item/1005007351717901.html?spm=a2g0o.productlist.main.1.1a32ZabUZabUfY) |
| ESC                   | 4      | n       | 6.3        | 25.2       |                    | [Link](https://www.aliexpress.com/item/1005007431507565.html?spm=a2g0o.productlist.main.1.79a3hJznhJznry) |
| Battery               | 1      | n       | 145.38     | 145.38     | (includes 2)       | [Link](https://www.aliexpress.com/item/1005004995261155.html?spm=a2g0o.productlist.main.1.60c439e7z7KGuy) |
| Radiolink FC          | 1      | n       | 31.18      | 31.18      |                    | [Link](https://www.aliexpress.com/item/1005009514369066.html?spm=a2g0o.productlist.main.11.72146403dDdVeX) |
| Power Dist. Board     | 1      | n       | 10.48      | 10.48      |                    | [Link](https://www.aliexpress.com/item/1005007472949326.html?spm=a2g0o.productlist.main.3.10b24310suD8nY) |
| Controller            | 1      | n       | 107.99     | 107.99     |                    | [Link](https://www.amazon.ca/Radiolink-T12D-Transmitter-Telemetry-Long-Range/dp/B0DB5JHSS6) |
| Propellors            | 1      | n       | 15.58      | 15.58      | includes 4 obviously | [Link](https://www.aliexpress.com/item/1005007471007910.html?spm=a2g0o.productlist.main.4.1ee12b0817sXsu) |
| M5x20 Screws          | 1      | n       | 5.2        | 5.2        |                    | [Link](https://www.aliexpress.com/item/1005004801296825.html?spm=a2g0o.productlist.main.1.5d541488qCS2BO) |
| M3x10 Screws          | 1      | n       | 4.34       | 4.34       | includes 10        | [Link](https://www.aliexpress.com/item/1005007360894545.html?spm=a2g0o.productlist.main.1.f39e5ce9wdB1FY) |
| Velcro Straps         | 8      | y       | 0          | 0          | already owned      |      |
| Double Sided Tape     | 1      | y       | 0          | 0          | already owned      |      |

|                      |        |         | CAD        | USD        |                    |
|----------------------|--------|---------|------------|------------|--------------------|
|                      |        | Total Cost | **414.87** | **299.41** |                    |
|                      |        |         |            |            | Note: 150 USD = 204.58 CAD |
