# Clone Repo in `workspace/src` directory

```
git clone https://github.com/htil/turtlebot3-boiler-plate
```

# cd to workspace

```
cd ~/ros_ws
```

# Build Project 

```
colcon build --symlink-install --packages-select auto_turtle
```

# Source Project

```
source install/setup.bash
```

# Install apriltag_msg package

```
sudo apt install ros-humble-apriltag-msgs
```

# Launch Project

```
ros2 launch auto_turtle auto_turtle_launch.py 
```