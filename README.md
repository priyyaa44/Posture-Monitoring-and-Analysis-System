# Posture Monitoring and Analysis System

## Overview
This project presents a software-based posture monitoring and analysis system
that uses computer vision and machine learning techniques to detect and
analyze sitting posture in real time.

The system relies on webcam-based video capture and pose estimation to
identify posture deviations and provide feedback to the user.


## Project Scope
This repository documents the **system design, methodology, and workflow**
of the posture monitoring project. The implementation code is not included.
The repository is intended for academic reference and design understanding.


## System Workflow
1. Live video capture using a webcam
2. Human pose detection using MediaPipe Pose
3. Extraction of skeletal landmarks (neck, shoulders, spine)
4. Angle calculation for posture evaluation
5. User-specific posture calibration
6. Classification of posture as good or poor
7. Visual and audio feedback to the user


## Methodology
Detailed algorithm explanation, flowcharts, and posture analysis logic
are documented in the **methodology/** folder.


## User Interface
The posture monitoring interface is implemented using Streamlit.
UI screenshots and interface-related documentation are available in the
**ui/** folder.


## Results
Output screenshots and posture analysis results are stored in the
**results/** folder.


## Applications
- Work-from-home posture monitoring
- Student ergonomic assistance
- Office health and wellness systems
- Educational demonstrations of computer vision


## Advantages
- Non-invasive and low-cost (webcam-based)
- Real-time posture analysis
- User-specific calibration
- Easy to deploy and use


## Future Scope
- Mobile application integration
- Advanced machine learning-based posture classification
- Long-term posture analytics
- Integration with wearable devices


## License
This project is licensed under the MIT License.
