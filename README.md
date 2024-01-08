# OpenCV ARUCO Angle Estimation
Real time angle estimation - https://youtu.be/pdwWh23FgnE


## Install OpenCV ARUCO package
`pip install opencv-contrib-python`  

## Install keyboard package
`pip install keyboard`  

## Run
`python video.py`  

## Testing
- Generation ARUCO Page: https://chev.me/arucogen/  

- Images:  
![21](5x5_1000.jpg)  

## Note
- If you have many cameras (real or virtual) connect to the computer, specify one that you want by changing camera-id in the video.py file from 0 to 1 or 2, etc.  
`cap = cv2.VideoCapture(0)`
