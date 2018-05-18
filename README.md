# FCND - Backyard Flyer Project
This project has three required criteria for an event driven Phython application. 

1. Completion of the classes arming_transition(), takeoff_transition(), waypoint_transition(), landing_transition(), and disarming_transition() where each of the command methods are filled in with an appropriate command(s) to the vehicle and transitions to the respective state in the state machine.

2. Setup state based transitions. Each of the command methods are filled in with an appropriate command(s) to the vehicle and transitions to the respective state in the state machine.  The callbacks check appropriate criteria dependent on the current state and transition to the appropriate next state when that criteria is met. Criteria cannot be time based.

3. Running the backyard_flyer.py script correctly commands the vehicle to fly in a square. The vehicle should fly in a square shape and land within 1m of the starting location. The size of each side of the square can will be 12 meters.

4. Using the log data to plot the altitude, velocity, or heading to better understand the drone's behavior (Optional). 

==================

My first apporach to the specs and criteria is to manually fly the following in the simulator. 

1. Arm controller
2. Takeoff to 6 meters high
3. Transtion to first waypoint 12 meters to the West
4. Transition to the second waypoint 12 meters to the South
5. Transition to the third waypoint 12 meters to the East
6. Transition to the final waypoint 12 meters to the North
7. Landing transition 
8. Disarm the controller

My second apprach to the specis and criteria is to code the Backyard flyer to perform the eight transitions.  

My third apporach to is to incorporate log data into visuals to improve the accuracy of the apporach.  


```






