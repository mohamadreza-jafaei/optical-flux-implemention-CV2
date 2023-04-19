## Optical Flow Implementation using OpenCV
This project implements optical flow using OpenCV and three different algorithms: Shi-Tomasi, Lucas-Kanade, and Gunner-Farneback. Optical flow is a technique for estimating the motion of objects in a video stream by analyzing the changes in pixel intensities between consecutive frames.

Installation
To use this project, you will need to have OpenCV installed on your system. You can install OpenCV using pip:

Copy code
pip install opencv-python
Usage
To run the optical flow algorithms on a video file, use the optical_flow.py script:

css
Copy code
python optical_flow.py --algorithm shi-tomasi --input_path /path/to/video/file
This will run the Shi-Tomasi optical flow algorithm on the specified video file. You can replace shi-tomasi with lucas-kanade or gunner-farneback to use a different algorithm. You can also specify the output file path using the --output_path argument (default is output.avi).

Results
The output of the optical flow algorithms is a video file that shows the estimated motion vectors overlaid on the original video frames. Here are example results for each algorithm:

Shi-Tomasi
Shi-Tomasi Optical Flow

Lucas-Kanade
Lucas-Kanade Optical Flow

Gunner-Farneback
Gunner-Farneback Optical Flow

Credits
This project is based on the OpenCV library and the following research papers:

Shi, Jianbo, and Carlo Tomasi. "Good features to track." IEEE Conference on Computer Vision and Pattern Recognition, 1994.
Lucas, Bruce D., and Takeo Kanade. "An iterative image registration technique with an application to stereo vision." International Joint Conference on Artificial Intelligence, 1981.
Gunner, Farneback. "Two-Frame Motion Estimation Based on Polynomial Expansion." Scandinavian Conference on Image Analysis, 2003.