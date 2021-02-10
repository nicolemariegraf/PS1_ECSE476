# PS1_ECSE476
My code, in package form, with CMakeLists.txt, package.xml, video, and source in a ROS package form.
The node to run my_stdr_control is nmg63_stdr_open_loop_commander

In your catkin_ws, all you need to have the robot0 navigate from the bottom corner to the top corner is the following command:

  rosrun my_stdr_control nmg63_stdr_open_loop_commander
  
The commands written in the cpp file were determined through trial and error with the STDR simulator.
