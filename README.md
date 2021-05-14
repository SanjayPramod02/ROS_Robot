# ROS_Robot
## Instrucitons for setting up the m2wr_decription package in local directory
1. Change directory to catkin_ws/src
```bash
cd ~/catkin_ws/src
```
2. Clone repository
```bash
git clone https://github.com/SanjayPramod02/ROS_Robot
```
3. Change directory to catkin_ws and run catkin_make to "make" the files in the workspace.
```bash
cd ..
catkin_make
```
4. verify whether ROS has identified package and installed it
```bash
rospack find m2wr_description
```
5. Run required files eg: rviz.launch
```bash
roslaunch m2wr_description rviz.launch
```



