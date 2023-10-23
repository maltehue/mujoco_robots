# mujoco_robots
Robot package for mujoco_sim (https://github.com/HoangGiang93/mujoco_sim)


#### Fork of the original repository to add new worlds for the hsr
To start a world with the robot holding a cup containing 200 particles, and a bowl to pour into

```bash
roslaunch hsr_mujoco hsrb4s_velocity_particle_cup.launch
```
In the world .xml file of this launch file are options to make the particles appear more viscous and to make them more bouncy when hitting the container box.
![image](https://github.com/maltehue/mujoco_robots/assets/122607802/d2f45669-b181-4e5b-a71c-507a02e25a2f)


To start a world with the robot holding a cup containing 200 particles, and a bowl and an empty cup on a table to pour into

```bash
roslaunch hsr_mujoco hsrb4s_velocity_particle_containers.launch
```
![image](https://github.com/maltehue/mujoco_robots/assets/122607802/9597f973-b6e0-47d2-9821-b33ff68a9d20)

To start the same world but with an empty gripper

```bash
roslaunch hsr_mujoco hsrb4s_velocity.launch
```

To start a world where the hsr holds a tray with one ball on it

```bash
roslaunch hsr_mujoco hsrb4s_velocity_tray.launch
```
![image](https://github.com/maltehue/mujoco_robots/assets/122607802/8c4dd17f-37ba-425d-a053-e82a91bbec1a)


