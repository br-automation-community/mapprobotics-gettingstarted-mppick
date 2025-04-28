# AS Help - Getting Started with MpPick

## Description

This project provides an easy Getting Started for testing a pick-and-place application with a delta robot.

The task involves automatically picking up chaotically arranged objects from one location (e.g., a moving conveyor belt) and placing them in an orderly manner at another location (also a moving conveyor belt). The objects can vary by product type, and the requirements may include sorting by properties such as color, weight, or other characteristics.

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

### Getting Started

For the most efficient and straightforward implementation of the "Getting Started" tutorial for pick-and-place, a pre-configured project is provided. This project can be started directly from Automation Studio project and started with just a few additional steps.

The prepared project includes:

- Virtual axes for the delta robot
- Virtual axes for the two conveyor belts

This eliminates the need to add drive modules, simplifying the setup process.