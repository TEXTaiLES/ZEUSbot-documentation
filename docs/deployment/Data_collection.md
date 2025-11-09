# Data Collection

<p style="text-align: justify;">
The robot maintains a stable distance from the object of interest to ensure optimal visibility and positioning. Using a robotic arm, the camera is moved to multiple viewpoints around the object, capturing images from different angles. This multi-perspective acquisition allows for better coverage and enhances the accuracy of the 3D reconstruction process.
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
ros2 run robot_controller go_with_arm
```

<p align="center">
  <img src="../../assets/3.gif" alt="Robot demo" width="700"/>
</p>

