# Arm Control

<p style="text-align: justify;">
I have developed a code that allows me to control the joints of the robotic arm. Through this implementation, each joint can be individually adjusted, enabling precise manipulation of the arm’s position and orientation. This functionality is essential for performing tasks such as object handling, image acquisition, or calibration within the robotic system.
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
python3 arm_control2.py
```

<p align="center">
  <img src="../../assets/4.gif" alt="Robot demo" width="700"/>
</p>