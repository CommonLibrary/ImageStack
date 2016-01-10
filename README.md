# ImageStack
ImageStack is a command-line stack calculator for images, developed in the Stanford Graphics Lab by Andrew Adams and other members of Marc Levoy's group.
ImageStack supports a wide variety of image processing operations, including recent techniques from the computational photography literature.Indeed, its 
key design goal is to make it easy to implement and experiment with new image processing techniques, in an adequately compute- and memory-efficient manner.
It is easily extensible with new operations, and is suitable for use on the command line, in scripts, or by linking to it as a library.
ImageStack represents all images as four-dimensional arrays of floating point data, where the four dimensions are space, time, and color channel.
This makes it suitable for processing bursts of images, high-dynamic range data, and more general scientific computing.
In many respects, ImageStack is like matlab, but more specialized towards images, somewhat leaner, and entirely on the command line.
