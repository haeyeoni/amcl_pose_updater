# amcl_pose_updater
This is modified version of amcl ros package. 
We added amcl pose updater that updates amcl_pose and the particle states when known-pose flag is detected.

Usage:
```
rosservice call /global_localization  0 0 0
```
