The Stavrow-net module is responsible for state estimation and gate localization for the quadrotor drone using IMU data and stereocamera inputs.
Overview

Stavrow-net is designed to estimate the drone's position, velocity, orientation, and relative position to the next gate based on the inputs from the IMU and stereocamera. This module is crucial for accurate navigation and control in drone racing environments.
Inputs

The following inputs are required by the Stavrow-net:

    IMU Accelerations: Accelerometer readings from the IMU.
    Gyro Angles: Orientation angles from the gyroscope.
    Gyro Rates: Angular rates from the gyroscope.
    Estimate of Gate Location: Localization estimates of the gate positions from the stereocamera.

Outputs

The Stavrow-net outputs the following estimates:

    Position: The estimated position of the drone in 3D space.
    Velocity: The estimated velocity of the drone in 3D space.
    Angular Angles and Rates (Quaternions): The estimated orientation of the drone represented as quaternions, along with the angular rates.
    Relative Position to the Next Gate: The estimated position of the drone relative to the next gate.
