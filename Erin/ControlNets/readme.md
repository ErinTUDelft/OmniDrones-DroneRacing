# ControlNet

The `ControlNet` module is responsible for controlling the quadrotor drone by computing the necessary motor RPM based on various inputs such as position, velocity, orientation, and waypoints.

## Overview

The `ControlNet` is a neural network-based controller designed to handle the dynamic environment of drone racing. It takes in several inputs related to the drone's state and the race course and outputs the required motor RPM values to achieve the desired flight behavior.

## Inputs

The following inputs are required by the `ControlNet`:

1. **Position**: The current position of the drone in 3D space.
2. **Velocity**: The current velocity of the drone in 3D space.
3. **Angles and Angular Rates (Quaternions)**: The orientation of the drone represented as quaternions, along with the angular rates.
4. **Current Waypoint**: The current target waypoint that the drone is aiming to reach.
5. **Following Waypoint**: The subsequent waypoint that the drone will target after reaching the current waypoint.
6. **Current Motor RPM**: The current rotational speeds of the drone's motors.

## Outputs

The `ControlNet` outputs the desired motor RPM values for the quadrotor:

1. **Motor RPM**: The rotational speeds for each of the drone's motors required to achieve the desired flight trajectory.

## File Structure

- **TBD**
