[image1]: ./images/rvizGoal.png
[image2]: ./images/gazeboGoal.jpg
[image3]: ./images/HsinBot1.jpg
[image4]: ./images/HsinBot2.jpg
[image5]: ./LATEX/laserrangefinder.png
[image6]: ./LATEX/f2.png
[image7]: ./LATEX/f3.png

# RoboND-Where-Am-I
Udacity Robotics Software Engineer Nanodegree Term 2 Localization Project:

### Running the Scripts
Run the following commands below in separate terminals: 

``
cd /home/workspace/catkin_ws``    
``catkin_make``   
``source devel/setup.bash``

Launch the world in Gazebo and RViz:  
`` cd /home/workspace/catkin_ws/``  
``roslaunch udacity_bot udacity_world.launch``  
Launch the AMCL node for localization:  
``roslaunch udacity_bot amcl.launch``  
Launch Navigation stack  
``rosrun udacity_bot navigation_goal``  

### Result Video:

### Udacity_bot:

![][image5]

### Udacity bot enter the goal: 

Gazebo                     |  Rviz
:-------------------------:|:-------------------------:
![][image7]                | ![][image6]

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/77fRZvHiigc/0.jpg)](https://youtu.be/77fRZvHiigc)  

### Hsin_bot:
Rviz                       |  Gazebo
:-------------------------:|:-------------------------:
![][image1]                | ![][image2]

### Hsin bot enter the goal: 

Hsin bot                   | Hsin bot
:-------------------------:|:-------------------------:
![][image3]                | ![][image4]

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/zJbhJagSImg/0.jpg)](https://youtu.be/zJbhJagSImg)
