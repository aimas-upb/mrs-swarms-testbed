# mrs-swarms-testbed

This repository presents an evaluation of the multi-robot swarm testbed in classical Gazebo. The objective is to explore the feasibility, design needs, and challenges in simulating swarm robotics within Gazebo's traditional simulation framework.

## How to Use
This package depends on following packages:  
`sudo apt install ros-melodic-turtlebot3*`  
`sudo apt install ros-melodic-teleop-twist-keyboard` 

For launching, in one terminal:  
`roslaunch swarm-testbed simulation.launch`  
To command the robots, open another terminal and run:  
`rosrun teleop_twist_keyboard teleop_twist_keyboard.py /cmd_vel:=/robot{N}/cmd_vel`  
where N={1,2}, depending on the robot you want to command.


## Acknowledgement

<p>
    <img src="./acknowledgement/logo-digitwins.png" alt="Digital Twin Logo" width="100" style="vertical-align: middle; margin-right: 10px;">
    This work was partially supported by the <a href="https://www.digitwin4ciue.eu/">DIGITWIN4CIUE</a> project of the European Union’s Digital Europe Programme under grant agreement No. 101084054.
</p>

