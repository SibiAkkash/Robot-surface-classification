### Sensor fusion
Combine multiple data sources in a way that generates a better understanding of the system
* Used in self-driving cars, radar tracking, IoT
 
---

* magnetometer
* accelerometer
* gyroscope
Use a combination of these to estimate the orientation of a system (attitude and heading reference system - AHRS)

### Orientation is described as a rotation
* choose reference frame
* specify rotation (3D rotation between 2 coordinate frames)
  * roll, pitch, yaw - has some drawbacks
  * direction cosine matrices (DCM)
  * Quaternion


pedestrian dead reckoning
kalman filters, KNN
CNN, RNN

sensor sampling frequencies are not same
dead reckon with IMU data, include WiFi data when received
