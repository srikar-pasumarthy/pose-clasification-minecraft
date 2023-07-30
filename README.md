# Using Pose Recognition to play minecraft

## Setup

### Installing Libraries
There are 3 libraries that you need to install: opencv, pyautogui, and mediapipe. To install run:
```bash
pip install pyautogui
pip install mediapipe
pip install opencv-python
```
If you can execute the first cell in _pose_detection.ipynb_ without any errors then you can move on.

### Connecting python to minecraft
Go ahead and start minecraft and jump into a new world. Once you have everything launched, you can run all the remaining cells in _pose_detection.ipynb_ and you can jump back into minecraft.

### Movement/Keys
At the moment, I have it programmed so that...
- **Saluting with right arm** moves the player to the right
- **Saluting with left arm** moves the player to the left

## TODO
- Speed up pyautogui as it is the bottleneck
- Add more controls
