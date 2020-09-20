# orne_simulations  
![Screenshot from 2020-09-21 03-49-16](https://user-images.githubusercontent.com/25315656/93719450-9b3bce00-fbbd-11ea-96d9-378a9c117f78.png)
![Screenshot from 2020-09-21 03-53-20](https://user-images.githubusercontent.com/25315656/93719546-36cd3e80-fbbe-11ea-971d-4e85b04b5a8f.png)
![Screenshot from 2020-09-21 03-53-58](https://user-images.githubusercontent.com/25315656/93719545-359c1180-fbbe-11ea-9369-72696dbf749c.png)
# build  
```
cd ~/catkin_ws/src
git clone https://github.com/taishiyamamoto/orne_simulations.git
catkin build orne_simulations
```

# Run
## spawn orne_box in the building No.2 3rd floor of CIT
```
roslaunch orne_gazebo orne_box_tsudanuma_world.launch model:=box
```

## spawn orne_alpha
```
roslaunch orne_gazebo orne_box_tsudanuma_world.launch model:=alpha
```
# TODO
* add model of orne_beta  
* add 3d lidar
