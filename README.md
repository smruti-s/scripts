# Scripts

Utility scripts for Ubuntu

## Basic Install Script

After cloning the repository, please follow the steps outlined below - 

```
chmod a+x install.sh
```
The terminal will prompt you to enter your password. Enter the following command after entering your password.

```
./install.sh
```

## Other Dependencies and Tools

The `deps_install` script installs following things:

1. PX4
2. Micro XRCE DDS

It also creates a ros2 workspace. 

```
chmod a+x deps_install.sh
```
The terminal will prompt you to enter your password. Enter the following command after entering your password.


```
./deps_install.sh
```

# References

https://github.com/ARK-Electronics/ROS2_PX4_Offboard_Example 
https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html 
