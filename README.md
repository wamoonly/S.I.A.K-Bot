S.I.A.K Bot has the ability to detect people in a row and detect the gap between the people. It also will be implemented with audio triggering which can notify people on the gap that they make. With the help of S.I.A.K Bot, gaps in the rows can be easily detected and help the congregation to fill the row space closely. Thus, the best congregational prayer can be performed by them. 

How to run:
1. Run $roscore on terminal to start the ROS environment. 
2. On another terminal, enter $rosrun robot_siak_pkg people_detection_publisher.py to start the publisher.
3. A new window will pop up that activates the camera. On a new terminal, enter $ rosrun robot_siak_pkg audio.py to start the subscriber node.
4. All done! Now we can $ rqt_graph on a new terminal to see the nodes running. 
