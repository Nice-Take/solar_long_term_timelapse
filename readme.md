# Solar-Powered Timelapse Camera System
* The code for this project is currently not public but the overview is*
* To interact with this currently deployed sample visit: https://nicetake.com/consolidated_viewer*

## Project Overview

The objective of this project was to develop a self-sustaining, solar-powered timelapse camera system capable of continuous operation and remote access without manual intervention. This system is complemented by a user-friendly front-end application for users to access and view timelapse esults or even capture a new image on demand.

## Hardware Engineering

### Solar-Powered Solution

The project's cornerstone is its innovative use of solar power, enabling the camera system to run indefinitely in outdoor settings.

![Solar-Powered Camera System](https://nicetake.com/tl_images/IMG_6420.jpeg)
*Caption: The outlet in this image does not work (We really tried).*


### The Hardware Nice & Tidy

Due to the distance from the subject special lensing had to be used.

![The Brain](https://nicetake.com/tl_images/IMG_5220.jpeg)
*Caption: The solar-powered timelapse camera build ready for the field.*


### Single-Board Computer

At the heart of the camera system is a single-board computer (SBC), chosen for its efficiency and compact form factor.

### Unanticipated Challenges

Spiders. Did not think of spiders. Once Halloween was through they went home.

![Did Not See This Coming](https://nicetake.com/tl_images/IMG_6126.jpeg)
*Caption: Too many legs and too many webs.*

## Software Engineering

### Custom Software Development

The system is powered by custom software designed to manage power consumption, automate the capture process, and handle data storage and retrieval.The cloud server is on AWS EC2 using S3. FastAPI was used to build the REST and the rest of the sauce was done with Python3 and Go. The frontend was built using Google's Flutter framework which leverages the Dart programming language.

![Desktop Grid View](https://nicetake.com/tl_images/timelapse_view_desktop.png)
*Caption: Desktop view from Safari.*


![Mobile Grid View](https://nicetake.com/tl_images/TimelapseViewer.png)
*Caption: Mobile grid view.*


![Image Click](https://nicetake.com/tl_images/021924.png)
*Caption: Image click to enlarge.*


![Image Zoom](https://nicetake.com/tl_images/021924_zoom.png)
*Caption: Image zoom.*


![Capture Now Success](https://nicetake.com/tl_images/capture_image_success.png)
*Caption: Capture Now Success.*
