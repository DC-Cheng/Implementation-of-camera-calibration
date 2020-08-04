# camera_calibration_OpenCV_impl #

# Target #
1. implementation of signle camera calibration.
2. achieving intrinsic and extrinsic parameters of a camera output.
3. understandinf basic knowledge of optical distortion.

# Theroy #
<br>![Image0](https://docs.opencv.org/2.4/_images/math/363c6d531e851a1eb934e7d6f875d593e2dc6f37.png)
<br>![Image1](https://docs.opencv.org/2.4/_images/math/803e522ec37bc5bc609c0ef08373a350a819fc15.png)
<br>![Image2](https://docs.opencv.org/2.4/_images/math/f51a5ba02487486308c29bef720f3186d18abac6.png)
<br>![Image3](https://docs.opencv.org/2.4/_images/pinhole_camera_model.png)
<br>![Image4](https://docs.opencv.org/2.4/_images/math/331ebcd980b851f25de1979ebb67a2fed1c8477e.png)
<br>![Image5](https://docs.opencv.org/2.4/_images/distortion_examples.png)

# Related openCV API function #
1. `cv::calibrateCamera()`
2. `cv::findchessboardcorners()`
3. `cv::cornerSubPix()`
4. `cv::solvePNP()`

# Flow # 
step0. install OpenCV and create building environment. 
<br> step1. import several images as input. (i.e. `left01-14.jpg`, `right01-14.jpg`)
<br> step2. set the parameter of the files. (i.e. `in_VID.xml`)
<br> step3. set the input images list. (i.e. `VID5.xml`)
<br> step4. run `camera_calibration.cpp` and simply read the code inside.
<br> step5. the result will be shown. (i.e. `out_camera_data.xml`)

# Reference #
to see more implementation of open souce computer vision library, you can check on the websites:
https://docs.opencv.org/2.4/modules/calib3d/doc/camera_calibration_and_3d_reconstruction.html
