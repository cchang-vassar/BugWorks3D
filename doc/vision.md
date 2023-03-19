# Vision Document
## High Level Description
A 3D simulator for Braitenberg vehicles in custom arenas. Users are able to design the internal configuration of their vehicles using a drag-and-drop interface, with pre-built vehicle componenets available for users to plug and play. The user can also design their own environments to simulate the vehicles in, with basic features including the number of light sources in the environment, obstacles and their positions, etc. The cumulative movement trajectories of the vehicles can be tracked as the simulations are run, and a visual recording of the simulation can also be downloaded afterward.

## Main Features
1.  A drag-and-drop UI for building Braitenberg vehicles
    * Packaged vehicle components
    * [stretch] separate vehicle component builder
2.  A drag-and-drop UI for building custom environments
3.  A simulation UI for running the vehicles in environments
    * A 2D bird's eye view of environment
    * A 3D angled bird's eye view of environment
    * [stretch] multiple custom camera angles to follow the vehicle(s) with (e.g. first-person)
4.  Toggle on/off 2D and 3D view
5.  Recordings of simulation
    * 2D bird's eye view
    * 3D angled bird's eye view
    * [stretch] from multiple custom camera angles

## Requirements
## Target Audience
1. Students learning Braitenberg concepts
2. Teachers teaching Braitenberg concepts
3. [stretch] Advanced users who want to design and test complex agent-environment interactions

## Value Proposition
*  Provide physically realistic tool for modelling and simulating agent-environment interactions
*  User can design, test, understand and explore unlimited configurations of vehicles and environments
*  Researchers can use tool to inspire better autonomous vehicle designs

## Constraints
*  System architecture must be scalable: lots of flexibility in future development
*  UI must be intuitive but also capable of handling wide range of possible inputs and future development
*  Handle wide range of possible user actions, especially in customization

## List of goals for each actor
|  Actor       |  Type of Actor     |  Goal                                                               |
|--------------|--------------------|---------------------------------------------------------------------|
|  Student     |  Primary           |  Learn Braitenberg concepts                                         |
|  Teacher     |  Primary           |  Have easy to use tool to teach Braitenberg concepts                |
|  Researcher  |  Primary           |  Simulate complex agent-environment interactions and gather data    |
