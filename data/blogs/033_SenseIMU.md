
## Introduction
Control a mouse by human gesture via Bluetooth - A demonstration of Kalman Filter and other different optimization and estimation approaches.

<div>
    <img src="assets/db/img/blogs/Freelance_25.jpg" class="blog-image" />
</div>

## Input
* Accelerometer raw data
* Gyroscope raw data
* Magnetometer raw data

## Output
* Estimated Euler angles
* Estimated Quaternion set
* Represent object orientation on 3D WinForm application
* Control mouse using estimated Euler angles via Bluetooth

## Functionality
* Bluetooth Connection
* Data plotting, 3D rendering
* Switching between different algorithms:
  - Tilt-compensation Method  
  - Gauss Newton Method 
  - AHRS
  - Quaternion based – gyro bias – EKF 
  - Quaternion based – gyro rate – EKF
  - DCM based KF 

## Screenshot

### HW Assembly  

<div>
    <img src="assets/db/img/blogs/Freelance_20.jpg" class="blog-image" />
</div>
<div>
    <img src="assets/db/img/blogs/Freelance_21.jpg" class="blog-image" />
</div>
<div>
    <img src="assets/db/img/blogs/Freelance_22.jpg" class="blog-image" />
</div>
<div>
    <img src="assets/db/img/blogs/Freelance_23.jpg" class="blog-image" />
</div>

### Demonstration  
<div>
    <img src="assets/db/img/blogs/Freelance_24.jpg" class="blog-image" />
</div>


### References:
 * Source code: [Link](https://github.com/jimmyvo2410/SenseIMU) 

