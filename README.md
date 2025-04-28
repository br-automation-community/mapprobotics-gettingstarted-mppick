# AS Help - Getting Started with MpPick

## Description

This project provides an easy Getting Started for testing a pick-and-place application with a delta robot.

The task involves automatically picking up chaotically arranged objects from one location (e.g., a moving conveyor belt) and placing them in an orderly manner at another location (also a moving conveyor belt). The objects can vary by product type, and the requirements may include sorting by properties such as color, weight, or other characteristics.

![image](https://github.com/user-attachments/assets/63105026-6842-4580-b3fe-3504cc6079cb)


### Application Options

The pick-and-place application can be used for:

- Packaging
- Continuous sorting of objects
- Reordering while moving
- Handling scrap from a chaotic arrangement
- Other similar tasks

### Requirements

- In simulation, Scene Viewer is recommended – the scene is either created automatically or obtained from GettingStartedHelper. The required connection login is **Username: User / Password: MpPick**
- The basics of coordinate systems are known.
- The basics for a customized frame hierarchy are known.
- "Getting started" tutorials are designed for simulation – describing adjustments to hardware or adapting to one's own hardware.
- Required licenses must be available depending on hardware and software components used (see Licensing).
- For real hardware, the transfer method must be taken into account according to the download behavior of the mapp Technology concept.

### Getting Started special implementation

For the most efficient and straightforward implementation of the "Getting Started" tutorial for pick-and-place, a pre-configured project is provided. This project can be started directly from Automation Studio project and started with just a few additional steps.

The prepared project includes:

- Virtual axes for the delta robot
- Virtual axes for the two conveyor belts

This eliminates the need to add drive modules, simplifying the setup process.

### Running and testing the application

The program can be tested using the Watch window and diagnostics functions.

The interface of the mapp function block in the Watch window can be used to enable commands such as switching on (Power) and homing (Home) as well as the movement (MoveXxx) or program (MoveProgram).

Additional functionalities are available in section Diagnostic functions.

The command starts the motion sequence of the pick-and-place system, and the ReadyXxx variables provide information about which program is working and has been prepared.
If an error occurs, the state of variable Ready changes from TRUE to FALSE.
For additional information, see the respective program on the function block outputs.

![image](https://github.com/user-attachments/assets/18624cdf-c7f3-4b00-b2c4-23d2cc294c08)

Tip: Changing the speed of the conveyor belts (PickConveyor) best shows how the PickCore solution works.
