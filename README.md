# Second Order Systems App in MATLAB

## Overview

This MATLAB application allows users to visualize the behavior of a standard second-order transfer function in real time. The app provides the following features:

- Plot of the unit step response
- Pole-zero diagram
- Bode plot
- Display of the transfer function

Users can interactively adjust the damping ratio (δ), natural frequency of oscillation (ω_n), and gain (K) using sliders, allowing for a dynamic exploration of the system's response.

## Transfer Function

The application utilizes the following standard second-order transfer function:

\[ G(s) = \frac{K \cdot \omega_n^2}{s^2 + 2 \cdot \delta \cdot \omega_n \cdot s + \omega_n^2} \]

## Features

1. **Unit Step Response Plot**: Displays the response of the system to a unit step input.
2. **Pole-Zero Diagram**: Illustrates the poles and zeros of the transfer function.
3. **Bode Plot**: Shows the frequency response of the system in terms of magnitude and phase.
4. **Interactive Sliders**: Users can modify:
   - Damping Ratio (δ) [Range: 0 to 2]
   - Natural Frequency (ω_n) [Range: 0 to 10]
   - Gain (K) [Range: 0 to 10]

## Getting Started

### Prerequisites

- MATLAB with App Designer support.
- Basic understanding of control systems and transfer functions.

### Video App Demo

[Watch the video](https://www.youtube.com/watch?v=Q38KdlibB_I)



