# OpenCV_ImageProcessing **WIP**

This project is intended to detect the face and eyes of a person getting the images from PC camera and sending it through a ROS topic. OpenCV 2.4.9 is the library that will be used for doing it.

The following templates, contained on *src* folder, are the base for this project:

1. opencv_template_node: This is the base template wich serves as an example of how OpenCV works with images, it contains the basic processing from taking the images by subscribing to camera node, converting them from ROS format to OpenCV format
, drawing an example circle, showing the processed image and publishing it trough a ROS topic, for wich it is necessary to convert to ROS format again.
2. opencv_template_node_hh: This template is pretty the same than the previous one, but implementing some defines and improving the original documentation.
3. opencv_grayImage_hh: This template shows how to convert an RGB color image to a gray scale one, for wich it uses cvtcolor function.
4. 
