Project Overview

Project Title

Real-Time Sign Language to Text Translation System

Motivation

Communication between hearing-impaired individuals and people who do not understand sign language can be challenging. This project aims to provide an automated solution capable of translating sign language gestures into readable text.

Objectives

* Capture video input from a camera.
* Detect and process sign language gestures.
* Convert recognized signs into text.
* Display translated text to the user.
* Deploy the application on an embedded Linux platform generated using Buildroot.

System Architecture

Camera
↓
Video Capture
↓
Gesture Recognition Model
↓
Text Generation
↓
User Display

Hardware Platform

* Development Laptop
* USB Camera
* QEMU Virtual Platform for testing

Build System

Buildroot will be used to generate the Linux image and required packages for deployment.

Software Components

* Linux
* Buildroot
* Python
* OpenCV
* PyTorch

Open Source Packages

* OpenCV
* PyTorch
* NumPy

Previous Course Content Used

* Linux Programming
* Buildroot Development
* Socket Programming
* Process Management

Repository Organization

Repository contains:

* Documentation
* Project Schedule
* Source Code
* Buildroot Configuration
* Testing Scripts

Expected Deliverables

* Functional sign language recognition prototype
* Embedded Linux image
* Project documentation
* Demonstration of translation results

References

* Buildroot Documentation
* OpenCV Documentation
* PyTorch Documentation