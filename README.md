# Gazebo Tutorial for grasping essential concepts and technical jargon.


### Original Tutorial found at http://www.generationrobots.com/en/content/75-gazebo-and-ros



* Changes added to the original tutorial which had issues if you execute the code fresh from the tutorial.
* System Requirements: Ubuntu 12.04+ and ROS Hydro+. 
* Recommended Configuration: Ubuntu 14.04 and ROS Indigo


#### Steps to run this | In your working directory: 

- $ sudo apt-get install ros-indigo-effort-controllers
- $ mkdir -p learn_gazebo/src
- $ cd learn_gazebo/src
- $ catkin_init_workspace
- $ cd ..
- $ catkin_make

####
- $ cd src
- $ git clone https://github.com/jaypatravali/mybot_gazebo.git
- $ cd ..
- $ catkin_make


#### To run this 
- $ cd learn_gazebo
- $ source devel/setup.sh
- $ roslaunch mybot_gazebo mybot.launch- 


