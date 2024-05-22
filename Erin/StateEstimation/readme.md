The `Stavrow-net` module is responsible for state estimation and gate localization for the quadrotor drone using IMU data and stereocamera inputs.

## Overview

`Stavrow-net` is designed to estimate the drone's position, velocity, orientation, and relative position to the next gate based on the inputs from the IMU and stereocamera. This module is crucial for accurate navigation and control in drone racing environments.

## Inputs

The following inputs are required by the `Stavrow-net`:

1. **IMU Accelerations**: Accelerometer readings from the IMU.
2. **Gyro Angles**: Orientation angles from the gyroscope.
3. **Gyro Rates**: Angular rates from the gyroscope.
4. **Estimate of Gate Location**: Localization estimates of the gate positions from the stereocamera.

## Outputs

The `Stavrow-net` outputs the following estimates:

1. **Position**: The estimated position of the drone in 3D space.
2. **Velocity**: The estimated velocity of the drone in 3D space.
3. **Angular Angles and Rates (Quaternions)**: The estimated orientation of the drone represented as quaternions, along with the angular rates.
4. **Relative Position to the Next Gate**: The estimated position of the drone relative to the next gate.
