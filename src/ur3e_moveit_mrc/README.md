# This package is intended to launch MoveIt functionality and start RViz for UR3e arm

To start MoveIt:

```bash
roslaunch ur3e_moveit_mrc ur3e_moveit.launch
```
To disable the back wall obstacle, add `spawn_wall:=false` to the end of the command