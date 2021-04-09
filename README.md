# amcl_pose_updater
This is modified version of amcl ros package. 
We added amcl pose updater that updates amcl_pose and the particle states when known-pose flag is detected.

Usage:
```
rosservice call /pose_update  new_x new_y new_theta
```
