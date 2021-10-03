# Stereo-Reconstruction

### What is stereo reconstruction?
Stereo reconstruction aims to perform a dense 3D reconstruction of a scene from a stereo image pair.

### Algorithm
1. Calculate Calibration Matrix of the camera
2. Estimaate relative pose ( rotation and translation ) between the stereo pair
3. Compute Disparity map from the obtained data.
4. Project the image and depth values to obtain a dense point cloud.
5. Visualise the point cloud in suitable software like MeshLab.

### Implementation details
Precalcuated pose and calibration data was used from the [Middlebury Dataset](https://vision.middlebury.edu/stereo/data/scenes2014/) for this implementation.<br/>
Refer [Pose_Calculation](...) for calculation of of pose if not available and replace appropriate data in the code before running the code.

### Results 
1. Piano dataset



