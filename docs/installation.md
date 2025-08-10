# Installation

## Prerequisites

Before installing the PyCuVSLAM ROS2 package, ensure you have the following prerequisites:

- ROS2 installed (Humble Hawksbill or later)
- Python 3.8 or later
- OpenCV
- PCL (Point Cloud Library)

## Installation Steps

1. Clone the repository:

```bash
git clone https://github.com/yourusername/pycuvslam-ros2.git
```

2. Navigate to the workspace:

```bash
cd pycuvslam-ros2
```

3. Install dependencies:

```bash
rosdep install -y --from-paths src --ignore-src --rosdistro $ROS_DISTRO
```

4. Build the package:

```bash
colcon build
```

5. Source the setup file:

```bash
source install/setup.bash
```
