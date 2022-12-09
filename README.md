# Raytracer

A program that creates images from scratch using a number of complex lighting and rendering effects.

First objects are defined in a scene. 
Then raytracing is used to produce realistic & lifelike lighting effects.

## Motivation

This project was created as a submission for [CSC418 - Spring, 2018] at the University of Toronto. The final code & project structure has been modified.

The contributors to this submission were myself, Oliver Straszynski, and Jacob Ritchie.

Some of the code was provided to us as setup (`bmp_io` , `scene_object` , `main`, others), and attribution to the original code authors is made on those individual files.

## Effects & Optimizations

### Octree Optimization

![TestImage](https://github.com/broliver12/raytracer/blob/master/images/octree.jpg)

### Environment mapping

### Cube Mapping

### Ambient Diffuse & Specular Reflection

### Anti Aliasing

## Usage

- Install g++

- execute `make -f Makefile clean`

- execute `make -f Makefile raytracer`

- execute `./raytracer`

- See output in `/output_images`

## License

This project is provided open source under the following MIT license.