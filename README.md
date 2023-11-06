# pmb2_mujoco

Provides a port of the pmb2 gazebo model to mujoco_ros.

### Dependencies

Requires the following PAL forks that override default ROS packages:
- [ros_control](https://github.com/DavidPL1/ros_control_pal)
- [ros_controllers](https://github.com/pal-robotics-forks/ros_controllers) (diff_drive_controller & joint_state_controller)

Additionally requires the following repos:
- [mujoco_ros_control_pal](https://github.com/DavidPL1/mujoco_ros_control_pal) (simulated pal hardware interfaces for mujoco)
- [pmb2_simulation](https://github.com/pal-robotics/pmb2_simulation) (pmb2_controller_configuration_gazebo)
- [pmb2_robot](https://github.com/pal-robotics/pmb2_simulation) (pmb2_controller_configuration & pmb2_description)