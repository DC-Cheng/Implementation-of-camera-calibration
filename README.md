# camera_calibration_OpenCV_impl #

# Target #
1. implementation of signle camera calibration.
2. achieving intrinsic and extrinsic parameters of a camera output.
3. understandinf basic knowledge of optical distortion.

# Related openCV API function #
1. `cv::calibrateCamera()`
2. `cv::findchessboardcorners()`
3. `cv::cornerSubPix()`
4. `cv::solvePNP()`

# Flow # 
[hint]:
<br> step1. import several images as input. (i.e. `left01-14.jpg`, `right01-14.jpg`)
<br> step2. set the parameter of the files. (i.e. `in_VID.xml`)
<br> step3. set the input images list. (i.e. `VID5.xml`)
<br> step4. run `camera_calibration.cpp` and simply read the code inside.
<br> step5. the result will be shown. (i.e. `out_camera_data.xml`)

# Reference #
to see more implementation of open souce computer vision library, you can check on the websites:
https://docs.opencv.org/2.4/modules/calib3d/doc/camera_calibration_and_3d_reconstruction.html
