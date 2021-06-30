# Depth-map-for-stereo-images
## Goal:
    To create a depth map for stereo images
#### **Knowlegde of Epipolar geometery is required*
![img](https://user-images.githubusercontent.com/55583932/123922762-fb11a180-d9a5-11eb-83a8-9fc98289b906.png)


* If we have two images of same scene, we can get depth information from that<br />
![download](https://user-images.githubusercontent.com/55583932/123925004-1e3d5080-d9a8-11eb-98fa-199aab3e3a17.png)

### disparity=x−x′=Bf/Z<br />
Here,<br />
**x** and **x′** are the distance between points in image plane corresponding to the scene point 3D<br />
**B** is the distance between two cameras (which we know) <br />
**f** is the focal length of camera (already known)<br /><br />
**The above equation says that the depth of a point in a scene is inversely proportional to the difference in distance of corresponding image points(disparity)**<br />
## Results:
![Capture 1](https://user-images.githubusercontent.com/55583932/123926043-20ec7580-d9a9-11eb-8b64-99fe66841011.PNG)
![Capture](https://user-images.githubusercontent.com/55583932/123926100-2fd32800-d9a9-11eb-9f33-d6db5ca403ff.PNG)

