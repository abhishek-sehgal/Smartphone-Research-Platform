# Smartphone Research Platform

## Overview

This GitHub repository provides a set of guidelines one needs in order to run C/MATLAB algorithms on Android and iOS devices. The application explored here is for hearing improvement studies, but these guidelines can serve as a good baseline for any Applied Digital Signal Processing application.

The repository covers the following aspects:
* Software tools required to implement the algorithms on smartphones
* How to run C code on Android or iOS devices
* Converting MATLAB functions into C Code using MATLAB Coder
* Hardware dependencies one needs to be aware of while implementing these algorithms
* Designing a real-time audio filtering app for both Android and iOS

## Users Guides

[Android](UsersGuide-SmartphoneResearchPlatform-Android.pdf)<br>
[iOS](UsersGuide-SmartphoneResearchPlatform-iOS.pdf)

## Prerequisites

- For iOS implementation, a Mac laptop or desktop machine is required, as well as an apple developer account
- For Android implementation, [Superpowered SDK](https://superpowered.com) has been used to set up the audio I/O, which can be found at: [LINK](https://github.com/superpoweredSDK/Low-Latency-Android-iOS-Linux-Windows-tvOS-macOS-Interactive-Audio-Platform)
- For converting MATLAB code to C, MATLAB Coder app for MATLAB is required

## Credits

[Nasser Kehtarnavaz](http://www.utdallas.edu/~kehtar/) and Abhishek Sehgal<br>
[Signal and Image Processing Lab](http://www.utdallas.edu/~kehtar/SIP/index.htm)<br>
The University of Texas at Dallas<br>

## License and Citation
The codes are licensed under MIT license.

For any utilization of the code content of this repository, the following paper needs to be cited by the user:

- N. Kehtarnavaz, F. Saki, and A. Duran, [Anywhere-Anytime Signals and Systems Laboratory: From MATLAB
to Smartphones](https://ieeexplore.ieee.org/document/8527721), 2nd Edition, Morgan and Claypool Publishers, 2018.
- N. Kehtarnavaz, A. Sehgal, and S. Parris, [Smartphone-Based Real-Time Digital Signal Processing](https://www.morganclaypool.com/doi/abs/10.2200/S00885ED2V01Y201811SPR016), 2nd Edition
Morgan and Claypool Publishers, 2018.
