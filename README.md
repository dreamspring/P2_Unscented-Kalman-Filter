# P2_Unscented-Kalman-Filter
Self-Driving Car Engineer Nanodegree Program, Project 2

## Overview
In this project, I utilized unscented kalman filter using C++ code to estimate the state of a moving object of interest with noisy lidar and radar measurements. 

## Basic Build Instructions
The project has the following dependencies (from Udacity's seed project):

cmake >= 3.5
make >= 4.1
gcc/g++ >= 5.4

To build the project:
1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make` 
   * On windows, you may need to run: `cmake .. -G "Unix Makefiles" && make`
4. Run it: `./UnscentedKF '

To run the code:
Set the build directory as current directory, then run ./UnscentedKF.
The following words will be shown on screen: Listening to port 4567.
Then run the simulator. There are two dataset sets in the simulator.

## Results
In this project, CTRV (constant turn rate and velocity magnitude) motion model  is chosen to implemented the unscented Kalman filter. 

Results with dataset 1:

The RMSE is calculated: 
X: 0.0769;  Y: 0.0870;  VX: 0.3709;  VY: 0.2945

Snapshot from simulator:

![Test One Visualization](https://github.com/dreamspring/P2_Unscented-Kalman-Filter/blob/master/P2_dataset1.png "Test One Visualization")

Results with dataset 2:

The RMSE is calculated: 
X: 0.0922;  Y: 0.0824;  VX: 0.6664;  VY: 0.4735

Snapshot from simulator:

![Test One Visualization](https://github.com/dreamspring/P2_Unscented-Kalman-Filter/blob/master/P2_dataset2.png "Test One Visualization")


