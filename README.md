# AMR_ROS
the following package contains the URDF description of mobile robot created as Autonomus mobile robots course project.

the Robot simulates some of the mobile robots algorithms like obstacle avoidence and go to goal (the available algorithms are located in /scripts directory).

# Demo Video
[![Watch Video](https://i.imgur.com/zctsYZF.png)](https://www.youtube.com/watch?v=ThAjbMSuvAo)

# how to use 
`cd catkin_ws/src/m2wr_description`

`git pull https://github.com/HemaZ/AMR_ROS.git`

`cd ..`

`catkin_make`

`roslaunch m2wr_description spawn.launch`

`rosrun gazebo_ros gazebo`

`rosrun m2wr_description obstacle_avoidance.py`

change the algorithm name in the above command to simulate different algorithm.


