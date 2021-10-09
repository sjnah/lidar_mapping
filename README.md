# ROS example (Opensource ROS migration)

ROS tutorial example for ROS migration

## Download
```bash
cd ~/catkin_ws/src
git clone https://github.com/sjnah/lidar_mapping
cd ..
catkin_make
```

## Run
```bash
# Terminal 1
roscore
```

```bash
# Terminal 2
cd ~/catkin_ws/src/lidar_mapping/scripts
python3 lidar_mapping_example.py
```

```bash
# Terminal 3
cd ~/catkin_ws/src/lidar_mapping/bag
rosbag play 2d_lidar2.bag -r 0.1
```


## Reference

### base code
- https://github.com/AtsushiSakai/PythonRobotics/tree/master/Mapping/lidar_to_grid_map

### rosbag file
- https://github.com/mbed92/laser-scanner-ros
