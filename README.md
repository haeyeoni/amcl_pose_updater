# amcl_pose_updater
This is modified version of [amcl ros package](https://github.com/ros-planning/navigation). 
We added amcl pose updater that updates amcl_pose and the particle states when known-pose flag is detected.

### Download
```
cd ~/leo_ws/src
git clone https://github.com/haeyeoni/amcl_pose_updater
cd ~/leo_ws
catkin_make
```

### Usage:
Run amcl_pose_updater node
```
roslaunch amcl_pose_updater amcl_diff.launch 
```
When you want to update pose with new known pose (fixed covariance)
```
rosservice call /pose_update  new_x new_y new_theta
```
