# Getting Started - mapp Robotics MpPick Process Solution

This Automation Studio project accompanies the [MpPick](https://help.br-automation.com/#/en/6/motion/mapp_motion/mapp_robotics/programmierung/lib/pick/pick_.html) Getting Started section from Automation Help. The Getting Started section explains the steps for configuring a pick-and-place application using the mapp Robotics MpPick process solution. The configuration consists of one delta robot and two conveyor belts. In this application, a delta robot of the type Codian D4-ST21-1100-R11 is used and inserted via the Specific Robots Assistant.

The task involves automatically picking up chaotically arranged objects from one location (e.g., a moving conveyor belt) and placing them in an orderly manner at another location (also a moving conveyor belt). The objects can vary by product type, and the requirements may include sorting by properties such as color, weight, or other characteristics.

<img width="1304" height="938" alt="MpPick Scene" src="https://github.com/user-attachments/assets/e3c68013-4ba7-416c-ad8e-373bbf6bd18e" />

## How to run the application

0. Activate ArSim
1. "Offline commission"
2. Open global Watch window or Watch window for any other task
3. Add 'CmdStart' process variable 
4. Open the automatically generated scene from the Logical View PickAndPlace/Scene: 'ObjectHierarchy.scn'
5. Connect SceneViewer via OPC-UA (Username: User, Password: MpPick)
6. Set the 'CmdStart' variable to TRUE

![image](https://github.com/user-attachments/assets/18624cdf-c7f3-4b00-b2c4-23d2cc294c08)
