# camera-calibration-and-image-undistortion
Based on 13 images given, compute the parameters and undistort them using OpenCV.

The code takes the tutorial on camera calibration of OpenCV as a reference, so if you need more information, please have a visit at
[Camera Calibration](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_calib3d/py_calibration/py_calibration.html#calibration)
and
[Camera Calibration and 3D Reconstruction](https://docs.opencv.org/2.4/modules/calib3d/doc/camera_calibration_and_3d_reconstruction.html).

## calibration.py
- Read all 13 images in folder "left" and compute the parameters of camera including camera matrix and distortion coefficients.
- return:
  - intrinsic matrix; 
  - distortion coefficients;
  - rotation vector for each image;
  - translation vector for each image.

## undistortion1.py
- using the parameters got in calibration.py, undistort all 13 images.
- output the 13 images undistorted in folder "calibresult1" and the corressponding undistortion error.

## undistortion2.py
- input a certain image needed to undistort, output the result to folder "calibresult2" and undistortion error.

## Note
If you have any question or advice, contact with me

email: zhangchihao@zju.edu.cn
