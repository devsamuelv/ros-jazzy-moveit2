FROM osrf/ros:jazzy-desktop-full

ENV ROS_DISTRO=$ROS_DISTRO
ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt -y --no-install-recommends install clangd clang git make

RUN echo "source /opt/ros/jazzy/setup.bash" >> /etc/bash.bashrc

RUN apt install -y ros-jazzy-moveit ros-jazzy-ros2-control ros-jazzy-ros2-controllers
RUN apt update