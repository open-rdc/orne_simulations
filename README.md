# orne_simulations  

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
