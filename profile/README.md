# Welcome to Mech-Mind's GitHub page :tada:

![banner](https://docs.mech-mind.net/download/github/banner.jpg)

Mech-Mind is an industry-leading company focusing on industrial 3D cameras and AI-powered software for intelligent robotics.
By combining 3D vision with AI technology, Mech-Mind brings automation to the next level and empowers partners and system integrators to manage the most challenging automation tasks, including bin picking, depalletizing & palletizing, picking & placing, assembly, and inspection.

Mech-Mind products are developed for easy integration with other systems. This page provides resources that can aid you in achieving such integration.

- [**Resources for Mech-Eye Industrial 3D Camera**](#blue_book-resources-for-mech-eye-industrial-3d-camera)
- [**Resources for Mech-Eye 3D Laser Profiler**](#blue_book-resources-for-mech-eye-3d-laser-profiler)
- [**Resources for Mech-DLK SDK**](#blue_book-resources-for-mech-dlk-sdk)

## :blue_book: Resources for Mech-Eye Industrial 3D Camera

Through Mech-Eye SDK, you can control Mech-Eye Industrial 3D Camera (hereinafter referred to as "the camera") to obtain images and point clouds. Available for Windows and Linux, Mech-Eye SDK includes Mech-Eye API (the native API) and the GenICam interface for the camera. Mech-Eye API is available for C++, C#, and Python. ROS 1 and ROS 2 interfaces are also provided for communicating with the camera.

Before downloading the samples and ROS interfaces, please install Mech-Eye SDK first.

### Download Mech-Eye SDK

You can download Mech-Eye SDK from [**Mech-Mind Download Center**](https://downloads.mech-mind.com/?tab=tab-sdk). The latest version of Mech-Eye SDK is recommended for more comprehensive functionality and better stability.

### Samples of Mech-Eye API

The following samples are provided:

- [**C++ samples**](https://github.com/MechMindRobotics/mecheye_cpp_samples/tree/master/area_scan_3d_camera)
- [**C# samples**](https://github.com/MechMindRobotics/mecheye_csharp_samples/tree/master/area_scan_3d_camera)
- [**Python samples**](https://github.com/MechMindRobotics/mecheye_python_samples/tree/master/area_scan_3d_camera)

### ROS Interfaces of Mech-Eye Industrial 3D Camera

To integrate the camera with ROS projects, download and install the ROS interface:

- [**ROS 1 interface**](https://github.com/MechMindRobotics/mecheye_ros_interface)
- [**ROS 2 interface**](https://github.com/MechMindRobotics/mecheye_ros2_interface)

### Samples of Third-Party Machine Vision Software

The camera can also be controlled by third-party machine vision software through Mech-Eye API or the GenICam interface.

The following samples are provided:

- [**HALCON samples (GenICam interface)**](https://github.com/MechMindRobotics/mecheye_halcon_samples/tree/main/area_scan_3d_camera)
- [**VisionPro samples (C# Mech-Eye API)**](https://github.com/MechMindRobotics/mecheye_visionpro_samples/tree/main/area_scan_3d_camera)
- [**LabVIEW samples (C# Mech-Eye API)**](https://github.com/MechMindRobotics/mecheye_labview_samples)

## :blue_book: Resources for Mech-Eye 3D Laser Profiler

Through Mech-Eye SDK, you can control Mech-Eye 3D Laser Profiler (hereinafter referred to as "the laser profiler") to obtain images and point clouds. Available for Windows and Linux, Mech-Eye SDK includes Mech-Eye API (the native API) and the GenICam interface for the laser profiler. Mech-Eye API is available for C++ and C#.

Before downloading the samples, please install Mech-Eye SDK first.

### Download Mech-Eye SDK

You can download Mech-Eye SDK from [**Mech-Mind Download Center**](https://downloads.mech-mind.com/?tab=tab-sdk). The latest version of Mech-Eye SDK is recommended for more comprehensive functionality and better stability.

### Samples of Mech-Eye API

The following samples are provided:

- [**C++ samples**](https://github.com/MechMindRobotics/mecheye_cpp_samples/tree/master/profiler)
- [**C# samples**](https://github.com/MechMindRobotics/mecheye_csharp_samples/tree/master/profiler)

### ROS Interfaces of Mech-Eye 3D Laser Profiler

To integrate the laser profiler with ROS projects, download and install the ROS interface:

- [**ROS 1 interface**](https://github.com/MechMindRobotics/mecheye_profiler_ros_interface)
- [**ROS 2 interface**](https://github.com/MechMindRobotics/mecheye_profiler_ros2_interface)

### Samples of Third-Party Machine Vision Software

The laser profiler can also be controlled by third-party machine vision software through Mech-Eye API or the GenICam interface.

The following samples are provided:

- [**HALCON samples (GenICam interface)**](https://github.com/MechMindRobotics/mecheye_halcon_samples/tree/main/profiler)
- [**VisionPro samples (C# Mech-Eye API)**](https://github.com/MechMindRobotics/mecheye_visionpro_samples/tree/main/profiler)

## :blue_book: Resources for Mech-DLK SDK

As a software development kit specifically designed for Mech-DLK, Mech-DLK SDK aims to help you easily implement deep learning inference in your software systems. With Mech-DLK SDK, you can rapidly deploy deep learning models and flexibly integrate deep learning functionality into your own applications without relying on Mech-Vision or Mech-MSR. Currently, C#, C++, and Python are supported.

You can apply Mech-DLK SDK to perform inference on models exported from Mech-DLK.

> Note: Mech-DLK SDK 3.0.0 and later can perform inference on models exported from Mech-DLK 2.5.4 and later. Mech-DLK SDK earlier than 3.0.0 can perform inference on models exported from Mech-DLK 2.4.2 – 2.5.4.

### Download Mech-DLK SDK

You can download Mech-DLK SDK from [**Mech-Mind Download Center**](https://downloads.mech-mind.com/?tab=tab-dlk-sdk). The latest version of Mech-DLK SDK is recommended for more comprehensive functionality and better stability.

### Samples of Mech-DLK SDK

The following samples are provided:

- [**C# samples**](https://github.com/MechMindRobotics/mechdlk_sdk/tree/v3.0.0/samples/csharp)
- [**C++ samples**](https://github.com/MechMindRobotics/mechdlk_sdk/tree/v3.0.0/samples/cpp)
- [**Python samples**](https://github.com/MechMindRobotics/mechdlk_sdk/tree/v3.0.0/samples/python)
