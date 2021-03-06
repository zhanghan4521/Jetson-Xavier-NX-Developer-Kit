# Jetson-Xavier-NX-Developer-Kit
## Getting Started with Jetson Xavier NX Developer Kit

There are already lots of resources on the official website, but some of the documents or information there are repetitive and are not so needed by a beginner. Therefore, I wrote this getting started guide, which is a compilation of the official resources, to provide those who are just getting started with a reference.

### Summary

`NVIDIA Jetson Xavier NX Developer Kit` includes Jetson Xavier NX module, thus enables development of full-featured, multi-modal AI applications for product based on the Jetson Xavier NX module. 

`Jetson Xavier NX module` is a compact power efficient computer for AI edge devices to run real-time AI applications. Delivering up to 21 TOPS of compute in a compact form factor with under 15W of power, it brings server-level performance and could-native workflows to edge AI devices and autonomous machines.


### What’s included

* A 90*103mm Reference `Carrier Board` (P3509-0000)
*	A `Jetson Xavier NX module` with heatsink/fan (P3669-0000)
*	A `19V power supply`
*	An 802.11 plug-in `WLAN` + `Bluetooth` 5.0 M.2 module + antennas

*** `Need to set up a MicroSD card` (16G or larger UHS-1 minimum) : https://developer.nvidia.com/embedded/learn/get-started-jetson-xavier-nx-devkit

<img src="https://github.com/zhanghan4521/Jetson-Xavier-NX-Developer-Kit/raw/master/2020-09-03T00_38_34.png" width="350">

Ports:

<img src="https://github.com/zhanghan4521/Jetson-Xavier-NX-Developer-Kit/raw/master/2020-09-03T00_39_10.png" width="600">

For interface details or power guide, please see from the [Jetson Xavier NX Developer Kit User Guide](https://developer.nvidia.com/embedded/downloads#?search=Jetson%20Xavier%20NX%20Developer%20Kit%20User%20Guide).


### Evaluating Jetson Xavier NX module

#### Jetson family:

NVIDIA Jetson is the world’s leading platform for AI at the edge. Its high-performance, low-power computing for deep learning and computer vision makes it the ideal platform for compute-intensive projects. The Jetson platform includes a variety of Jetson modules together with NVIDIA JetPack SDK. 

<img src="https://github.com/zhanghan4521/Jetson-Xavier-NX-Developer-Kit/raw/master/2020-09-03T01_00_57.png" width="600">

The platform was focused on accelerating convolutional neural networks but Jetson’s GPU architecture has the flexibility to accelerate both today’s and tomorrow’s algorithms. Supports for the latest and greatest networks are added in the continuous introduced Jetson modules.

#### Why Jetson Xavier NX module:

<img src="https://github.com/zhanghan4521/Jetson-Xavier-NX-Developer-Kit/raw/master/2020-09-04T03_38_45.png" width="250">

Jetson Xavier NX is the latest member of Jetson family, with more than 10 times the performance and a smaller form factor than its widely adopted predecessor Jetson TX2 at the same price. Based on NVIDIA's groundbreaking Xavier SoC, it can run multiple complex models and multiple high-definition sensor streams in parallel. Jetson Xavier NX module was designed for accelerating machine learning applications and is useful for deploying computer vision and deep learning to the edge. 


### JetPack SDK

`NVIDIA JetPack SDK` is the most comprehensive solution for building AI applications. It includes the latest OS images for Jetson products, along with libraries and APIs, samples, developer tools, and documents. ``JetPack 4.4`` adds support for Jetson Xavier NX, which contains CUDA Toolkit 10.2 along with cuDNN 8.0, TensorRT 7.1, DeepStream 5.0, the NVIDIA Container Runtime for deploying cloud-native services, and other components.

`NVIDIA Jetson Linux Driver Package (L4T)` is the operating system component of JetPack, and provides the Linux kernel, Bootloader, Jetson Board Support Package (BSP), and sample filesystem for Jetson developer kits.

* Install JetPack 4.4:
https://developer.nvidia.com/embedded/downloads#?search=Jetson%20Xavier%20NX
*	Jetson Linux Developer Guide: 
https://docs.nvidia.com/jetson/l4t/index.html

#### source: https://developer.nvidia.com/embedded/jetson-xavier-nx-devkit
