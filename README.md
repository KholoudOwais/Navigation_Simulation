# Navigation_Simulation

## Steps
1. Launch Simulation World
  - `$ export TURTLEBOT3_MODEL=burger`
  - `$ roslaunch turtlebot3_gazebo turtlebot3_world.launch`
  
2. Run Navigation Node
  - `$ export TURTLEBOT3_MODEL=burger`
  - `$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml`
  
3. Estimate Initial Pose
  - Click the `2D Pose Estimate button` in the RViz menu.
  - Click on the map where the actual robot is located and drag the large green arrow toward the direction where the robot is facing.

4. Set Navigation Goal
  - Click the `2D Nav Goal button` in the RViz menu.
  - Click on the map to set the destination of the robot and drag the green arrow toward the direction where the robot will be facing.

## Result

<img src = 'Screenshot from 2021-07-10 18-43-14.png'>
