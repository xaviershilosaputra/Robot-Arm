# Robot-Arm
DIY 3D printed Arduino robot arm.

## Description
This is a DIY 3D printed robot arm project that I created to help me pick up items on my desk. It uses an Arduino UNO microcontroller, a PCA9685 servo driver, and several MG995 servos for movement. 

## Why I created this project
I created this DIY 3D printed robot arm project to learn more about Hardware and Electronics to complement my existing coding and software development skills. I have always wanted to build cool projects like Legos or other DIY projects, but never have the courage or facility to learn about hardware and electronics. Through this Fallout Project, I wanted to dive deeper into electronics and go crazy to make an ambitious project to make full use of the facility and support given to me. I hope to continue making other cool projects in the future (I already had plans to make other robots or tools such as a dog or flying robots, and this project will hopefully prepare me to make even more usefull or ambitious projects in the future).

## What I learned
Through this robot arm project, I aim to learn about CAD, making a wiring diagram, robotics, embedded systems, microcontrollers, and microcontroller coding. Even in this early stages (this was written before designing or assembling the project) I have already learned how to create a good readme, how to search for electronics parts (and their datasheets), and actually reading a component datasheet. 

## Aim
The robot arm must be able to achieve the following task:
- Pick up stationaries and light to medium desktop items.
- Be modular and upgradable for future improvements.
- Maintain a compact footprint such that it doesn't take up too much desk space.

## Future Upgrades
- Add camera module and smart image detection
- Add wireless control using a desktop or mobile app
- Add a master and slave system to easily control the robot
- Upscale the design to a larger size with nema stepper motors instead of servos for higher load capacity. 
- Create several different size variants using multiple servo options such as the SG90/MG90S or the DS3135MG for lighter or heavier load handling.

## Bill of Materials (BOM)

| No. | Category            | Item                         | Qty | Est. Price (USD) | Description / Notes                                  | Link |
|-----|---------------------|------------------------------|-----|------------------|------------------------------------------------------|------|
| 1   | Controller          | Arduino Uno                  | 1   | Est.             | Main microcontroller for controlling the robot arm   | |
| 2   | Servo Control       | PCA9685 PWM Servo Driver     | 1   | Est.             | 16-channel PWM driver for controlling multiple servos | |
| 3   | Power               | 5V 5–10A DC Power Supply     | 1   | Est.             | External power source for servos                     | |
| 4   | Servo Motor         | MG995 High Torque Servo      | 8   | Est.             | Used for all joints and gripper                      | |
| 5   | Mechanical Parts    | 3D Printed Arm Components    | 1 set | Est.           | Includes base, arm segments, wrist, and gripper      | |
| 6   | Mechanical Parts    | Servo Horns                  | 2   | Est.             | Servo arms for mounting and motion transfer          | |
| 7   | Wiring              | Wire                         | 1 set | Est.           | Connections between Arduino, driver, and servos      | |
| 8   | Wiring              | Servo Extension Cables       | 1–2 | Est.             | Extends servo wiring to controller board             | |
| 9   | Fasteners           | Assorted Screws & Bolts (M2/M3) | 1 set | Est.         | For mounting servos and structural parts             | |
| 10  | Fasteners           | Heat-set Threaded Inserts    | 6–10 | Est.           | For durable threaded mounts in 3D printed parts      | |
| 11  | Consumables         | PLA or PETG Filament         | 1   | Est.            | Material for printing robot arm components           | |
| 12  | Assembly            | Solder Wire                  | 1   | Est.             | Used for soldering electronic connections            | |
| 13  | Assembly            | Flux                         | 1   | Est.             | Helps improve solder joint quality                   | |

Total: Est.
