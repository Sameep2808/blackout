# RWA3_ENPM809E
Baseline package for RWA3.

# Disclaimer

This package is provided as an example on how to perform kitting with the kitting robot. There is no guarantee that it will work everytime you run the demo.

# Installation

Assuming your catkin workspace is `ariac_ws`
```bash
cd ~/ariac_ws/src
git clone 
cd ..
rosdep install --from-paths ./src --ignore-packages-from-source -y
catkin build
source ~/ariac_ws/devel/setup.bash
```

# Run

- To run the code

```bash
roslaunch group3_rwa3 ariac.launch
rosrun group3_rwa3 kitting_movegroup_node
```

