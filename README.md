# geometry
Packages for common geometric calculations including the ROS transform library, "tf". Also includes ROS bindings for "bullet" physics engine and "kdl" kinematics/dynamics package.
## Yesterday, at the evening we (@Wessi, @Selamab, @Tesfa and @Meagreg) briefly discussed about the skeleton tracker and the corresponding tf which we have been working to integrate the other functionalities into the skeleton tracker. From the ros side, specifically on tf and tf_monitor @Tesfa gave us a good presentment explanation on different tf and skeleton components.
## 1. First we will work to monitor the skeleton data by using a modified version of tf_monitor which publishes filtered names then we will be able to combine the tracked users as a block of different multiple frames.
## 2. Second we will work on identifying and separating each of the frames for each user.
## 3. Third we will work on getting the transformations and rotations data specific to each frame.
## 4. Being able to accomplish all the above means we are able to exactly indicate where to integrate the other functions to the skeleton tracker.
## 5. Then we will integrate the gesture recognizer to the skeleton tracker, and others too.
