##SLAM-Project##

<p align="center">
  <img src="./misc/where.gif"/>
</p>

 This project discusses the SLAM(Simultaneous Localization And Mapping) problem and why it is important in robotics. Issues and challenges associated with the problem are highlighted and different approaches of SLAM are identified, including FastSLAM and GraphSLAM. Using ROS and Gazebo, a simulated robot equipped with a laser rangefinder and RGB-D camera is used to implement a form of GraphSLAM called Real-Time-Appearance-Base-mapping (RTAB-map) to generate 2D and 3D maps of two different environments. Both environments are successfully mapped, however the first environment is mapped more accurately due its layout and clearer features. It was found that an environment that has a lot of recurring features throughout the map caused issues with correspondence leading to poor mapping results. It is concluded that the work carried out in this project could easily be transferred to real world robots. Please refer to Map_My_World_Robot_project.pdf