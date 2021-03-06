### Introduction
At VietSkyLine, I realized that Kalman Filter is the most challenging Machine Learning area in an UAV system. After I left the company, I decided to go deeper in this area. The project is a result after I investigated on many pieces of related published paper in 6 months. It includes Matlab modeling and simulating on many optimization approaches in the object-orientation-estimation system.

### Features:
* Input: raw data from Accelerometer, Gyroscope, Magnetometer
* Output: Euler angles, Quaternion

### Approaches:
* Tilt-compensation Method
<div>
    <img src="assets/db/img/blogs/HCMUT_11.jpg" class="blog-image" />
</div>

* Gauss Newton Method
<div>
    <img src="assets/db/img/blogs/HCMUT_12.jpg" class="blog-image" />
</div>

* AHRS
<div>
    <img src="assets/db/img/blogs/HCMUT_13.jpg" class="blog-image" />
</div>

* Quaternion based – gyro bias – Extended Kalman Filter
<div>
    <img src="assets/db/img/blogs/HCMUT_14.jpg" class="blog-image" />
</div>

* Quaternion based – gyro rate – Extended Kalman Filter
<div>
    <img src="assets/db/img/blogs/HCMUT_15.jpg" class="blog-image" />
</div>

* DCM based Kalman Filter
<div>
    <img src="assets/db/img/blogs/HCMUT_16.jpg" class="blog-image" />
</div>

### References:
 * Source code: [Link](https://github.com/jimmyvo2410/ObjectOrientationEstimationSystem) 
