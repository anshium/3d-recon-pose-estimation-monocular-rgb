# README for 3D Reconstruction and Nearest 6-DoF Pose Estimation

## Overview

This repository contains a comprehensive pipeline for real-time **3D reconstruction** and **nearest 6 Degrees of Freedom (6DOF) pose estimation** from monocular RGB video data. The approach integrates various computer vision and robotics techniques to deliver accurate pose estimation, which is essential for applications in augmented reality, robotics, and autonomous systems.

- Real-time 3D model construction using **Truncated Signed Distance Function (TSDF)** fusion.
- Accurate estimation of the object’s **6DOF pose**.
- High-resolution 3D mesh generation using **Marching Cubes** and **Occupancy Dual Contouring** algorithms.

## Pipeline Overview

The pipeline consists of three main steps:

1. **3D Model Construction**: Using TSDF fusion from consecutive depth maps to create a dense 3D model.
2. **Pose Estimation**: Estimating the object's 6DOF pose based on the constructed model.
3. **Mesh Generation**: Generating a high-resolution 3D mesh for refined pose estimation through differential rendering.

## Dataset

The following datasets are utilized in this project:
- **7 Scenes Dataset**: Provides ground-truth 6DOF poses along with RGB images and depth maps.
- **Blender**: Used to create synthetic environments with accurate camera poses.
- **Gazebo**: Simulates a robot with a depth camera to gather RGB-D data.

## Contributors

- \*Gaurav Behera (gaurav.behera@research.iiit.ac.in)
- \*Samkit Jain (samkit.jain@students.iiit.ac.in)
- \*Ansh Chablani (ansh.chablani@research.iiit.ac.in)

\* = Equal Contribution
