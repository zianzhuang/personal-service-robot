## Group Number
2


## List of Commands
roscore
roslaunch mie443_contest2 turtlebot_world.launch world:=1
roslaunch turtlebot_gazebo amcl_demo.launch map_file:=/<map_file>/map_1.yaml
rosrun mie443_contest2 contest2


## File Path Strings
in contest2.cpp:
line 102: std::ofstream results_file("/home/janicezhou/Desktop/results.txt"); //// update result file address
line 114: templates_file.open("/home/janicezhou/catkin_ws/src/mie443_contest2/boxes_database/templates.xml"); //// update result file address

## Output File Location
The output file will be saved on the desktop as specified in line 102 above

## Simulation Video
In case the video in this folder cannot be opened, here is the link to view the video online: https://drive.google.com/file/d/1U1rrSMnYqr5uiRTeNn_JtLm0G0biuszL/view?usp=sharing



Thank you!
