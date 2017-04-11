# openFABMAP


Open Source C++ Code for the FAB-MAP Algorithm. This fork has been modified to compile with openCV 3.2 and LSD-SLAM under Ubuntu 16.04 and ROS Kinetic.
For a propper read on what this is, refer to the original repo [here](https://github.com/arrenglover/openfabmap).

## Dependencies

- openCV 3.2 (if using ROS try ros-<distro>-opencv3 - tested on kinetic, it includes compiled non-free libraries as well)
- cmake

## Installation

### Windows (Visual Studio 2008)

please use the [original version](https://github.com/arrenglover/openfabmap), as I haven't tried building on Windows. I may have broke something during the port.

### Linux (g++)

The usuall cmake chain:
1. make a build directory for your generated code i.e. `cd <fabmaproot> && mkdir build && cd build/`
2. `cmake ..` or `cmake-gui ..`
3. 'make' (or other build tool that you are using)




