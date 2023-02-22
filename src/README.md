dynamixel_mx_controller/
|-- CMakeLists.txt
|-- package.xml
|-- src/
    |-- dynamixel_mx_controller_node.cpp
    |-- dynamixel_mx_controller.cpp
    |-- dynamixel_mx_controller.h


    CMakeLists.txt: This file is used to build the package and contains information about the package's dependencies, libraries, and executables.

    package.xml: This file contains information about the package, such as the package name, version, and dependencies.

    <package_name>: This folder contains the source code for the ROS1 package. Within this folder, you can have the following files:
        <package_name>_node.cpp: This is the main source file for the ROS node that communicates with the Dynamixel MX-64 motor.
        <package_name>_controller.cpp: This file contains the implementation of the custom ROS message type dynamixel_mx_controller::MXCurrentControl.
        <package_name>_controller.h: This file contains the declaration of the custom ROS message type dynamixel_mx_controller::MXCurrentControl.
