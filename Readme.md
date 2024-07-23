# Pick and Place operation using Franka Emika Panda Robot

## Description
This repository contains the code for controlling the Franka Emika Panda Robot to execute pick and place operations using Moveit2 

## Author
- Name: Swaraj Mundruppady Rao

## Requirements
- MoveIt library
- ROS2 Humble 
- Follow this link for Moveit Installation : https://moveit.picknik.ai/humble/doc/tutorials/getting_started/getting_started.html#download-source-code-of-moveit-and-the-tutorials


## Steps to Run the Package 
1.  Download the package and paste it inside the src folder and build the package using colcon build
2. Open two terminal windows and source them 
3. Run the following command in the terminal :
```bash
    ros2 launch moveit2_tutorials demo.launch.py
```

5. Disable Query Goal Pose in RViz 
6. Run the following command to see the robot move and perform the required movements:
   ```bash
      ros2 run swaraj_120127007 swaraj_120127007
   ```
8. The terminal window will show the movement being performed and will also show what movement is being carried out.


## Link to Github : https://github.com/SwarajMundruppadyRao/Moveit2-Franka-Emika-
