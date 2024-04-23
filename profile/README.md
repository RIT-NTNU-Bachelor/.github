# Bachelor Thesis: User-Face tracking for Unreal Interface

Welcome to our GitHub organization, dedicated to the bachelor thesis of Kjetil Indrehus, Sander Hauge, and Martin Johannessen. This project aims to develop a system that uses Unreal Engine and a simple camera to track the user's face and eye direction, re-rendering scenes in real-time to maintain the illusion of 3D objects fixed in space from the user's perspective. This technology enables users to view 3D models from different distances and angles while ensuring the objects appear stationary, enhancing the mixed reality experience.

## Project Overview

Our project involves a complex integration of face detection, eye tracking, and real-time rendering techniques to achieve low latency and high temporal smoothness. These aspects are crucial for creating a realistic and immersive user experience, free from motion sickness and visual discomfort. We use a game engine to render the scene and use OpenCV for tracking the face of the user. 

### Problem Statement

The challenge lies in identifying the user's face and eye direction accurately and re-projecting the virtual scene accordingly. The software includes a calibration mode for both the camera and the display of virtual objects, along with manual adjustment capabilities for specific requirements. Our goal is to minimize latency and ensure smooth temporal transitions, providing a seamless and realistic interaction with 3D models.

### Main Repositories

Our system comprises several components, divided across the following main repositories:

1. **face-detection-opencv-cpp** - This repository contains the code for detecting the user's face using OpenCV and C++. It's a critical component for tracking the user's position and orientation.
2. **Unreal-facetracking-client** - Here, we integrate the face tracking data with Unreal Engine, enabling the real-time rendering of scenes based on the user's perspective.
3. **OpenCV_Server** - This repository manages the communication between the face detection module and the Unreal Engine client, ensuring efficient data transfer and processing.

### Client

Our project is in collaboration with the Rochester Institute of Technology (RIT), specifically with the Munsell Color Science Laboratory (MCSL). MCSL, located at RIT in Rochester, New York, is at the forefront of color science research, with a particular focus on augmented and virtual reality technologies.

## Installation and Usage

Please refer to each repository for detailed instructions on setting up and running the components of the system.

- [Unreal-facetracking-client](https://github.com/RIT-NTNU-Bachelor/Unreal-facetracking-client)
- [OpenCV_Server](https://github.com/RIT-NTNU-Bachelor/OpenCV_Server)

## Contributors

- Kjetil Indrehus
- Sander Hauge
- Martin Johannessen

