# ros_logicam
A ROS package for logitech webcams

sudo apt-get install ros-<distro>-audio-common

git clone https://github.com/ros-drivers/usb_cam.git

https://unix.stackexchange.com/questions/512759/multiple-dev-video-for-one-physical-device

https://wiki.openrobotino.org/index.php?title=USB_cameras

ls /dev/video*
udevadm info --query=all --attribute-walk --name=/dev/video0

nano /etc/udev/rules.d/99-camd2.rules