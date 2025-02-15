# `pykdl_conda` branch

> make `PyKDL` installed in conda environment

## My guide

**Please check [pykdl_installation_guide.md](./pykdl_installation_guide.md)!**

- ref: https://github.com/orocos/orocos_kinematics_dynamics/commit/364596e866e5569f9312967a447f9afdfc1099f6

## Kinematics and Dynamics Library

[![CI](https://github.com/orocos/orocos_kinematics_dynamics/workflows/CI/badge.svg)](https://github.com/orocos/orocos_kinematics_dynamics/actions)

Orocos project to supply RealTime usable kinematics and dynamics code,
it contains code for rigid body kinematics calculations and
representations for kinematic structures and their inverse and forward
kinematic solvers.

The C++ library is located in the `orocos_kdl` folder. The installation instructions can be found in
[INSTALL.md](orocos_kdl/INSTALL.md).

The python bindings, are located in the `python_orocos_kdl` folder. The installation instructions can be found in
[INSTALL.md](python_orocos_kdl/INSTALL.md).

Always use the same version of the C++ library and the python bindings. As a mismatch between these two can cause many issues.

Also when using ROS/catkin, it is preferred to use the catkin installation method over the `cmake/make` method.
