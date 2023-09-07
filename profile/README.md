# Welcome to Mech-Mind's GitHub page :tada:

![banner](https://docs.mech-mind.net/download/github/banner.jpg)

Mech-Mind is an industry-leading company focusing on industrial 3D cameras and AI-powered software for intelligent robotics.
By combining 3D vision with AI technology, Mech-Mind brings automation to the next level and empowers partners and system integrators to manage the most challenging automation tasks, including bin picking, depalletizing & palletizing, picking & placing, assembly, and inspection.

Mech-Mind products are developed for easy integration with other systems. This page provides resources that can aid you in achieving such integration.

- [**Resources for Mech-Eye Industrial 3D Camera**](#resources-for-mech-eye-industrial-3d-camera)
- [**Resources for Mech-DLK SDK**](#resources-for-mech-dlk-sdk)

## Resources for Mech-Eye Industrial 3D Camera

Through Mech-Eye SDK, you can control Mech-Eye Industrial 3D Camera (hereinafter referred to as "the camera") to obtain images and point clouds. Available for Windows and Linux, Mech-Eye SDK includes Mech-Eye API (the native API) and the GenICam interface for the camera. Mech-Eye API is available for C++, C#, and Python. ROS 1 and ROS 2 interfaces are also provided for communicating with the camera. 

After installing Mech-Eye SDK, you can download samples and ROS interfaces.


### Download Mech-Eye SDK

You can download Mech-Eye SDK from [**Mech-Mind Download Center**](https://downloads.mech-mind.com/?tab=tab-sdk). The latest version of Mech-Eye SDK is recommended for more comprehensive functionality and better stability.

### Samples of Mech-Eye API

The following samples are provided:

- [**C++ samples**](https://github.com/MechMindRobotics/mecheye_cpp_samples)
- [**C# samples**](https://github.com/MechMindRobotics/mecheye_csharp_samples)
- [**Python samples**](https://github.com/MechMindRobotics/mecheye_python_samples)

### ROS Interfaces of Mech-Eye Industrial 3D Camera

To integrate the camera with ROS projects, download and install the ROS interface:

- [**ROS 1 interface**](https://github.com/MechMindRobotics/mecheye_ros_interface)
- [**ROS 2 interface**](https://github.com/MechMindRobotics/mecheye_ros2_interface)

### Samples of Third-Party Machine Vision Software

The camera can also be controlled by third-party machine vision software through Mech-Eye API or the GenICam interface. 

The following samples are provided:

- [**HALCON samples (GenICam interface)**](https://github.com/MechMindRobotics/mecheye_halcon_samples)

## Resources for Mech-DLK SDK

As a secondary development software kit specifically designed for Mech-DLK, Mech-DLK SDK aims to help you easily implement deep learning inference in the software systems. With Mech-DLK SDK, you can rapidly deploy deep learning models and flexibly integrate deep learning functionality into your own applications without relying on Mech-Vision. Currently, development in C language is supported. 

You can apply Mech-DLK SDK to implement inference for deep learning models trained by Mech-DLK (version 2.4.2 or above).

### Obtain Mech-DLK SDK

Follow steps below to obtain Mech-DLK SDK:
1. Create a local project folder, for example, *dlk_sdk*.
2. Clone the [**Mech-DLK SDK repository**](https://github.com/MechMindRobotics/mechdlk_sdk/tree/v2.0.0) from GitHub to *dlk_sdk*.
3. Download the third-party libraries (3rd_dll.zip) and resources file (resources.zip) that Mech-DLK SDK relies on to *dlk_sdk* from [**Mech-Mind Download Center**](https://downloads.mech-mind.com/?tab=tab-dlk-sdk).
4. Unzip the downloaded packages to ensure the *dlk_sdk* folder contains the required files: 3rd_dll, mechdlk_sdk, and resources.

### Samples of Mech-DLK SDK

The following samples are provided:

- [**C samples**](https://github.com/MechMindRobotics/mechdlk_sdk/tree/v2.0.0/samples/c)




