# ros2

This role installs [ROS 2](http://www.ros2.org/) following [this page](https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html).  
Also, it installs development tools following [this page](https://docs.ros.org/en/galactic/Installation/Ubuntu-Development-Setup.html).

## Inputs

| Name              | Required | Description                                      |
| ----------------- | -------- | ------------------------------------------------ |
| rosdistro         | true     | ROS distro.                                      |
| installation_type | false    | The installation type (`desktop` or `ros-base`). |
