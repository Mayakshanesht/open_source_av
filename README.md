# open_source_av
A repository to host the open source projects for Autonomous Driving research whatsapp group
Community Creator: Mayur Waghchoure


I am hoping all our projects would fit together as a jigsaw puzzle to get the autonomous driving capable software
# Track A
First visual/sensor fusion + Semantic BEV + detection + tracking + motion prediction to get the current tracks and future trajectories
# Track B 
Semantic SLAM, 3D mapping, and Localization or point cloud project to localize the object and to get the map
# Track C 
Then path planning would jump in and then controls
# Track D
DBW, Motor controls and Simulation based testing

# Projects

## Track A Projects:

## 1. Visual Fusion/ Sensor fusion
To fuse the data from multiple modalities to get the understanding of the scene. e.g. Lidar and camera fusion to get the list of detected objects

## 2. Semantic BEV
To merge the data from the multiple cameras toget the birds eye view of the scene, and then perfrom the downstream tasks on it. first try this with IPM , and then using the transformers.

## 3. Object detection and tracking
First try out one stage and two stage object detector on camera images to detect the vehicles, pedestrians, traffic lights and Signs, and track them further
Second, to perform this on Birds eye view(BEV) maps of the scene by merging info from multiple cameras

## 4. Motion prediction
To perfrom the track prdection using the model based approach followed by hybrid approach and then deep learning approach for the long term motion prediction

## 5. Sensor fusion
Fuse the data from different sensors using the different data association methods and kalman filters

## Track B projects:

## 6. Localization
1. GPS and Odometry based Localization using the Kalman filters
2. Visual odometry
3. HD Map based Localization 
a. Lanelet maps
b. Lidar Point Cloud based Localization 
3. Mapless Localization

please find the relevant research papers, and try to implement first GPS +IMU based Localization. 
Eventually try the HD Map based localization

## 7. 3D mapping and 3D scene reconstruction
To create the map of the environment using the lidar or camera data.

## 8. Semantic SLAM
using the Graph neural networks create the map of the environment and localize inside it

## Track C projects:

## 9. Path Planning
we would want to develop the path planning algorithm for the autonomous vehicles. 
1. Global planner: here we would want to develop the global planner using the lanelet maps or Google maps api
2. Behavior planner: it would be rule based in the beginning using the state machines, which we can later do using the RL
3. Local planner: local planner would be of different style, which would include the path profiling and velocity profile planning, some algo are state lattice planners,  RRT* etc. We could also develop MPC controller do the trajectory planning and tracking

## 10. MPC based trajectory planning and control to enable the connected mobility

## 11. Longitudinal and Lateral control algorithms

## Track D projects
## 12. Drive by wire module
## 13. Motor controllers
## 14. Communication network
## 15. Simulation for the testing

## 16. ADAS feature development using the Model based design methodology

