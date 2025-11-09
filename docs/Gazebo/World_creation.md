# World creation

### Install Gazebo 
1. Open the terminal and type:

```
sudo apt install ros-humble-gazebo-*
```

  Close and reopen the terminal
   
### Gazibo world

2. To launch it, type gazebo.
In Insert, there’s Add Path.
At http://models.gazebosim.org/
 you can find ready-made Gazebo models.

3. To create walls: Edit → Building Editor.
Draw the walls, and to save: File → Save As (Ctrl+Shift+S) → enter the name and where to save → Save → Exit (in the next window).

4. To save the world: File → Save World As → enter the name (name.world) and location → Save.

To open the world you created, you need to be in the folder where you saved it
(hercules@hercules:~/gazebo_examples$)
and type in the terminal:

```
gazebo (name.world)
```

 <div style="text-align:center;">
    <img src="../../assets/4.png" alt="Robot demo" width="700"/>
</div>
