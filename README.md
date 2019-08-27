Video loading works with sdl2

Dense SLAM vs feature based SLAM

Using ORB features (https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_orb/py_orb.html"

## Epipolar geometry
https://www.robots.ox.ac.uk/~vgg/hzbook/hzbook2/HZepipolar.pdf
Epipolar Geometry and the Fundamental MatrixThe epipolar geometry is the intrinsic projective geometrybetween two views.  It isindependent of scene structure, and only depends on the cameras’ internal parametersand relative pose.The fundamental matrixFencapsulates this intrinsic geometry.  It is a3×3matrixof rank 2. If a point in 3-spaceXis imaged asxin the first view, andx′in the second,then the image points satisfy the relationx′TFx= 0.