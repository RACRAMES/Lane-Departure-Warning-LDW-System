# **Lane Departure Warning System for Autonomous Driving** 

### Objective

#### Lane Departure Warning (LDW) System: a monocular camera is used for detecting current lane, tracking the vehicle position and estimating the front road status. 

### Code & Files

#### 1. The project includes the following files

* [calibration.py](calibration.py) contains the script to calibrate camera and save the calibration results
* [main.py](main.py) is the main code
* [lane.py](model.h5) contains the lane class 
* [camera_cal](camera_cal) folder contains the images used for camera calibration and calibration results 
* [examples](examples) folder contains the sample images and videos
* [environment-gpu.yml](environment-gpu.yml) environment file with GPU 
* [README.md](README.md) summarizing the results

#### 2. Dependencies & my environment

* OpenCV3, Python3.5 
* you can use provided [environment file with GPU](environment-gpu.yml) to install the dependencies.

#### 3. How to run the code
If you want to run the demo, you can simply run:
```sh
python main.py
```
If you want to use the code to calibration your own camera and test the video, save the image into [camera_cal](camera_cal) and calibrate them with: 
```sh
python calibration.py
```



