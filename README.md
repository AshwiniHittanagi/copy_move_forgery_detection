# copy_move_forgery_detection
Implementation of a copy move forgery algorithm based on algorithm in Fridrich's paper in 2003. 

This is a program for determining if an image was a victim of copy-move forgery. The program accepts an image and two arguments (quality factor and threshold). After analyzing an image, the program outputs an image with the expected copy-move regions highlighted.

The main purpose of this project was to highlight an expected deficiency of this approach to forgery detection - this algorithm (due to the discrete cosine transform) is not invariant to any rotation or scaling in the copy-move region.
