# clustering_based_motion_detection
This project implements a motion detection system that processes video streams to detect motion using clustering techniques and frame similarity measurement. The system is designed to be adaptive, allowing for sensitivity adjustments through an adjustable threshold.

### Instructions to Run:
the device running this needs to have a camera/webcam and Numpy, SKlearn, and OpenCV libraries are required<br>
Just run the Code as a normal .py file or as a .ipybn notebook(preferred)<br>
If the model detects motion, it prints 'motion detected' or 'no motion detected' this can be changed to return specific values if it is being used as a function<br>
To close the program/ video stream press 'q'<br>
### <b>Adjusting Sensitivity</b>
To modify the sensitivity of motion detection, adjust the threshold value in the script. Lowering the threshold will make the system less sensitive to minor movements while increasing it will increase sensitivity.

#### Drawback: a good amount of processing power is required for real-time results, I'll be working on a more efficient solution soon,
