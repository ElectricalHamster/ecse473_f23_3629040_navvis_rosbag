# ECSE473_f23_jxc2077_navvis_rosbag
## Introduction
This package is built for **Lab#3**  in ECSE 473 at CWRU.
## Instructions
One Launch file is included within the lackage. This file has two different arguments:
- **use_xacro_new**: when true, it gives the robot new links and joints, including base_link and also enable user to see maps and sensor datas.
- **use_xacro**: this determines whether to use xacro or urdf files from the previous package: **navvis_description**. It must be true if use_xacro_new is true. 


## Note
Package navvis_description is required for this package. Both package should be placed under /src

