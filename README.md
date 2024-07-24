# ros2-space-concordia-intro

Github repository for introduction task to Space Concordia

In this project, a ros2 workspace will be created alongside a custom package that will hold the service and client nodes. The client will be written in C++ while the server node will be written in Python.

### Usage

#### Source the setup files

For both the service and client nodes, run each of these commands in a new terminal to source the setup files:

` $ source /opt/ros/humble/setup.bash`

Then navigate into the root directory of the project and run:

`$ source install/setup.bash`

#### Service node

Now run the service node in one terminal:

`$ ros2 run <package_name> <executable_name_service>`

#### Client node

And run the client node in the other terminal:

`$ ros2 run <package_name> <executable_name_client>`

###### _By Jacques Martinez_
