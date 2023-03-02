# ros2bridge_embedded
Bridge to communicate ROS2 nodes (messages by topics) and embedded platforms using wether WIFI (sockets) or serial port

## Mission Description of the System

The system shall have the capability of communicate an embedded platform with a ROS2 computation graph. It means that all messages published in the different topics by ROS2 nodes running in a Debian based Operating System shall be available for the embedded platform so the program running inside could subscribe to those topics

In the same way, from the embedded platform, different types of messages shall may be published in order to be available throught the computation graph for the ROS 2 nodes.

The high level overview of the system is depicted bellow.

![SysMLDiagram](https://github.com/fgonzalezr1998/ros2bridge_embedded/blob/main/docs/diagrams/ros2bridge_embedded_sysml.png)
