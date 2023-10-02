# ECSE473_f23_jxc2077_navvis_rosbag

## Introduction
This package is built for **Lab#3**  in ECSE 473 at CWRU.

## Instructions
One Launch file is included within the package. This file has two different arguments:
- **'use_xacro_new'**: When it's true, it will give the robot new links and joints, and it also enable user to see maps and sensor datas.
- **'use_xacro'**: It determines whether to use xacro or urdf files from the previous package: **navvis_description**. The **'use_xacro'** must be true if use_xacro_new is true. 

## Note
Package navvis_description is required for this package. Both package should be placed under /src

