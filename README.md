The calibrate.cpp source is modified from https://learnopencv.com/camera-calibration-using-opencv/

Get a checkerboard image at https://github.com/opencv/opencv/blob/master/doc/pattern.png

`cameraMatrix` is `[f_x, 0, c_x; 0, f_y, c_y; 0, 0, 1]` (https://docs.opencv.org/master/d9/d0c/group__calib3d.html#ga3207604e4b1a1758aa66acb6ed5aa65d)

`distCoeffs` is `k_1, k_2, p_1, p_2, k_3`

You can check fps conveniently at https://webcamtests.com/fps.
