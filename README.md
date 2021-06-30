# Depth-map-for-stereo-images
## Goal:
    To create a depth map for stereo images
#### **Knowlegde of Epipolar geaometery is required*
![img](https://user-images.githubusercontent.com/55583932/123922762-fb11a180-d9a5-11eb-83a8-9fc98289b906.png)


* If we have two images of same scene, we can get depth information from that<br />
![download](https://user-images.githubusercontent.com/55583932/123925004-1e3d5080-d9a8-11eb-98fa-199aab3e3a17.png)

### disparity=x−x′=Bf/Z<br />
Here,<br />
**x** and **x′** are the distance between points in image plane corresponding to the scene point 3D<br />
**B** is the distance between two cameras (which we know) <br />
**f** is the focal length of camera (already known)<br />
The above equation says that the depth of a point in a scene is inversely proportional to the difference in distance of corresponding image points(disparity)<br />
