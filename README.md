# V4L2_ImageCapture
Capture images from V4L2 compatible video devices.

Simply install:
sudo pkg install v4l_compat v4l-utils

or:
sudo apt-get install libv4l-dev

and run:
gcc getimage.c -Wall -o getimage && ./getimage -o -c 1 && eom output.bmp

