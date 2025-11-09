# UGV Control

<p style="text-align: justify;">
The robot can also be controlled directly from the PC using keyboard input. This allows the operator to manually navigate or adjust the robot’s position in real time, providing an intuitive and straightforward way to interact with the system during testing or demonstration.
</p>
### Steps

<p style="text-align: justify;">
Inside the folder `my_robot_description`, open two terminal windows.
In the first terminal, execute the following commands:
</p>
```
source install/setup.bash
```
after

```
ros2 launch my_robot_bringup my_robot_gazebo.launch.xml 
```

Then, in the second terminal, run:

```
source install/setup.bash
```
after

```
ros2 run teleop_twist_keyboard teleop_twist_keyboard 
```
<p align="center">
  <img src="../../assets/5.gif" alt="Robot demo" width="700"/>
</p>