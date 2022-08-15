# 3d-Math-Java
An extensive 3d math package, well suited for games, 3d rendering or general math applications. 
This is what I used for my [3d renderer](https://github.com/trrt-good/3d-Rendering-JAVA) project.

## Features:

### [Quaternion](https://github.com/trrt-good/3d-Math-Java/blob/main/Quaternion.java):
- axis-angle conversion to quaternions
- euler angle conversion to quaternion
- inverse calculation
- multiplcation function

### [Matrix3x3](https://github.com/trrt-good/3d-Math-Java/blob/main/Matrix3x3.java):
- determinant 
- cofactor 
- adjugate  
- inverse 
- matrix multiplication
- component-wise multiplication
- rotation matrix creation for each axis
- rotation matrix creation for axis angle representations

### [Vector3](https://github.com/trrt-good/3d-Math-Java/blob/main/Vector3.java):
- magnitude calculation
- normalization
- all basic operations
- quaternion conversion
- dot product
- cross product
- lerp method 
- matrix multiplcation
- plane intersection calculation
- projection to planes
- projection to vectors
- distance to a line
- distance to a plane
- angle between two vectors
- unit vector creation from pitch and yaw angles
- rotation methods for x y z axis
- rotation method for axis angle representation
- rotation method using quaternions

### [Plane](https://github.com/trrt-good/3d-Math-Java/blob/main/Plane.java)
(mainly just an object used by the [Vector3](https://github.com/trrt-good/3d-Math-Java/blob/main/Vector3.java) class)
- calculating the paramtetric equation representation for a plane
