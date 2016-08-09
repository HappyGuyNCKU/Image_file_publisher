# Image_file_publisher
## OVERVIEW
This project is a ros package can provide two images as stereo camera topic.

## INSTALLATION
Download catkin tools: 

    $ sudo apt-get install python-catkin-tools

Create a catkin workspace:

    $ mkdir catkin_ws && cd catkin_ws

Clone this project into source folder:

    $ mkdir src && cd src
    $ git clone https://github.com/workfunction/Image_file_publisher

Leave sorce folder and build:

    $ cd ..
    $ catkin init
    $catkin build

Finally source the environment variable of bash:

    $ source devel/setup.bash

## USAGE
Simply runing the executable `my_publisher` in package and give him two image:

    $ rosrun image_transport_tutorial my_publisher <left_image> <right_image>
