# Instant-BndW-Sketch-From-Live-Cam
Here the main idea is to convert the image into a grayscale and then blur the background. Then we will add the black and white foreground to the blurred image. To separate the background we will be inverting the image and then we will blur it, and our final output will be a pencil sketch of the provided image or the frame recorded in the webcam.



Live Sketch Algorithm OpenCV
Capturing Real-time Video from the source example – computer’s camera
Reading each frame of the video, so that we can make manipulations on the frame.
Converting each frame from colored to grayscale, using OpenCV functions.
Making Use of Blurring on the grayscale image to remove all the noises on the picture/image. ( Gaussian Blur )
Detecting Edges of the blurred image, for making it like a sketch of the person or object. (Canny Edge)
Thresholding the Edge Detected image
