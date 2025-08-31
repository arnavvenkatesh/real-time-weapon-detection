# real-time-weapon-detection

## Overview
This project uses OpenCV’s Haar cascade classifier to detect weapons (guns) in a live webcam feed. Frames are captured from the default camera, converted to grayscale, and passed through a pre-trained cascade. When a detection occurs, a bounding box is drawn and an on-screen warning is displayed.

## How to Use
1. Ensure the cascade file `cascade.xml` is present in the repository root (this is the Haar cascade used by the detector).
2. Install dependencies from `requirements.txt`.
3. Open the Jupyter notebook `Weapon Detection_Arnav Venkatesh.ipynb` and **Run All**.
4. A window titled **GUN DETECTOR** will open. Point the webcam at your test scene (or a video).
5. Press `q` to quit.

## Notes
- Camera index is set to `0` (internal webcam). Change if needed.
- Detection depends on the quality of the cascade and scene conditions; expect false positives/negatives.
- This repository is for educational/demonstration purposes only.

## Author
**Arnav Venkatesh**


