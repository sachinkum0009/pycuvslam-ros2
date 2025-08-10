# Usage

## Running the Node

To run the PyCuVSLAM ROS2 node, use the following command:

```bash
ros2 run pycuvslam pycuvslam_node
```

## Launching the Node

You can also launch the node using a launch file:

```bash
ros2 launch pycuvslam pycuvslam_launch.py
```

## Configuration

The node can be configured using parameters. Here is an example of how to set parameters when launching the node:

```bash
ros2 launch pycuvslam pycuvslam_launch.py param1:=value1 param2:=value2
```
