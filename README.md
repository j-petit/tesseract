# tesseract
This branch is a reduced fork of Tesseract to be used for building the experimental MoveIt Bullet collision checking. See this [issue](https://github.com/ros-planning/moveit/issues/1427) for more information. 

The new planning framework (Tesseract) was designed to be lightweight, limiting the number of dependencies, mainly to only used standard library, eigen, boost, orocos and very few external ROS packages. It currently contains seven packaged described below:

* **tesseract_msgs** – This package contains the ROS message types used by Tesseract.

*WARNING: These packages are under heavy development and are subject to change.*

## Clone Repository

This repository contains submodules so use the *--recursive* flag as shown below.

`git clone --recursive`

## Build Branch Sphinx Documentation

```
cd gh_pages
sphinx-build . output
```
Now open gh_pages/output/index.rst and remove *output* directory before commiting changes.
