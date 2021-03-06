## Self-Driving Car Capstone Project

This is the final capstone project of the Self Driving Car Nanodegree course offered by Udacity.

In this project we write code to help drive Carla (an actual car) autonomously although at a maximum speed of 10mph for safety reasons. This project brings together several aspects of the SDC course such as Perception, Planning and Control. We first test the code on the simulator and then run it on Carla. The code is written using the ROS (Robotics Operating System) framework which works both on the simulator as well as on Carla. The final project report for our team sumission is [here](https://github.com/DeniseJames/CarND-Capstone/blob/master/SDC%20Capstone%20Project.pdf). 

The following gives details on how to run the code:

---

### Installation 

* Be sure that your workstation is running Ubuntu 16.04 Xenial Xerus or Ubuntu 14.04 Trusty Tahir. [Ubuntu downloads can be found here](https://www.ubuntu.com/download/desktop). 
* If using a Virtual Machine to install Ubuntu, use the following configuration as minimum:
  * 2 CPUIn this final capstone project of the Self-Driving Car Nanodegree course we write code to help drive Carla (an actual car) autonomously although at a maximum speed of 10mph for safety reasons. This project brings together several aspects of the SDC course such as Perception, Planning and Control. We first test the code on the simulator and then run it on Carla. The code is written using the ROS (Robotics Operating System) framework which works both on the simulator as well as on Carla.
  * 2 GB system memory
  * 25 GB of free hard drive space
  
  The Udacity provided virtual machine has ROS and Dataspeed DBW already installed, so you can skip the next two steps if you are using this.

* Follow these instructions to install ROS
  * [ROS Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu) if you have Ubuntu 16.04.
  * [ROS Indigo](http://wiki.ros.org/indigo/Installation/Ubuntu) if you have Ubuntu 14.04.
* [Dataspeed DBW](https://bitbucket.org/DataspeedInc/dbw_mkz_ros)
  * Use this option to install the SDK on a workstation that already has ROS installed: [One Line SDK Install (binary)](https://bitbucket.org/DataspeedInc/dbw_mkz_ros/src/81e63fcc335d7b64139d7482017d6a97b405e250/ROS_SETUP.md?fileviewer=file-view-default)
* Download the [Udacity Simulator](https://github.com/udacity/self-driving-car-sim/releases/tag/v0.1).

### Usage

1. Clone the project repository
```bash
git clone https://github.com/udacity/carnd_capstone.git
```

2. Install python dependencies
```bash
cd carnd_capstone
pip install -r requirements.txt
```
3. Make and run styx
```bash
cd ros
catkin_make
source devel/setup.sh
roslaunch launch/styx.launch
```
4. Run the simulator


