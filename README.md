# rh_renderer
This is a repo forked from [Rhoana](http://github.com/Rhoana/rh_renderer)

## Description
A Rhoana library that performs the rendering of images after applying both affine and non-affine transformations.
The available transformations are part of the models defined in this library.
This package also renders tilespecs.

## Installation
### (Optional)Install OpenCV
1. Download the source codes of [OpenCV](https://opencv.org/releases/).
2. Follow the [tutorial](https://docs.opencv.org/master/d7/d9f/tutorial_linux_install.html).
Notice the optional **step 6** when building OpenCV from source using Cmake.
```
Add this flag when running CMake: -DOPENCV_GENERATE_PKGCONFIG=ON
```
### Install tinyr
Refer to the repo [tinyr](https://github.com/HoraceKem/tinyr).
### Install this repo
```
$ git clone git@github.com:HoraceKem/rh_renderer.git
$ cd rh_renderer/
$ pip install -r requirements.txt
$ pip install --editable .
```

## Usage

TODO.

