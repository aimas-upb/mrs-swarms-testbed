# mrs-swarms-testbed

## How to Use
This package depends on following packages:  
`sudo apt install ros-melodic-turtlebot*`  
`sudo apt install ros-melodic-teleop-twist-keyboard` 

For launching, in one terminal:  
`roslaunch swarm-testbed simulation.launch`  
To command the robots, open another terminal and run:  
`rosrun teleop_twist_keyboard teleop_twist_keyboard.py /cmd_vel:=/robot{N}/cmd_vel`  
where N={1,2}, depending on the robot you want to command.



