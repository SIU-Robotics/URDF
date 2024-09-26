# URDF
Figuring out the digital design for the robot.
Use Xacro only. We do not have a way to auto generate urdf outside of xacro.

ros2 launch urdf_tutorial display.launch.py model:=$(pwd)/frame.xacro
^^Why does this work?^^