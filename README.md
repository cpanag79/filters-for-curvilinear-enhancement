# Filters for curvilinear enhancement

Step filtering and Polynomial filtering for enhancement of partial curvilinear structures

Matlab Code: https://www.mathworks.com/matlabcentral/fileexchange/46541-filters-for-curvilinear-enhancement

This code is an implementation of the Step filtering and the Polynomial filtering method proposed in [1]
providing an enhancement on partial curvilinear structures.
The method was applied on geophysical images in an effort to recognize the linear patterns
of subsurface architectural structures that exist in archaeological sites [1].
This method efficiently combines a rotation
and scale-invariant filter and a pixel-labeling method, providing
a robust enhancement and detection of mostly line structures in
2-D grayscale images, respectively. This is the code for the rotation and scale-invariant filter [1], [2].
You can find more details in
www.csd.uoc.gr/~cpanag

Usage: runFiltering.m : An example to run the function step_pol_filtering (Step filtering and Polynomial filtering)
data.mat : A synthetic magnetic image (see [1]) used for testing
dataR.mat: A real magnetic image (see [1]) that can be used for testing

It returns the filter output that provides an enhancement on partial curvilinear structures.

We will appreciate if you cite our paper in your work.
[1] C. Panagiotakis, E. Kokinou and A. Sarris, Curvilinear Structure Enhancement and Detection in Geophysical
Images, IEEE Trans. on Geoscience and Remote Sensing, vol. 49, no. 6, pp. 2040-2048, 2011.

[2] C. Panagiotakis and E. Kokinou, Linear Pattern Detection of Sea Faults via a Topology and Shape Optimization Method, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 8, no. 1, pp. 3-11, 2015.
