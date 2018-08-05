# image shot
<img src="/picture/1.png" width="70%" height="70%">  

# youtube video
Click image to link to YouTube video.  
[![Video Label](http://img.youtube.com/vi/gjvN7VKTSh8/0.jpg)](https://youtu.be/gjvN7VKTSh8?t=0s)   

# Run
* First install open manipulator  
http://emanual.robotis.com/docs/en/platform/openmanipulator/   
* Second replace meshes and urdf folders of 'ros_data folder' to 'open_manipulator_description'  
* Third run  
roscore  
roslaunch open_manipulator_gazebo open_manipulator_gazebo.launch  
roslaunch open_manipulator_moveit open_manipulator_demo.launch use_gazebo:=true   

