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

1. Anaconda
2. PX4
3. Micro XRCE DDS

It also creates a conda environment and a ros2 workspace. 

Before running the `deps_install` script, please download the Ananconda installation file from [here](https://www.anaconda.com/download/) 

```
chmod a+x deps_install.sh
```
The terminal will prompt you to enter your password. Enter the following command after entering your password.


```
./deps_install.sh
```