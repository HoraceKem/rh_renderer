# rh_renderer
This is a repo forked from [Rhoana](http://github.com/Rhoana/rh_renderer)

## Description
A Rhoana library that performs the rendering of images after applying both affine and non-affine transformations.
The available transformations are part of the models defined in this library.
This package also renders tilespecs.

## Installation
### Install OpenCV3(Check your PKG_CONFIG_PATH if you have installed before)
```
$ conda create -n YOUR_ENV python=3.7
$ conda install opencv=3.4
$ export PKG_CONFIG_PATH=/path/to/conda envs/YOUR_ENV/lib/pkgconfig/
```
**Tips:**
   - **DON'T** use OpenCV2.x because of python3.
   - **DON'T** use OpenCV4.x because there are some significant changes that could lead to conflicts.
   - A later version will support OpenCV4.
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

