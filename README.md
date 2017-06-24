# A C++ implementation for using Prolog in ROS

![ros](https://img.shields.io/badge/ROS-Kinetic-brightgreen.svg)

## Overview

**Author(s): Ralf Kaestner</br>
Affiliation: Autonomous Systems Lab, ETH Zurich**

## Content

This project provides a ROS server/client interface to Prolog.

## Installation

### Dependencies

- [swi-prolog](http://www.swi-prolog.org)

  ```
  sudo apt-get install swi-prolog
  ```

- [jsoncpp](https://github.com/open-source-parsers/jsoncpp)

  ```
  sudo apt-get install libjsoncpp-dev
  ```

- [roscpp-nodewrap](https://github.com/ethz-asl/roscpp-nodewrap)

  ```shell
  cd <path_to_your_catkin_space>
  git clone https://github.com/ethz-asl/roscpp-nodewrap.git
  ```

### Building

```
cd <path_to_your_catkin_space>
catkin_make
```

## Usage

### Prolog Server

To launch the Prolog server, run

  ```
  roslaunch prolog_server mt_server_node.launch
  ```

### Interactive Prolog Client

To launch the interactive Prolog client, run

  ```
  roslaunch prolog_client interactive_client_node.launch
  ```

## Bugs & Feature Requests

Please report bugs and feature requests on the
[Issue Tracker](https://github.com/ethz-asl/ros-prolog).
